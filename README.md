# PokeTeams

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.2.

## Main commands

To run locally:

 `ng serve --open`

To generate `dist` folder to deploy into Production:

 `ng build --prod --bh ./`

## Running Legacy app

There may be issues running this webapp if you have installed the latest versions of NodeJS and angular-cli. Downgrading angular-cli version to 6.0.x may be required. The following commands will help to run this Angular 5 (legacy) app:

 `npm install --legacy-peer-deps`

 `npm uninstall -g @angular/cli`

 `npm cache clean --force`

 `npm install -g @angular/cli@6.0.8`

 `ng serve --open`

To generate dist files (build the webapp):

 `export NODE_OPTIONS=--openssl-legacy-provider`

 `ng build --prod --bh ./`

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
