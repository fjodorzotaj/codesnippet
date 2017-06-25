# Codesnipped application

This project was created with the MEAN stack and generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.1.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:3000/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|module`.

## Install the required modules with npm

Run `npm install`, to install the Angular packages

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## MongoDB as the NoSQL database backend

As the NoSQL MongoDB from mlab.com is used. The MongoDB sample collection is in `mongo.txt`. You can create a new collection in mlab.com and import the content of mongo.txt file. The mlab connection configuration is in the file `api.js` inside the folder `/server/routes`

mongodb://user:password@host.mlab.com:35532/dbname

## First setup and installation
`node -v`  make sure that node is installed
`npm -v`   make sure that npm packager is installed
`npm install -g @angular/cli` make sure that angular is installed, otherwise install it with npm
`npm install --save express body-parser`  install the required express and body-parser
`npm install` install the required angular packages
`ng build` to build the project
`node server.js` to start the application which will be accessible in `http://localhost:3000`

Port can be changed in the `server.js` file

`const port = process.env.PORT || '3000';`

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Todo list

1. Registration and login page
2. Search bar with search page
3. Payment module with Paypal
