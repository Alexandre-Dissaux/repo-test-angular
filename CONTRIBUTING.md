# Contributing to AEF-Portail-Agent

[Return to AEF-Portail-Agent main page](/README.md)

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to AEF-Portail-Agent.
These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[I don't want to read this whole thing, I just have a question!!!](#i-dont-want-to-read-this-whole-thing-i-just-have-a-question)

[What should I know before I get started?](#what-should-i-know-before-i-get-started)
  * [AEF-Portail-Agent](#AEF-Portail-Agent)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Pull Requests](#pull-requests)

[Styleguides](#styleguides)
  * [Git Workflow](#git-workflow)
  * [Git Commit Messages](#git-commit-messages)
  * [Specs Styleguide](#specs-styleguide)

[Additional Notes](#additional-notes)

## I don't want to read this whole thing I just have a question!!!

> **Note:** [Please don't file an issue to ask a question.] You'll get faster results by using the resources below.

You can join the AEF-Portail-Agent team:

* [Join the AEF-Portail-Agent Team](http://anef.scille.eu/matrix/#/vls-ts/contact)
  * Sometimes it takes several hours for team to respond &mdash; please be patient!

## What should I know before I get started?

### AEF-Portail-Agent

[You can check the README](README.md)

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report. Following these guidelines helps maintainers understand your report :pencil:, reproduce the behavior :computer: :computer:, and find related reports :mag_right:.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). Fill out [the required template](ISSUE_TEMPLATE.md), the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting A Bug Report

* **Check the tag version** Be sure to use the latest version of AEF-Portail-Agent.
* **Perform a [search](https://github.com/Scille/AEF-Portail-Agent/issues)** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've checked there is no existing issue your bug is related to, create an issue and provide the following information by filling in [the template](ISSUE_TEMPLATE.md).

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how you used AEF-Portail-Agent, e.g. which command exactly you used in the terminal, or how you used AEF-Portail-Agent otherwise. When listing steps, **don't just say what you did, but explain how you did it**. For example, if you clicked on a button, explain if you used the mouse, or a keyboard shortcut, and if so which one?
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots** which show you following the described steps and clearly demonstrate the problem.
* **If you're reporting that AEF-Portail-Agent crashed**, include any crash report with a stack trace from the operating system or console errors. Include the crash report in the issue in a [code block](https://help.github.com/articles/markdown-basics/#multiple-lines), a [file attachment](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/), or put it in a [gist](https://gist.github.com/) and provide link to that gist.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Did the problem start happening recently** or was this always a problem?
* If the problem started happening recently, **can you reproduce the problem in an older version of AEF-Portail-Agent?** What's the most recent version in which the problem doesn't happen?
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

Include details about your configuration and environment:

* **Which version of AEF-Portail-Agent are you using?**
* **What's the name and version of the OS you're using?**
* **What's the name and version of the webbrowser you're using?**
* **Are you running AEF-Portail-Agent in a virtual machine?** If so, which VM software are you using and which operating systems and versions are used for the host and the guest?

### Pull Requests

* Fill in [the required template](PULL_REQUEST_TEMPLATE.md)
* Include issue numbers in the PR title
* Include screenshots and animated GIFs in your pull request whenever possible.
* Follow code rules in [docs](/docs) before opening a PR.
* Your branch must be based on and up-to-date with `develop`
* Your branch name must :
    * begin with the ticket number if there's one
    * begin with hotfix if this is a quick fix without ticket
    * have each word separated with a `-`
    * in english
* End all files with a newline
* Place imports in the following order:
    * Built in Angular Modules (such as `@angular/core`)
    * External Modules (such as `ng2-translate`)
    * Shared Modules (such as `../shared/i18n.module.ts`)
    * Global Resources (such as `../environments/environment`)
    * Local Modules (using relative paths)

## Styleguides

### Gestion du CHANGELOG

Format des entrées dans le CHANGELOG_UNRELEASED :
- <ID_JIRA>: <Libellé ticket JIRA>

Exemple :
- NAT-232: Mot de passe expiré

### Git Workflow

We follow [gitflow rules](https://leanpub.com/git-flow/read).

So, when you start working on a new thing (feature, bug fix, refactoring…), you should create a dedicated branch from the `develop` branch.

You can open a pull request (PR) at anytime to generate discussions.

PR are reviewed technically by other developers, functionally by the Product Owner, then merged into the `develop` branch.

`qualif` is our release branch.

`master` is our (pre-)production branch.

### Git Commit Messages

There is no enforced rule but you can read these inspirational links:
- [How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/)
- [Semantic Commit Messages](https://seesparkbox.com/foundry/semantic_commit_messages)

### Specs Styleguide

- Include thoughtfully-worded, well-structured [Jest](https://jestjs.io/docs/en/getting-started) specs in the `/specs` folder.
- Treat `describe` as a noun or situation.
- Treat `it` as a statement about state or how an operation changes state.

### Naming

- You are invited to refer to the [business glossary](https://scille.atlassian.net/wiki/spaces/SIEF/pages/16384045/Glossaire+g+n+ral+et+liste+des+applications+existantes) (in french) of the application in order to choose a coherent name for your functions and variables.

## Additional Notes

To see specifically how to code on the project : [see coding style](/docs/CODING_STYLE.md)

For any information you can't find here, you can contact the dev team.
