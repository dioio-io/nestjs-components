<p align="center">
  <a href="http://nestjs.com"><img src="https://nestjs.com/img/logo_text.svg" alt="Nest Logo" width="320" /></a>
</p>


# Algoan NestJS components

A collection of [NestJS](https://docs.nestjs.com) components.

## NestJS Pagination

A simple interceptor formatting a HTTP response with a `Link` header and a `Content-Range`.

See [the documentation here](./packages/nestjs-pagination/README.md).

## NestJS Logging interceptor

A simple NestJS interceptor catching request details and logging it using the built-in [Logger](https://docs.nestjs.com/techniques/logger#logger) class. It will use the default Logger implementation unless you pass your own to your Nest application.

See [the documentation here](./packages/nestjs-logging-interceptor/README.md).