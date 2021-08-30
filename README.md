[English](./README-en.md) | 简体中文

## 目录

- [目录](#目录)
- [官方文档](#官方文档)
- [框架](#框架)
- [中间件](#中间件)
  - [JSON](#json)
  - [JSONP](#jsonp)
  - [CSS预处理器](#css预处理器)
  - [主体解析(Body解析)](#主体解析body解析)
  - [工具](#工具)
  - [模板引擎](#模板引擎)
  - [文件服务](#文件服务)
  - [压缩](#压缩)
  - [Session](#session)
  - [文档](#文档)
  - [安全](#安全)
  - [日志](#日志)
  - [错误报告](#错误报告)
  - [i18n](#i18n)

## 官方文档

- [官网](https://koajs.com/)
- [仓库](https://github.com/koajs/koa)
- [Wiki](https://github.com/koajs/koa/wiki)

## 框架

- [Egg](https://github.com/eggjs/egg) - 为企业级框架和应用而生。 ![](https://img.shields.io/github/stars/eggjs/egg.svg?style=social&label=Star)  ![](https://img.shields.io/npm/dm/egg.svg?style=flat-square)
- [ThinkJS](https://github.com/thinkjs/thinkjs) - 支持ES2015 +的框架, 支持TypeScript。 ![](https://img.shields.io/github/stars/thinkjs/thinkjs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/thinkjs.svg?style=flat-square)
- [lad](https://github.com/ladjs/lad) - 最好的Node.js框架，由前Express和Koa团队成员创建。 ![](https://img.shields.io/github/stars/ladjs/lad.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/lad.svg?style=flat-square)
- [CabloyJS](https://github.com/zhennann/Cabloy) - 一款自带工作流引擎的Node.js全栈框架, 基于koa + egg + vue + framework7. ![](https://img.shields.io/github/stars/zhennann/Cabloy.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/cabloy.svg?style=flat-square)
- [koatty](https://github.com/Koatty/koatty) - Koa2 + Typescript = Koatty。使用Typescript装饰器实现了控制反转和面向切面编程。 ![](https://img.shields.io/github/stars/Koatty/koatty.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koatty.svg?style=flat-square)

## 中间件

### JSON

- [koa-json](https://github.com/koajs/json) - 将 JSON 打印美化的中间件。 ![](https://img.shields.io/github/stars/koajs/json.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-json.svg?style=flat-square)
- [koa-json-filter](https://github.com/koajs/json-filter) - 该中间件允许客户端只过滤他们需要的响应，减少线路上的流量。 ![](https://img.shields.io/github/stars/koajs/json-filter.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-json-filter.svg?style=flat-square)
- [koa-json-mask](https://github.com/nemtsov/koa-json-mask) - 该中间件允许客户端只过滤他们需要的响应，减少线路上的流量。 ![](https://img.shields.io/github/stars/nemtsov/koa-json-mask.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-json-mask.svg?style=flat-square)
- [koa-is-json](https://github.com/koajs/is-json) - 检查 koa 主体是否应该被解析为 JSON。 ![](https://img.shields.io/github/stars/koajs/is-json.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-is-json.svg?style=flat-square)

### JSONP

- [koa-jsonp](https://github.com/kilianc/koa-jsonp) - 支持GET/POST JSONP流的中间件。 ![](https://img.shields.io/github/stars/kilianc/koa-jsonp.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-jsonp.svg?style=flat-square)
- [koa-safe-jsonp](https://github.com/koajs/koa-safe-jsonp) - 安全的Koa JSONP插件。 ![](https://img.shields.io/github/stars/koajs/koa-safe-jsonp.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-safe-jsonp.svg?style=flat-square)
- [koa-response-jsonp](https://github.com/keenwon/koa-response-jsonp) - KOA JSONP中间件。 ![](https://img.shields.io/github/stars/keenwon/koa-response-jsonp.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-response-jsonp.svg?style=flat-square)

### CSS预处理器

- [koa-stylus](https://github.com/yosssi/koa-stylus) - Stylus中间件。 ![](https://img.shields.io/github/stars/yosssi/koa-stylus.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-stylus.svg?style=flat-square)
- [koa-scss](https://github.com/adamkdean/koa-scss) - SCSS中间件。 ![](https://img.shields.io/github/stars/adamkdean/koa-scss.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-scss.svg?style=flat-square)
- [koa-less](https://github.com/chosecz/koa-less) - LESS中间件。 ![](https://img.shields.io/github/stars/chosecz/koa-less.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-less.svg?style=flat-square)
- [koa.sass](https://github.com/clthck/koa-sass) - Sass中间件。 ![](https://img.shields.io/github/stars/clthck/koa-sass.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa.sass.svg?style=flat-square)
- [koa-postcss](https://github.com/HowlingEverett/koa-postcss) - PostCSS中间件。 ![](https://img.shields.io/github/stars/HowlingEverett/koa-postcss.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-postcss.svg?style=flat-square)
### 主体解析(Body解析)

- [koa-bodyparser](https://github.com/koajs/body-parser) - 用于Koa，基于co-body的主体解析。 ![](https://img.shields.io/github/stars/koajs/body-parser.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-bodyparser.svg?style=flat-square)
- [koa-body](https://github.com/dlau/koa-body) - 功能齐全的 koa 主体解析器中间件。支持 multipart、urlencoded 和 json 请求正文。 提供与 Express 的 bodyParser 相同的功能 - multer。 ![](https://img.shields.io/github/stars/dlau/koa-body.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-body.svg?style=flat-square)
- [koa-better-body](https://github.com/tunnckoCore/opensource/tree/master/@packages/koa-better-body) - 功能齐全的 koa 体解析器！支持解析文本、缓冲区、json、json patch、json api、csp-report、multipart、form和urlencoded body。 适用于 koa@1、koa@2 并将适用于 koa@3。 ![](https://img.shields.io/github/stars/tunnckoCore/opensource.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-better-body.svg?style=flat-square)
- [koa-multer](https://github.com/koa-modules/multer) - Multer 是一个 Node.js 中间件，用于处理 koa 的 multipart/form-data。 koa 中间件的 multer 封装。 ![](https://img.shields.io/github/stars/koa-modules/multer.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-multer.svg?style=flat-square)
- [koa-xml-body](https://github.com/creeperyang/koa-xml-body) - 解析 xml http 请求正文。 ![](https://img.shields.io/github/stars/creeperyang/koa-xml-body.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-xml-body.svg?style=flat-square)
- [koa-busboy](https://github.com/dominhhai/koa-busboy) - 处理 koa v2 的 multipart/form-data 数据。 ![](https://img.shields.io/github/stars/dominhhai/koa-busboy.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-busboy.svg?style=flat-square)
- [koa-json-body](https://github.com/venables/koa-json-body) - 解析合法的 JSON 请求正文。 ![](https://img.shields.io/github/stars/venables/koa-json-body.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-json-body.svg?style=flat-square)

### 工具

- [koa-convert](https://github.com/gyson/koa-convert) - 将koa legacy (v0.x & v1.x版本) 生成器中间件转化为promise中间件(v2.x)。 ![](https://img.shields.io/github/stars/gyson/koa-convert.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-convert.svg?style=flat-square)

### 模板引擎

- [koa-views](https://github.com/queckezz/koa-views) - Render your views with almost any templating engine ![](https://img.shields.io/github/stars/queckezz/koa-views.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-views.svg?style=flat-square)
- [koa-ejs](https://github.com/koajs/ejs) -  Koa视图渲染中间件，支持ejs所有特性。 ![](https://img.shields.io/github/stars/koajs/ejs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-ejs.svg?style=flat-square)
- [koa-react-view](https://github.com/koajs/react-view) - Koa视图渲染中间件，用于在服务端渲染React组件。 ![](https://img.shields.io/github/stars/koajs/react-view.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-react-view.svg?style=flat-square)
- [koa-hbs](https://github.com/jwilm/koa-hbs) - Express风格视图渲染。 ![](https://img.shields.io/github/stars/jwilm/koa-hbs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-hbs.svg?style=flat-square)
- [koa-pug](https://github.com/chrisyip/koa-pug) - [Pug](https://pugjs.org/api/getting-started.html) (原名Jade) 中间件。 ![](https://img.shields.io/github/stars/chrisyip/koa-pug.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-pug.svg?style=flat-square)
- [koa-handlebars](https://github.com/dominicbarnes/koa-handlebars) - [Handlebars](http://handlebarsjs.com/)视图渲染中间件。 ![](https://img.shields.io/github/stars/dominicbarnes/koa-handlebars.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-handlebars.svg?style=flat-square)
- [koa-swig](https://github.com/koa-modules/swig) - [swig](http://paularmstrong.github.io/swig/)视图渲染中间件, 支持标签，过滤器和插件。 ![](https://img.shields.io/github/stars/koa-modules/swig.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-swig.svg?style=flat-square)
- [koa-vue-view](https://github.com/imingyu/koa-vue-view) - Koa视图渲染中间件，用于在服务端渲染Vue组件。![](https://img.shields.io/github/stars/imingyu/koa-vue-view.svg?style=social&label=Star) [![image](https://img.shields.io/npm/dt/koa-vue-view.svg)](https://www.npmjs.com/package/koa-vue-view)
- [koa-view](https://github.com/d-band/koa-view) - [Nunjucks](http://mozilla.github.io/nunjucks/)视图渲染中间件。 ![](https://img.shields.io/github/stars/d-band/koa-view.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-view.svg?style=flat-square)
- [koa-nunjucks-next](https://github.com/beliefgp/koa-nunjucks-next) - [Nunjucks](http://mozilla.github.io/nunjucks/)视图渲染中间件, 支持异步过滤器，渲染原始字符串。 ![](https://img.shields.io/github/stars/beliefgp/koa-nunjucks-next.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-nunjucks-next.svg?style=flat-square)
- [koa-dom](https://github.com/juliangruber/koa-dom) - 服务端渲染DOM模板。![](https://img.shields.io/github/stars/juliangruber/koa-dom.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-dom.svg?style=flat-square)
- [co-ejs](https://github.com/nswbmw/co-ejs) - koa ejs视图渲染中间件。 ![](https://img.shields.io/github/stars/nswbmw/co-ejs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/co-ejs.svg?style=flat-square)
- [koa-xtpl](https://github.com/zce/koa-xtpl) - xtemplate模板引擎的封装(使其在Koa 2使用更简单). ![](https://img.shields.io/github/stars/zce/koa-xtpl.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-xtpl.svg?style=flat-square)
- [koa-nunjucks-async](https://github.com/uniibu/koa-nunjucks-async) - 一个Koa@2 [Nunjucks](http://mozilla.github.io/nunjucks/)视图渲染中间件。使用 Node 的原生 `async/await` 和 `util.promisify`。 还将 ctx.state 暴露给渲染模板。 ![](https://img.shields.io/github/stars/uniibu/koa-nunjucks-async.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-nunjucks-async.svg?style=flat-square)
- [koajs-nunjucks](https://github.com/Faeson/koajs-nunjucks) - [Nunjucks](http://mozilla.github.io/nunjucks/)视图渲染中间件。 ![](https://img.shields.io/github/stars/Faeson/koajs-nunjucks.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koajs-nunjucks.svg?style=flat-square)
- [koa-swig-render](https://github.com/JiangJie/koa-swig-render) - [swig](http://paularmstrong.github.io/swig/)视图渲染中间件. ![](https://img.shields.io/github/stars/JiangJie/koa-swig-render.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-swig-render.svg?style=flat-square)
- [koa2-jsx](https://github.com/artdecocode/koa2-jsx) - [JSX](https://reactjs.org/docs/introducing-jsx.html) 使用服务器端 React 方法渲染，Redux 支持从上下文设置模板数据。可用于创建通用应用程序。 ![](https://img.shields.io/github/stars/artdecocode/koa2-jsx.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa2-jsx.svg?style=flat-square)
- [koahub-handlebars](https://github.com/koahubjs/koahub-handlebars) - Handlebars视图渲染中间件, 使用async/await ![](https://img.shields.io/github/stars/koahubjs/koahub-handlebars.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koahub-handlebars.svg?style=flat-square)

### 文件服务

- [koa-static](https://github.com/koajs/static) - 静态文件服务中间件。 ![](https://img.shields.io/github/stars/koajs/static.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-static.svg?style=flat-square)
- [koa-send](https://github.com/koajs/send) - 传送静态文件。 ![](https://img.shields.io/github/stars/koajs/send.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-send.svg?style=flat-square)

### 压缩

- [koa-compress](https://github.com/koajs/compress) - 用于压缩的中间件。 ![](https://img.shields.io/github/stars/koajs/compress.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-compress.svg?style=flat-square)
- [koa-compressor](https://github.com/koajs/compressor) - SPDY/HTTP2压缩中间件 (总是gzips) ![](https://img.shields.io/github/stars/koajs/compressor.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-compressor.svg?style=flat-square)
- [kompression](https://github.com/tuananh/kompression) - koa-compress的fork版本，用于支持brotli压缩 ![](https://img.shields.io/github/stars/tuananh/kompression.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/kompression.svg?style=flat-square)
- [koa-minify](https://github.com/coderaiser/koa-minify) - 将 js、css、html 和 img最小化的中间件。![](https://img.shields.io/github/stars/coderaiser/koa-minify.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-minify.svg?style=flat-square)
- [koa-uglify2](https://github.com/grayleonard/koa-uglify2) - 带有缓存的 js 的uglify中间件。 ![](https://img.shields.io/github/stars/grayleonard/koa-uglify2.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-uglify2.svg?style=flat-square)

### Session

- [koa-session](https://github.com/koajs/session) - 简单基于Cookie的Session中间件。 ![](https://img.shields.io/github/stars/koajs/session.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-session.svg?style=flat-square)
- [koa-generic-session](https://github.com/koajs/generic-session) - 基于内存、redis或其他的Session存储中间件。 ![](https://img.shields.io/github/stars/koajs/generic-session.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-generic-session.svg?style=flat-square)
- [koa-redis](https://github.com/koajs/koa-redis) - 使用Redis的Koa Session。 ![](https://img.shields.io/github/stars/koajs/koa-redis.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-redis.svg?style=flat-square)
- [koa-redis-session-sets](https://github.com/koajs/redis-session-sets) - 带有字段引用交叉集的 Koa Redis Session。 ![](https://img.shields.io/github/stars/koajs/redis-session-sets.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-redis-session-sets.svg?style=flat-square)

### 文档

- [koa-docs](https://github.com/a-s-o/koa-docs) - 用于自动生成和提供API文档的Koa中间件。 ![](https://img.shields.io/github/stars/a-s-o/koa-docs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-docs.svg?style=flat-square)
- [koa-joi-swagger](https://github.com/zaaack/koa-joi-swagger) - 使用 joi 模式验证请求和响应，并生成 swagger 文档以创建漂亮的 API 文档。 ![](https://img.shields.io/github/stars/zaaack/koa-joi-swagger.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-joi-swagger.svg?style=flat-square)

### 安全

- [koa-helmet](https://github.com/venables/koa-helmet) - 提供重要的安全头header，使您的应用默认更安全。 ![](https://img.shields.io/github/stars/venables/koa-helmet.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-helmet.svg?style=flat-square)
- [koa-rbac](https://github.com/yanickrochon/koa-rbac) - 用于Koa的基于角色的权限访问控制。 ![](https://img.shields.io/github/stars/yanickrochon/koa-rbac.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-rbac.svg?style=flat-square)
- [koa-ip](https://github.com/MangroveTech/koa-ip) - 用于Koa的Ip过滤中间件。支持白名单和黑名单。 ![](https://img.shields.io/github/stars/MangroveTech/koa-ip.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-ip.svg?style=flat-square)
- [koa-authz](https://github.com/node-casbin/koa-authz) - 用于Koa2，基于Casbin的授权中间件。 ![](https://img.shields.io/github/stars/node-casbin/koa-authz.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-authz.svg?style=flat-square)
- [koa-ip-filter](https://github.com/tunnckoCore/koa-ip-filter) - koa 的中间件，它使用 `ip-filter` 和 `micromatch` 根据 glob 模式、RegExp、字符串或 glob 数组过滤 IP。 支持自定义 403 Forbidden 消息和自定义 ID。![](https://img.shields.io/github/stars/tunnckoCore/koa-ip-filter.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-ip-filter.svg?style=flat-square)
- [koa-protect](https://github.com/may215/koa-protect) - 用于koa应用的安全模块。 ![](https://img.shields.io/github/stars/may215/koa-protect.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-protect.svg?style=flat-square)
- [koa-acl](https://github.com/Jackong/koa-acl) - 用于Koa的访问控制列表(ACL)中间件。 ![](https://img.shields.io/github/stars/Jackong/koa-acl.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-acl.svg?style=flat-square)

### 日志

- [koa-logger](https://github.com/koajs/logger) - 开发风格日志中间件。 ![](https://img.shields.io/github/stars/koajs/logger.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-logger.svg?style=flat-square)
- [koa-bunyan-logger](https://github.com/koajs/bunyan-logger) - 使用Bunyan请求日志的Koa中间件。 ![](https://img.shields.io/github/stars/koajs/bunyan-logger.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-bunyan-logger.svg?style=flat-square)
- [koa-accesslog](https://github.com/koajs/accesslog) - 通用日志格式访问日志的中间件。 ![](https://img.shields.io/github/stars/koajs/accesslog.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-accesslog.svg?style=flat-square)

### 错误报告

- [koa-onerror](https://github.com/koajs/onerror) - Koa 的错误处理程序，hack ctx.onerror。 ![](https://img.shields.io/github/stars/koajs/onerror.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-onerror.svg?style=flat-square)
- [koa-error](https://github.com/koajs/error) - 错误响应中间件(支持返回text, json, html模板引擎). ![](https://img.shields.io/github/stars/koajs/error.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-error.svg?style=flat-square)
- [koa-json-error](https://github.com/koajs/json-error) - 纯 JSON 应用程序的错误处理程序。 ![](https://img.shields.io/github/stars/koajs/json-error.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-json-error.svg?style=flat-square)
- [koa-errorhandler](https://github.com/nswbmw/koa-errorhandler) - Koa 的错误处理程序中间件。 ![](https://img.shields.io/github/stars/nswbmw/koa-errorhandler.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-errorhandler.svg?style=flat-square)
- [koa-error-slack](https://github.com/rturk/koa-error-slack) - 发送 Koa 错误到 Slack。 ![](https://img.shields.io/github/stars/rturk/koa-error-slack.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-error-slack.svg?style=flat-square)

### i18n

- [koa-i18n](https://github.com/koa-modules/i18n) - 基于 i18n-2 的轻量级简单翻译中间件。 ![](https://img.shields.io/github/stars/koa-modules/i18n.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-i18n.svg?style=flat-square)
- [koa-locale](https://github.com/koa-modules/locale) - 从查询参数、子域名、accept-languages或 cookie 中获取区域设置变量。 ![](https://img.shields.io/github/stars/koa-modules/locale.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-locale.svg?style=flat-square)
