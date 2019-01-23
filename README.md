# FooLib

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.2.1.

# Step to reproduce issue

npm install
ng build foo-lib
ng serve foo-tester **To launch test application in order to verify library is build and included correctly**
cd dist/foo-lib
npm link

Next step in application-tester project ReadMe

N.B. in test application module route is added and we can navigate to main_path/child'


#SOLVED
See README file of foo-tester project.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
