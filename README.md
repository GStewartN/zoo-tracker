# Zoo Tracker

Epicodus-JavaScript, Week 3 Independent Project, 08.18.2017

_By Nathan Stewart_

## Description

This app is a basic zoo animal tracker for zookeepers. Users can add, list, and edit animals.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.3.0.

## Prerequisites

You will need the following things properly installed on your computer.

* [Node.js](https://nodejs.org/) (with NPM)
* [Angular CLI](https://github.com/angular/angular-cli) version 1.3.0.

## Configuration/Dependencies

* angular-cli
* bower
* bootstrap

The app will use angular-cli and assets and dependencies packaged with it.

## Setup/Installation

* `$ git clone <repository-url>` this repository
* `$ cd zoo-tracker`
* `$ npm install`
* `$ bower install`

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
Before running the tests make sure you are serving the app via `ng serve`.

## Specifications

| Behavior | Input | Output |
|----------|-------|--------|
| add animal to list | user fills out add animal form and clicks add button | new animal displays in current animal residents list |
| edit animals | user clicks an animal edit button, makes changes in the form, and clicks done | animal displays in current animal resident list with new values |
| filter animals | user chooses one of the filter options from dropdown list | resident animal list displays only animals that meet filter parameters |

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

### License

MIT License

Copyright &copy; 2017 Nathan Stewart

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
