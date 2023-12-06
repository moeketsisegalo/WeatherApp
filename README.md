# MyWeatherApp

This project is a weather application generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.0.

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

## RapidAPI Weather API Configuration

To integrate with the RapidAPI weather API, this Angular application relies on specific configuration settings. Below is an overview of the key configuration parameters stored in the `environment.ts` file.

### Environment Configuration

```typescript```
// src/environments/environment.ts

export const environment = {
    production: false,
    weatherApiBaseUrl: 'https://weatherapi-com.p.rapidapi.com/current.json',
    XRapidAPIHostHeaderName: 'X-RapidAPI-Host',
    XRapidAPIHostHeaderValue: 'weatherapi-com.p.rapidapi.com',
    XRapidAPIKeyHeaderName: 'X-RapidAPI-Key',
    XRapidAPIKeyHeaderValue: '035b854d26mshce7d8592f07d0c1p10e77fjsn78af0be4bbbe'
};

### Configuration


Before running the application, make sure to configure the API key in the appropriate configuration files. Typically, this involves updating a configuration file with your RapidAPI key.

// src/app/config/api.config.json
{
  "rapidApiKey": "your_rapidapi_key_here"
}
