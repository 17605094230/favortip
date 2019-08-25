# 前端编写js说明
> A TypeScript Framework on top of Express !

## What is it

Ts.ED is a framework on top of Express to write your application with TypeScript (or in ES6). It provides a lot of decorators 
to write your code.

## Features

* Define class as Controller,
* Define class as Service (IoC),
* Define class as Middleware and MiddlewareError,
* Define class as Converter (POJ to Model and Model to POJ),
* Define root path for an entire controller and versioning your Rest API,
* Define as sub-route path for a method,
* Define routes on GET, POST, PUT, DELETE and HEAD verbs,
* Define middlewares on routes,
* Define required parameters,
* Inject data from query string, path parameters, entire body, cookies, session or header,
* Inject Request, Response, Next object from Express request,
* Template (View),
* Swagger documentation and Swagger-ui,
* Testing.

## Documentation

Documentation is available on [https://tsed.io](https://tsed.io)

## Examples

Examples are available on [https://tsed.io/#/tutorials/overview](https://tsed.io/#/tutorials/overview)

## Installation

You can get the latest release using npm:

```batch
$ npm install --save @tsed/core @tsed/common express@4 @types/express
```







