# AEF-Portail-Agent

Web application used by prefecture agents to process foreigners requests to acquire a temporary residence permit in France.

## Table of Contents

- [Technologies](#technologies-used)
- [Setup](#get-started)
- [Install new packages](#install-new-packages)
- [How to ? (commands)](#how-to--commands)
- [How to contribute ?](#how-to-contribute-)
- [License](#license)

## Technologies

- [Angular (v7)](https://angular.io/) as the framework, with [TypeScript](https://www.typescriptlang.org/)
- [PrimeNG](https://www.primefaces.org/primeng) as UI components for Angular
- [Moment.js](https://momentjs.com/) for easier way to handle dates and times
- [SASS](http://sass-lang.com/) as CSS preprocessor
- [Jest](https://github.com/facebook/jest) as testing framework
- [Angular CLI](https://github.com/angular/angular-cli) as CLI tool to generate, serve and build files

## Setup

Install [node and npm](https://nodejs.org/en/download/).

> Note: the project works with node v12.x (LTS) and npm v6.x. If you have troubles with installation or commands, check these versions.

Before installing dependencies, you need to create an [SSH key] (https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) don't type a secure passphrase then add the public key to github.

Install dependencies with `npm install`.

If not already done, install `angular-cli` globally with `npm install -g @angular/cli`.

You need to install the [Sief back-end](https://github.com/Scille/sief-back) and make it run to consume its APIs.

You can install Robot 3T to see your database. (https://robomongo.org/)
Or if you use VsCode you can add the package mongodb for vscode (https://code.visualstudio.com/docs/azure/mongodb)

For the moment, you also need an up and running __sief-front__ to handle authentication and credentials. Referer to [sief-front README](https://github.com/Scille/sief-front/blob/develop/README.md) and this [installation procedure](https://scille.atlassian.net/wiki/spaces/SIEF/pages/813432838/Cohabitation+du+Portail+Asile+Dublin+et+Portail+S+jour+Agent) for further installation instructions like nginx.

API URL is configured [as an environment variable](https://github.com/Scille/aef-portail-usager/tree/master/src/environments). It follows
back-end default conventions.

> Note: If you want to run your custom environment − e.g. to change the API port you use − you can create `src/environments/environments.local.ts`. It won't be versioned. Then, simply run `npm run start:local` to launch your application.

## Install new packages

We want to prevent the CI to fail if a sub-dependency does upgrade to an unexpected version.

To do so, we've locked dependencies versions with [package-lock](https://docs.npmjs.com/cli/v6/configuring-npm/package-lock-json).

This is transparent if you use `npm install --save` and `npm install --save-dev` to install new packages.
Don't forget to commit the updated `package-lock.json` along the `package.json` when you do so.

## Parameters list (feature flipping and global environment variables)

[See parameters list](/docs/PARAMETERS.md)

## How to ? (commands)

[See command list](/docs/COMMANDS.md)

## How to contribute ?

[See contributing](CONTRIBUTING.md)
[See coding style](/docs/CODING_STYLE.md)
[See best practices](/docs/BEST_PRACTICES.md)
