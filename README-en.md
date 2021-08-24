English | [简体中文](./README.md)

## Table of contents

- [Table of contents](#table-of-contents)
- [Official](#official)
- [Repository](#repository)
- [Middleware](#middleware)
  - [JSON](#json)
  - [JSONP](#jsonp)
  - [Templating](#templating)
  - [File Serving](#file-serving)
  - [Session](#session)
  - [Logging](#logging)
  - [Error reporting](#error-reporting)

## Official

- [Website](https://koajs.com/)
- [Repository](https://github.com/koajs/koa)

## Repository

## Middleware

### JSON

- [koa-json](https://github.com/koajs/json) - Pretty-printed JSON response middleware.
- [koa-json-filter](https://github.com/koajs/json-filter) - Middleware allowing the client to filter the response to only what they need, reducing the amount of traffic over the wire.
- [koa-json-mask](https://github.com/nemtsov/koa-json-mask) - Middleware allowing the client to filter the response to only what they need, reducing the amount of traffic over the wire.
- [koa-is-json](https://github.com/koajs/is-json) - check if a koa body should be interpreted as JSON

### JSONP

- [koa-jsonp](https://github.com/kilianc/koa-jsonp) - Koajs JSONP streaming friendly middleware with GET/POST support.
- [koa-safe-jsonp](https://github.com/koajs/koa-safe-jsonp) - Safe jsonp plugins for koa.
- [koa-response-jsonp](https://github.com/keenwon/koa-response-jsonp) - koa jsonp middleware.

### Templating

- [koa-ejs](https://github.com/koajs/ejs) - A koa view render middleware, support all feature of ejs.
- [koa-react-view](https://github.com/koajs/react-view) - A Koa view engine which renders React components on server.

### File Serving

- [koa-static](https://github.com/koajs/static) - Static file server middleware.
- [koa-send](https://github.com/koajs/send) - Transfer static files.

### Session

- [koa-session](https://github.com/koajs/session) - Simple cookie-based session middleware
- [koa-generic-session](https://github.com/koajs/generic-session) - koa session store with memory, redis or others.
- [koa-redis](https://github.com/koajs/koa-redis) - koa session with redis
- [koa-redis-session-sets](https://github.com/koajs/redis-session-sets) - Koa Redis sessions with field-referencing cross sets

### Logging

- [koa-logger](https://github.com/koajs/logger) - Development style logging middleware.
- [koa-bunyan-logger](https://github.com/koajs/bunyan-logger) - Koa middleware for bunyan request logging.
- [koa-accesslog](https://github.com/koajs/accesslog) - Middleware for common log format access logs.

### Error reporting

- [koa-error](https://github.com/koajs/error) - Error response middleware (text, json, html).
- [koa-onerror](https://github.com/koajs/onerror) - an error handler for koa, hack ctx.onerror
- [koa-json-error](https://github.com/koajs/json-error) - Error handler for pure-JSON apps.
- [koa-errorhandler](https://github.com/nswbmw/koa-errorhandler) - Error handler middleware for koa.
- [koa-error-slack](https://github.com/rturk/koa-error-slack) - Send Koa errors to Slack.
