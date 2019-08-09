# AngularI18n

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.0.6.


## Getting Started

1. mark html element with personal tag i18n (e.g. `i18n="<meaning>|<description> @@myId"`)
2. run `ng xi18n --output-path src/locale`
3. create a copy messages.xlf (e.g. messages.it.xlf)
4. add <source> tag with relative translation
5. in angular.json add in build ann serve part the specific configurations:it 
6. `npm run start` for normal version
7. `npm run start:it` in this case, for it version
8. that's all folks :)

[official guide](https://angular.io/guide/i18n#internationalization-i18n)

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
