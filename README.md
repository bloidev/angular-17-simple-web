# SimpleWeb

# Creando este template desde 0 | angular 17

```sh

# instala la versión de nodejs v18.16.0 puedes usar nvm en windows, para administrar versiones de node.
# instala el @angular/cli
> npm install -g @angular/cli

# Comprueba la versión instalada con:
> ng version

# creemos nuestra primera app
> ng new simple-web

# completamos los datos que nos ira solicitando
> ng new simple-web
? Which stylesheet format would you like to use? *CSS*
? Do you want to enable Server-Side Rendering (SSR) and Static Site Generation (SSG/Prerendering)? *Yes*
# lo anterior creara el proyecto con la estructura de angular e instalará los packages.
# ingresamos a nuestro proyecto con
> cd simple-web
# y levantamos servidor local
simple-web> ng serve

Global setting: enabled
Local setting: enabled
Effective status: enabled

Initial Chunk Files | Names         |  Raw Size
polyfills.js        | polyfills     |  82.71 kB | 
main.js             | main          |  23.49 kB | 
styles.css          | styles        |  95 bytes | 

                    | Initial Total | 106.29 kB

Application bundle generation complete. [11.554 seconds]
Watch mode enabled. Watching for file changes...
  ➜  Local:   http://localhost:4200/
```

# Angular Readme

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.0.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
