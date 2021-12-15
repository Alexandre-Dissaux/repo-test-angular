# Coding Style

[Return to AEF-Portail-Agent main page](/README.md)

We follow recommendations from the [Angular style guide](https://angular.io/docs/ts/latest/guide/style-guide.html).

## Referencing a template reference variable

> From [Angular Template Syntax](https://angular.io/docs/ts/latest/guide/template-syntax.html#!#referencing-a-template-reference-variable)

To avoid confusion with data variables, we do suffix template variables with `Elt`.

Don't do that:
```html
<!-- phone refers to the input element; confused with the phone number variable -->
<input #phone placeholder="Example: {{phone}}">
<button (click)="callPhone(phone.value)">Call</button>
```

Do this:
```html
<!-- phoneElt refers to the input element without ambiguity -->
<input #phoneElt placeholder="Example: {{phone}}">
<button (click)="callPhone(phoneElt.value)">Call</button>
```

## Writing tests

Before going any further, a few considerations to remember.
Each class should have it's own responsibility, and not trespass on the responsibilities of other classes.
The components' responsibility is to manage the DOM, thus should avoid manipulating data as much as possible and delegate API requests and data formatting to services.
In our Angular app, services can be global or local. A global service will usually be a kind of helper class. It can be used by several components (or even other services). A local service will be placed in a components' folder and be only used by that component to delegate some methods and treatments.  

### Testing components
As previously determined, a component is responsible to manage the DOM.
We will mount the component with it's template and simulate actions on the DOM in order to test the consequential results of these actions.
Since this kind of test checks how the template and the component work together, we characterize them as Integration Tests.

#### TestBed and style
Angular components are tested with TestBed, a module which allows to instanciate and configure a component in the context of an unit test or an integration test.
Here is an example :
```javascript
beforeEach(() => {
  TestBed.configureTestingModule({
    imports: [
      FormsModule,
      ErrorModule
    ],
    declarations: [MyComponent],
    providers: [
      TitleService,
      ContactService,
      {provide: ApiService, useClass: ApiServiceStub}
    ]
  })
    .compileComponents();
 
  this.fixture = TestBed.createComponent(MyComponent);
  this.component = this.fixture.componentInstance;
  this.injector = getTestBed();
  this.title = this.injector.get(TitleService);
  this.contact = this.injector.get(ContactService);
  this.apiService = this.injector.get(ApiService);
});
```
The `getTestBed()` method finds the instance of the TestBed injector, we use it to keep the injector as a reference to use in our test context
The `injector.get()` method finds the instance of an injected dependency from the component.

#### Async
The `async` utility tells Angular to run the code in a dedicated test zone that intercepts promises.
`fixture.whenStable()` allows us to wait until all promises have been resolved to run our expectations.

Here is an example :
```javascript
it('should display title', async(() => {
    debugElement
      .query(By.css('.set-title'))
      .triggerEventHandler('click', null);
 
    fixture.whenStable().then(() => {
      fixture.detectChanges();
      const value = debugElement.query(By.css('h1')).nativeElement.innerText;
      expect(value).toEqual('One crazy app!');
    });
  }));
});
```

**ALERT** We do not use Async, see further for details


#### fakeAsync and his good friend tick
`async`'s principal drawback is that we have to explicitly wait for the resolution of all promises before going further, which can really slow the testing process.
`fakeAsync` offers a nice solution to that problem by transforming the asynchronous code into synchronous code.

Here is an example : 
```javascript
it('should increment in template', fakeAsync(() => {
  debugElement
    .query(By.css('button.increment'))
    .triggerEventHandler('click', null);
 
  tick();
  fixture.detectChanges();
 
  const value = debugElement.query(By.css('h1')).nativeElement.innerText;
  expect(value).toEqual('1');
}));
```
The `tick()` method is used to fake the passage of time. If called with no argument, it asks the test runner to wait for all micro tasks to be finished (waiting for all promises to resolve for example).
It is also possible to give a value in milliseconds to fake the duration of that value.


### Basic principles

#### Double testing
A feature concept should not be tested in both integration (component) and unit (service) tests.
Both test types should complete each other.

#### Negative assertions
Negative assertions (notToBe, notToEqual) should be avoided since they are hard to read and unreliable in most cases.
These tests can almost always be (better) written with positive assertions.

#### One test per concept
Multiple assertions can and should be regrouped in one unique test if these assertions verify the same testing concept (an expected behavior depending on a given context).

#### Naming convention
It is not always necessary to include the mention `service` in the variable name of a service and is often superfluous. Think twice about your variable names.

### Mocks, stubs, spies and fakeObjects

#### Spies
A spy, as its name implies, is the encapsulation of a real object or class, decorated with methods allowing to spy on its behavior without modifying it.

#### Stubs
A stub is used to fake the behavior of a method or an object by decorating it with the same methods than a spy in order to observe said behavior.

#### Mocks
A mock replaces completely a real object or class with a fake one and offers no-op responses to some of its methods.

#### Jasmine and Jest
In Jasmine, the line between spy and stub is very narrow. Both are created with the `spyOn()` method.
`spyOn(object, 'method')` creates a spy of that method.
`spyOn(object, 'method').and.returnValue('value')` creates a stub of that method and returns the value passed in argument of `returnValue()`.
Jest, which is built upon Jasmine, follows the same principle

#### Jest Manual Mocks
Manual mocks are used to stub out functionality with mock data.
Manual mocks are defined by writing a module in a `__mocks__/` subdirectory immediately adjacent to the module.
For example, if we want to mock Angular's `environments/environment.ts` file, we can create an `environments/__mocks__/environmnet.ts` mock.
It will be applied to the test context by declaring `jest.mock('module-or-file-to-mock')`. In our example : `jest.mock('<route-to-src>/environments/environment.ts')`

## Code Reviews
A few rules about code reviews : 
- A branch is reviewed as soon as possible and as much as possible.
- Reviewers should carry out acceptance testing by deploying the branch under review onto a feature environment.
- The review should be done with the `Contributing` document on hand.
