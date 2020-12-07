# AngularWebApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.1.

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

# Learning

## Angular.json
Workspace configuration is created at the top level of the workspace.
This is where you can set per-project defaults for CLI comand options, and specify configurations to use when the CLI builds a project.

## Package.json
Configures npm package dependencies that are available to all projects in the workspace.

## Package-lock.json
Provides version information fo all packages intalled into node_modules by npm client.

## Karma.conf.js

Is a Partial Karma configuration file. The CLi constructs the full runtime conf in memory.

## Tsconfig.json

The base Typescript configuration for projects in the workspace. All other conf files inherit form this base file. 

## Tslint.json

Default TSLit conf for the projects. TSLint will be deprecated and ESLint as standard linter for both TS and JS.

## Interpolation Binding Sintax {{}}

It allows to present a component's property directly inside a HTML Tag.

## @Component 

Is adecorator function that specifies the Angular metadata for component

## Data Binding in Angular

1. Event binding (When information flow from the view to the component when an event is triggered)
2. Two-way data binding (Is a mechanism where data flows both ways from the component to the view and back)
3. Interpolation (Text representing variables in components are placed  in between double curly braces in the template)
4. Property Binding (Lets you set the property of a view element, it uses [] syntax)

## FormsModule

Export the required providers and directives for template-driven forms.