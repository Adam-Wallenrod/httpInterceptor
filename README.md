# Httpinterceptor

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.3.

The project is an example of angular http interceptor. In general HTTP Interceptor allows to catch HTTP
requests and responses which then you can easily modify. The following example uses interceptor in order 
to catch all outgoing requests and incoming responses and log them in the console.

First button triggers method1Call() which sends a request for users (https://jsonplaceholder.typicode.com/users)
Second button triggers method2Call() which does pretty much the same thing. However the request contains a wrong url.
As a result it ends with an error.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.


## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.


## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
