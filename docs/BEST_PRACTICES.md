# Angular best pratices

## Usage of module

Modules are used to structure our application.
We identified two main cases where the usage of modules are  recommended:

- To take advantage of lazy-loading

- To create functional modules which will helps in managing development of the application

Loading modules on demand helps minimize the amount of code that needs to be loaded at startup.

This mecanism is very useful and can be used to lazy load a functionnal module (e.g an Admin module which can set a functionnal boundary and also be lazy loaded )

## Usage of Class vs Plain Old Javascript Object

This project and the Angular Framwork make an extensive use of ES6 and Typescript syntax.
We prefer the usage of Class and/or Interface **with defined type** to refer to our data, this way we can:

- Cleary identify object and type  
- Fully use autocompletion feature
- Avoid improper use of some data

## Usage of Angular Test Bed

Usage of Angular Test Bed is not mandatory. Keep in mind that Angular Component can be tested as simple classes if you dont check template or use intensive DI.

Testing with Angular Test Bed can quickly become ressource heavy and slow if you require lots of modules and/or trigger manually detect changes using `fixture.detectChanges()`

Some rule of thumb regarding Angular Test Bed are:

- if you are testing no Angular classes (e.g. utilitary class or models) => do not use Angular Test Bed
- if you don't need to test template and dont use DI => do not use Angular Test Bed
- if you don't need to test template => use TestBed with `CUSTOM_ELEMENTS_SCHEMA` or `NO_ERRORS_SCHEMA`

``` javascript
      TestBed.configureTestingModule({
      ...
      schemas: [CUSTOM_ELEMENTS_SCHEMA]
      })
```

- if you rely heavily on DI try to maximaxize the usage of mocks
- otherwise if you notice an overhead on time exectution you can prevent the default before each recompile and module loading with tools like [ng-bullet](https://www.npmjs.com/package/ng-bullet)

On this subject you can also watch [You're Testing Your Angular Code Wrong (Probably)](https://www.youtube.com/watch?v=7JucMlrs3dQ)

## Usage of Constructor vs Angular NgOnInit

**WIP**
