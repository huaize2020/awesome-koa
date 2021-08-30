English | [简体中文](./README.md)

## Table of contents

- [Table of contents](#table-of-contents)
- [Official](#official)
- [Framework](#framework)
- [Middleware](#middleware)
  - [JSON](#json)
  - [JSONP](#jsonp)
  - [Body Parsing](#body-parsing)
  - [Utilities](#utilities)
  - [Templating](#templating)
  - [File Serving](#file-serving)
  - [Compression](#compression)
  - [Session](#session)
  - [Documentation](#documentation)
  - [Security](#security)
  - [Logging](#logging)
  - [Error reporting](#error-reporting)
  - [i18n](#i18n)

## Official

- [Website](https://koajs.com/)
- [Repository](https://github.com/koajs/koa)
- [Wiki](https://github.com/koajs/koa/wiki)

## Framework

- [Egg](https://github.com/eggjs/egg) - Born to build better enterprise frameworks and apps with Node.js & Koa. ![](https://img.shields.io/github/stars/eggjs/egg.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/egg.svg?style=flat-square)
- [ThinkJS](https://github.com/thinkjs/thinkjs) - Use full ES2015+ features to develop Node.js applications, Support TypeScript. ![](https://img.shields.io/github/stars/thinkjs/thinkjs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/thinkjs.svg?style=flat-square)
- [lad](https://github.com/ladjs/lad) - The best Node.js framework. Made by a former Express TC and Koa team member. ![](https://img.shields.io/github/stars/ladjs/lad.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/lad.svg?style=flat-square)
- [CabloyJS](https://github.com/zhennann/Cabloy) - A Node.js full-stack framework with workflow engine, based on koa + egg + vue + framework7. ![](https://img.shields.io/github/stars/zhennann/Cabloy.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/cabloy.svg?style=flat-square)
- [koatty](https://github.com/Koatty/koatty) - Koa2 + Typescript = Koatty. Use Typescript's decorator implement IOC and AOP. ![](https://img.shields.io/github/stars/Koatty/koatty.svg?style=social&label=Star)  ![](https://img.shields.io/npm/dm/koatty.svg?style=flat-square)

## Middleware

### JSON

- [koa-json](https://github.com/koajs/json) - Pretty-printed JSON response middleware. ![](https://img.shields.io/github/stars/koajs/json.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-json.svg?style=flat-square)
- [koa-json-filter](https://github.com/koajs/json-filter) - Middleware allowing the client to filter the response to only what they need, reducing the amount of traffic over the wire. ![](https://img.shields.io/github/stars/koajs/json-filter.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-json-filter.svg?style=flat-square)
- [koa-json-mask](https://github.com/nemtsov/koa-json-mask) - Middleware allowing the client to filter the response to only what they need, reducing the amount of traffic over the wire. ![](https://img.shields.io/github/stars/nemtsov/koa-json-mask.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-json-mask.svg?style=flat-square)
- [koa-is-json](https://github.com/koajs/is-json) - check if a koa body should be interpreted as JSON ![](https://img.shields.io/github/stars/koajs/is-json.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-is-json.svg?style=flat-square)

### JSONP

- [koa-jsonp](https://github.com/kilianc/koa-jsonp) - Koajs JSONP streaming friendly middleware with GET/POST support. ![](https://img.shields.io/github/stars/kilianc/koa-jsonp.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-jsonp.svg?style=flat-square)
- [koa-safe-jsonp](https://github.com/koajs/koa-safe-jsonp) - Safe jsonp plugins for koa. ![](https://img.shields.io/github/stars/koajs/koa-safe-jsonp.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-safe-jsonp.svg?style=flat-square)
- [koa-response-jsonp](https://github.com/keenwon/koa-response-jsonp) - koa jsonp middleware. ![](https://img.shields.io/github/stars/keenwon/koa-response-jsonp.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-response-jsonp.svg?style=flat-square)

### Body Parsing

- [koa-bodyparser](https://github.com/koajs/body-parser) - A body parser for koa, base on co-body. ![](https://img.shields.io/github/stars/koajs/body-parser.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-bodyparser.svg?style=flat-square)
- [koa-body](https://github.com/dlau/koa-body) - A full-featured koa body parser middleware. Supports multipart, urlencoded, and json request bodies. Provides the same functionality as Express's bodyParser - multer. ![](https://img.shields.io/github/stars/dlau/koa-body.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-body.svg?style=flat-square)
- [koa-better-body](https://github.com/tunnckoCore/opensource/tree/master/@packages/koa-better-body) - Full-featured koa body parser! Support parsing text, buffer, json, json patch, json api, csp-report, multipart, form and urlencoded bodies. Works for koa@1, koa@2 and will work for koa@3. ![](https://img.shields.io/github/stars/tunnckoCore/opensource.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-better-body.svg?style=flat-square)
- [koa-multer](https://github.com/koa-modules/multer) - Multer is a node.js middleware for handling multipart/form-data for koa. multer wrapper for koa's middleware. ![](https://img.shields.io/github/stars/koa-modules/multer.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-multer.svg?style=flat-square)
- [koa-xml-body](https://github.com/creeperyang/koa-xml-body) - Parse xml http request bodies ![](https://img.shields.io/github/stars/creeperyang/koa-xml-body.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-xml-body.svg?style=flat-square)
- [koa-busboy](https://github.com/dominhhai/koa-busboy) - Handling multipart/form-data for koa v2. ![](https://img.shields.io/github/stars/dominhhai/koa-busboy.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-busboy.svg?style=flat-square)
- [koa-json-body](https://github.com/venables/koa-json-body) - Parse valid JSON request bodies. ![](https://img.shields.io/github/stars/venables/koa-json-body.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-json-body.svg?style=flat-square)

### Utilities

- [koa-convert](https://github.com/gyson/koa-convert) - convert koa legacy ( v0.x & v1.x ) generator middleware to promise middleware ( v2.x ). ![](https://img.shields.io/github/stars/gyson/koa-convert.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-convert.svg?style=flat-square)

### Templating

- [koa-views](https://github.com/queckezz/koa-views) - Render your views with almost any templating engine ![](https://img.shields.io/github/stars/queckezz/koa-views.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-views.svg?style=flat-square)
- [koa-ejs](https://github.com/koajs/ejs) - A koa view render middleware, support all feature of ejs. ![](https://img.shields.io/github/stars/koajs/ejs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-ejs.svg?style=flat-square)
- [koa-react-view](https://github.com/koajs/react-view) - A Koa view engine which renders React components on server. ![](https://img.shields.io/github/stars/koajs/react-view.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-react-view.svg?style=flat-square)
- [koa-hbs](https://github.com/jwilm/koa-hbs) - Express-style Handlebars view rendering. ![](https://img.shields.io/github/stars/jwilm/koa-hbs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-hbs.svg?style=flat-square)
- [koa-pug](https://github.com/chrisyip/koa-pug) - a [Pug](https://pugjs.org/api/getting-started.html) (renamed Jade) middleware for Koa. ![](https://img.shields.io/github/stars/chrisyip/koa-pug.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-pug.svg?style=flat-square)
- [koa-handlebars](https://github.com/dominicbarnes/koa-handlebars) - [Handlebars](http://handlebarsjs.com/) view rendering. ![](https://img.shields.io/github/stars/dominicbarnes/koa-handlebars.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-handlebars.svg?style=flat-square)
- [koa-swig](https://github.com/koa-modules/swig) - Focus on [swig](http://paularmstrong.github.io/swig/), support tags, filters, and extensions. ![](https://img.shields.io/github/stars/koa-modules/swig.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-swig.svg?style=flat-square)
- [koa-vue-view](https://github.com/imingyu/koa-vue-view) - A Koa view engine which renders Vue components on server. ![](https://img.shields.io/github/stars/imingyu/koa-vue-view.svg?style=social&label=Star) [![image](https://img.shields.io/npm/dt/koa-vue-view.svg)](https://www.npmjs.com/package/koa-vue-view)
- [koa-view](https://github.com/d-band/koa-view) - [Nunjucks](http://mozilla.github.io/nunjucks/) view rendering. ![](https://img.shields.io/github/stars/d-band/koa-view.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-view.svg?style=flat-square)
- [koa-nunjucks-next](https://github.com/beliefgp/koa-nunjucks-next) - [Nunjucks](http://mozilla.github.io/nunjucks/) view rendering, support asynchronous filters, render raw string. ![](https://img.shields.io/github/stars/beliefgp/koa-nunjucks-next.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-nunjucks-next.svg?style=flat-square)
- [koa-dom](https://github.com/juliangruber/koa-dom) - server-side dom templating ![](https://img.shields.io/github/stars/juliangruber/koa-dom.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-dom.svg?style=flat-square)
- [co-ejs](https://github.com/nswbmw/co-ejs) - koa ejs view render middleware. ![](https://img.shields.io/github/stars/nswbmw/co-ejs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/co-ejs.svg?style=flat-square)
- [koa-xtpl](https://github.com/zce/koa-xtpl) - A node.js wrapper around xtemplate engine (easier for Koa 2). ![](https://img.shields.io/github/stars/zce/koa-xtpl.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-xtpl.svg?style=flat-square)
- [koa-nunjucks-async](https://github.com/uniibu/koa-nunjucks-async) - A Koa@2 middleware for rendering [Nunjucks](http://mozilla.github.io/nunjucks/) templates. Uses Node's native `async/await`, and `util.promisify`. Also exposes ctx.state to rendered templates. ![](https://img.shields.io/github/stars/uniibu/koa-nunjucks-async.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-nunjucks-async.svg?style=flat-square)
- [koajs-nunjucks](https://github.com/Faeson/koajs-nunjucks) - [Nunjucks](http://mozilla.github.io/nunjucks/) view rendering. ![](https://img.shields.io/github/stars/Faeson/koajs-nunjucks.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koajs-nunjucks.svg?style=flat-square)
- [koa-swig-render](https://github.com/JiangJie/koa-swig-render) - Focus on - [swig](http://paularmstrong.github.io/swig/), used as a middleware. ![](https://img.shields.io/github/stars/JiangJie/koa-swig-render.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-swig-render.svg?style=flat-square)
- [koa2-jsx](https://github.com/artdecocode/koa2-jsx) - [JSX](https://reactjs.org/docs/introducing-jsx.html) rendering using server-side React methods, with Redux support to set templating data from context. Can be used to create universal application. ![](https://img.shields.io/github/stars/artdecocode/koa2-jsx.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa2-jsx.svg?style=flat-square)
- [koahub-handlebars](https://github.com/koahubjs/koahub-handlebars) - Handlebars view rendering, Use async/await ![](https://img.shields.io/github/stars/koahubjs/koahub-handlebars.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koahub-handlebars.svg?style=flat-square)

### File Serving

- [koa-static](https://github.com/koajs/static) - Static file server middleware. ![](https://img.shields.io/github/stars/koajs/static.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-static.svg?style=flat-square)
- [koa-send](https://github.com/koajs/send) - Transfer static files. ![](https://img.shields.io/github/stars/koajs/send.svg?style=social&label=Star)

### Compression

- [koa-compress](https://github.com/koajs/compress) - Compression middleware  ![](https://img.shields.io/github/stars/koajs/compress.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-compress.svg?style=flat-square)
- [koa-compressor](https://github.com/koajs/compressor) - SPDY/HTTP2 compression middleware (always gzips) ![](https://img.shields.io/github/stars/koajs/compressor.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-compressor.svg?style=flat-square)
- [kompression](https://github.com/tuananh/kompression) - forked of koa-compress with support for brotli compression ![](https://img.shields.io/github/stars/tuananh/kompression.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/kompression.svg?style=flat-square)
- [koa-minify](https://github.com/coderaiser/koa-minify) - minify middleware for js, css, html and img. ![](https://img.shields.io/github/stars/coderaiser/koa-minify.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-minify.svg?style=flat-square)
- [koa-uglify2](https://github.com/grayleonard/koa-uglify2) - uglify middleware for js with caching. ![](https://img.shields.io/github/stars/grayleonard/koa-uglify2.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-uglify2.svg?style=flat-square)

### Session

- [koa-session](https://github.com/koajs/session) - Simple cookie-based session middleware ![](https://img.shields.io/github/stars/koajs/session.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-session.svg?style=flat-square)
- [koa-generic-session](https://github.com/koajs/generic-session) - koa session store with memory, redis or others. ![](https://img.shields.io/github/stars/koajs/generic-session.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-generic-session.svg?style=flat-square)
- [koa-redis](https://github.com/koajs/koa-redis) - koa session with redis ![](https://img.shields.io/github/stars/koajs/koa-redis.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-redis.svg?style=flat-square)
- [koa-redis-session-sets](https://github.com/koajs/redis-session-sets) - Koa Redis sessions with field-referencing cross sets ![](https://img.shields.io/github/stars/koajs/redis-session-sets.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-redis-session-sets.svg?style=flat-square)

### Documentation

- [koa-docs](https://github.com/a-s-o/koa-docs) - Koa middleware for automatically generating and serving API documentation ![](https://img.shields.io/github/stars/a-s-o/koa-docs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-docs.svg?style=flat-square)
- [koa-joi-swagger](https://github.com/zaaack/koa-joi-swagger) - Using joi schema to validate request & response, and generate swagger document to create beautiful API documents. ![](https://img.shields.io/github/stars/zaaack/koa-joi-swagger.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-joi-swagger.svg?style=flat-square)

### Security

- [koa-helmet](https://github.com/venables/koa-helmet) - Provides important security headers to make your app more secure by default.
 ![](https://img.shields.io/github/stars/venables/koa-helmet.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-helmet.svg?style=flat-square)
- [koa-rbac](https://github.com/yanickrochon/koa-rbac) - Role-Based Access Control for koa. ![](https://img.shields.io/github/stars/yanickrochon/koa-rbac.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-rbac.svg?style=flat-square)
- [koa-ip](https://github.com/MangroveTech/koa-ip) - Ip filter middleware for koa, support whitelist and blacklist.  ![](https://img.shields.io/github/stars/MangroveTech/koa-ip.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-ip.svg?style=flat-square)
- [koa-authz](https://github.com/node-casbin/koa-authz) - ACL, RBAC, ABAC authorization middleware based on [Casbin](https://github.com/casbin/node-casbin).  ![](https://img.shields.io/github/stars/node-casbin/koa-authz.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-authz.svg?style=flat-square)
- [koa-ip-filter](https://github.com/tunnckoCore/koa-ip-filter) - Middleware for koa that filters IPs against glob patterns, RegExp, string or array of globs using `ip-filter` and `micromatch`. Support custom 403 Forbidden message and custom ID.  ![](https://img.shields.io/github/stars/tunnckoCore/koa-ip-filter.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-ip-filter.svg?style=flat-square)
- [koa-protect](https://github.com/may215/koa-protect) - Security module for koa applications. ![](https://img.shields.io/github/stars/may215/koa-protect.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-protect.svg?style=flat-square)
- [koa-acl](https://github.com/Jackong/koa-acl) - ACL middleware for koa. ![](https://img.shields.io/github/stars/Jackong/koa-acl.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-acl.svg?style=flat-square)

### Logging

- [koa-logger](https://github.com/koajs/logger) - Development style logging middleware. ![](https://img.shields.io/github/stars/koajs/logger.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-logger.svg?style=flat-square)
- [koa-bunyan-logger](https://github.com/koajs/bunyan-logger) - Koa middleware for bunyan request logging. ![](https://img.shields.io/github/stars/koajs/bunyan-logger.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-bunyan-logger.svg?style=flat-square)
- [koa-accesslog](https://github.com/koajs/accesslog) - Middleware for common log format access logs. ![](https://img.shields.io/github/stars/koajs/accesslog.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-accesslog.svg?style=flat-square)

### Error reporting

- [koa-onerror](https://github.com/koajs/onerror) - an error handler for koa, hack ctx.onerror ![](https://img.shields.io/github/stars/koajs/onerror.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-onerror.svg?style=flat-square)
- [koa-error](https://github.com/koajs/error) - Error response middleware (text, json, html). ![](https://img.shields.io/github/stars/koajs/error.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-error.svg?style=flat-square)
- [koa-json-error](https://github.com/koajs/json-error) - Error handler for pure-JSON apps. ![](https://img.shields.io/github/stars/koajs/json-error.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-json-error.svg?style=flat-square)
- [koa-errorhandler](https://github.com/nswbmw/koa-errorhandler) - Error handler middleware for koa. ![](https://img.shields.io/github/stars/nswbmw/koa-errorhandler.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-errorhandler.svg?style=flat-square)
- [koa-error-slack](https://github.com/rturk/koa-error-slack) - Send Koa errors to Slack. ![](https://img.shields.io/github/stars/rturk/koa-error-slack.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-error-slack.svg?style=flat-square)

### i18n

- [koa-i18n](https://github.com/koa-modules/i18n) - Lightweight simple translation middleware based on i18n-2. ![](https://img.shields.io/github/stars/koa-modules/i18n.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-i18n.svg?style=flat-square)
- [koa-locale](https://github.com/koa-modules/locale) - Get locale variable from query, subdomain, accept-languages or cookie. ![](https://img.shields.io/github/stars/koa-modules/locale.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-locale.svg?style=flat-square)
