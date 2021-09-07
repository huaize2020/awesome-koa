[English](./README-en.md) | 简体中文

## 目录

- [目录](#目录)
- [官方文档](#官方文档)
- [框架](#框架)
- [内容管理系统 (CMS)](#内容管理系统-cms)
- [中间件](#中间件)
  - [JSON](#json)
  - [JSONP](#jsonp)
  - [CSS预处理器](#css预处理器)
  - [主体解析(Body解析)](#主体解析body解析)
  - [工具](#工具)
  - [模板引擎](#模板引擎)
  - [文件服务](#文件服务)
  - [路由和挂载](#路由和挂载)
  - [授权/鉴权](#授权鉴权)
  - [数据库](#数据库)
  - [Graphql](#graphql)
  - [压缩](#压缩)
  - [Session](#session)
  - [Cookies](#cookies)
  - [缓存](#缓存)
  - [限流](#限流)
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

- [Egg](https://github.com/eggjs/egg) - 为企业级框架和应用而生。 ![](https://img.shields.io/github/stars/eggjs/egg.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/egg.svg?style=flat-square)
- [ThinkJS](https://github.com/thinkjs/thinkjs) - 支持ES2015 +的框架, 支持TypeScript。 ![](https://img.shields.io/github/stars/thinkjs/thinkjs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/thinkjs.svg?style=flat-square)
- [midway](https://github.com/midwayjs/midway) - 面向前端/全栈开发人员的 Node.js Serverless框架。 Midway 可以使用 koa、express 或 EggJS 作为基本的 web 框架。 ![](https://img.shields.io/github/stars/midwayjs/midway.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/midway.svg?style=flat-square)
- [lad](https://github.com/ladjs/lad) - 最好的Node.js框架，由前Express和Koa团队成员创建。 ![](https://img.shields.io/github/stars/ladjs/lad.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/lad.svg?style=flat-square)
- [CabloyJS](https://github.com/zhennann/Cabloy) - 一款自带工作流引擎的Node.js全栈框架, 基于koa + egg + vue + framework7. ![](https://img.shields.io/github/stars/zhennann/Cabloy.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/cabloy.svg?style=flat-square)
- [koatty](https://github.com/Koatty/koatty) - Koa2 + Typescript = Koatty。使用Typescript装饰器实现了控制反转和面向切面编程。 ![](https://img.shields.io/github/stars/Koatty/koatty.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koatty.svg?style=flat-square)

## 内容管理系统 (CMS)

- [Strapi](https://github.com/strapi/strapi) - 用于构建强大 API 的内容管理框架 (headless-CMS)。 ![](https://img.shields.io/github/stars/strapi/strapi.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/strapi.svg?style=flat-square)


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

- [koa-compose](https://github.com/koajs/compose) - 组合多个中间件为一个。![](https://img.shields.io/github/stars/koajs/compose.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-compose.svg?style=flat-square)
- [koa-convert](https://github.com/gyson/koa-convert) - 将koa legacy (v0.x & v1.x版本) 生成器中间件转化为promise中间件(v2.x)。 ![](https://img.shields.io/github/stars/gyson/koa-convert.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-convert.svg?style=flat-square)
- [koa-connect](https://github.com/vkurchatkin/koa-connect) - 在Koa中使用connect和express中间件。 ![](https://img.shields.io/github/stars/vkurchatkin/koa-connect.svg?style=social&label=Star) ![](https://img.shields.io/npm/dt/koa-connect.svg)
- [koa-useragent](https://github.com/rvboris/koa-useragent) - 快速显露user-agent的中间件。 ![](https://img.shields.io/github/stars/rvboris/koa-useragent.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-useragent.svg?style=flat-square)

### 模板引擎

- [koa-views](https://github.com/queckezz/koa-views) - 可使用几乎任何模板引擎渲染你的视图。 ![](https://img.shields.io/github/stars/queckezz/koa-views.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-views.svg?style=flat-square)
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
- [koa-xtpl](https://github.com/zce/koa-xtpl) - xtemplate模板引擎的封装(使其在Koa 2使用更简单). ![](https://img.shields.io/github/stars/zce/koa-xtpl.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-xtpl.svg?style=flat-square)
- [koa-nunjucks-async](https://github.com/uniibu/koa-nunjucks-async) - 一个Koa@2 [Nunjucks](http://mozilla.github.io/nunjucks/)视图渲染中间件。使用 Node 的原生 `async/await` 和 `util.promisify`。 还将 ctx.state 暴露给渲染模板。 ![](https://img.shields.io/github/stars/uniibu/koa-nunjucks-async.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-nunjucks-async.svg?style=flat-square)
- [co-ejs](https://github.com/nswbmw/co-ejs) - koa ejs视图渲染中间件。 ![](https://img.shields.io/github/stars/nswbmw/co-ejs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/co-ejs.svg?style=flat-square)
- [koajs-nunjucks](https://github.com/Faeson/koajs-nunjucks) - [Nunjucks](http://mozilla.github.io/nunjucks/)视图渲染中间件。 ![](https://img.shields.io/github/stars/Faeson/koajs-nunjucks.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koajs-nunjucks.svg?style=flat-square)
- [koa-swig-render](https://github.com/JiangJie/koa-swig-render) - [swig](http://paularmstrong.github.io/swig/)视图渲染中间件. ![](https://img.shields.io/github/stars/JiangJie/koa-swig-render.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-swig-render.svg?style=flat-square)
- [koa2-jsx](https://github.com/artdecocode/koa2-jsx) - [JSX](https://reactjs.org/docs/introducing-jsx.html) 使用服务器端 React 方法渲染，Redux 支持从上下文设置模板数据。可用于创建通用应用程序。 ![](https://img.shields.io/github/stars/artdecocode/koa2-jsx.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa2-jsx.svg?style=flat-square)
- [koahub-handlebars](https://github.com/koahubjs/koahub-handlebars) - Handlebars视图渲染中间件, 使用async/await ![](https://img.shields.io/github/stars/koahubjs/koahub-handlebars.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koahub-handlebars.svg?style=flat-square)

### 文件服务

- [koa-static](https://github.com/koajs/static) - 静态文件服务中间件。 ![](https://img.shields.io/github/stars/koajs/static.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-static.svg?style=flat-square)
- [koa-send](https://github.com/koajs/send) - 传送静态文件。 ![](https://img.shields.io/github/stars/koajs/send.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-send.svg?style=flat-square)
- [koa-static-cache](https://github.com/jonathanong/koa-static-cache) - 带缓存的静态文件服务。 ![](https://img.shields.io/github/stars/jonathanong/koa-static-cache.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-static-cache.svg?style=flat-square)
- [koa-favicon](https://github.com/koajs/favicon) - 基于 `serve-favicon`提供网站图标服务favicon。 ![](https://img.shields.io/github/stars/koajs/favicon.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-favicon.svg?style=flat-square)
- [koa-static-server](https://github.com/pkoretic/koa-static-server) - 具有目录、重写和索引支持的 koa 静态文件服务中间件。 ![](https://img.shields.io/github/stars/pkoretic/koa-static-server.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-static-server.svg?style=flat-square)
- [koa-sendfile](https://github.com/koajs/sendfile) - 基础文件发送工具。 ![](https://img.shields.io/github/stars/koajs/sendfile.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-sendfile.svg?style=flat-square)
- [koa-file-server](https://github.com/koajs/file-server) - 具有附加功能的静态文件服务，如支持 etag 和 SPDY 推送。 ![](https://img.shields.io/github/stars/koajs/file-server.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-file-server.svg?style=flat-square)
- [koa-stream](https://github.com/claudetech/koa-stream) - 支持范围请求的文件发送实用程序。 ![](https://img.shields.io/github/stars/claudetech/koa-stream.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-stream.svg?style=flat-square)
- [koa-better-serve](https://github.com/tunnckoCore/koa-better-serve) - 使用 `koa-send` 提供小型、简单和正确的文件服务——仅此而已。 ![](https://img.shields.io/github/stars/tunnckoCore/koa-better-serve.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-better-serve.svg?style=flat-square)
- [koa-spa](https://github.com/ktmud/koa-spa) - 基于`koa-static-cache`(静态缓存)构建的单页应用服务器。 ![](https://img.shields.io/github/stars/ktmud/koa-spa.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-spa.svg?style=flat-square)
- [koa-serve-static](https://github.com/koa-modules/serve-static) - 提供静态文件，基于 Express 的 `serve-static`。 ![](https://img.shields.io/github/stars/koa-modules/serve-static.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-serve-static.svg?style=flat-square)
- [koa-static2](https://github.com/Secbone/koa-static2) - 在用户声明的名称下的文件夹提供文件服务。 ![](https://img.shields.io/github/stars/Secbone/koa-static2.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-static2.svg?style=flat-square)
- [koa-static-folder](https://github.com/janpieterz/koajs-static-folder) - 使用文件夹提供静态文件。 ![](https://img.shields.io/github/stars/janpieterz/koajs-static-folder.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-static-folder.svg?style=flat-square)
- [koa-serve-list](https://github.com/koa-modules/serve-list) - 基于 Express 的 `serve-index` 为 koa 提供目录列表。 ![](https://img.shields.io/github/stars/koa-modules/serve-list.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-serve-list.svg?style=flat-square)
- [koa-serve](https://github.com/adamkdean/koa-serve) - 提供静态文件服务的Koa中间件。 ![](https://img.shields.io/github/stars/adamkdean/koa-serve.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-serve.svg?style=flat-square)

### 路由和挂载

- [koa-router](https://github.com/koajs/koa-router) - Koa路由中间件。 ![](https://img.shields.io/github/stars/koajs/koa-router.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/@koa/router.svg?style=flat-square)
- [koa-mount](https://github.com/koajs/mount) - 挂载Koa应用作为中间件。 ![](https://img.shields.io/github/stars/koajs/mount.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-mount.svg?style=flat-square)
- [koa-route](https://github.com/koajs/route) - 一个简单的路由中间件。 ![](https://img.shields.io/github/stars/koajs/route.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-route.svg?style=flat-square)
- [koa-joi-router](https://github.com/koajs/joi-router) - 可配置、输入和输出校验规则的路由。 ![](https://img.shields.io/github/stars/koajs/joi-router.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-joi-router.svg?style=flat-square)
- [koa-trie-router](https://github.com/koajs/trie-router) - 基于字典树的路由。![](https://img.shields.io/github/stars/koajs/trie-router.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-trie-router.svg?style=flat-square)
- [koa-tree-router](https://github.com/steambap/koa-tree-router) - 基于树结构的高性能路由。 ![](https://img.shields.io/github/stars/steambap/koa-tree-router.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-tree-router.svg?style=flat-square)
- [koa-oai-router](https://github.com/BiteBit/koa-oai-router) - Koa 路由，基于 OpenAPI、Swagger 和 Json Schema。 ![](https://img.shields.io/github/stars/BiteBit/koa-oai-router.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-oai-router.svg?style=flat-square)
- [koa-rewrite](https://github.com/koajs/rewrite) - URL重写中间件。 ![](https://img.shields.io/github/stars/koajs/rewrite.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-rewrite.svg?style=flat-square)
- [koa-better-router](https://github.com/tunnckoCore/koa-better-router) - 稳定和可爱的`koa`路由，使用 `path-match`。 轻松构建强大、灵活的RESTful API。 ![](https://img.shields.io/github/stars/tunnckoCore/koa-better-router.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-better-router.svg?style=flat-square)
- [koa-qs](https://github.com/koajs/qs) - 支持嵌套的 query string。 ![](https://img.shields.io/github/stars/koajs/qs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-qs.svg?style=flat-square)
- [koa-rest-router](https://github.com/tunnckoCore/koa-rest-router) - 最强大、灵活和可组合的路由中间件，用于轻松构建企业 RESTful API！ ![](https://img.shields.io/github/stars/tunnckoCore/koa-rest-router.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-rest-router.svg?style=flat-square)
- [koa-66](https://github.com/menems/koa-66) - 用于koa v2路由。 ![](https://img.shields.io/github/stars/menems/koa-66.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-66.svg?style=flat-square)
- [koa-react-router](https://github.com/afenton90/koa-react-router) - koa 2 中间件，用于 React 服务器端渲染和路由使用 [react-router](https://github.com/ReactTraining/react-router) ![](https://img.shields.io/github/stars/afenton90/koa-react-router.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-react-router.svg)
- [koa-combine-routers](https://github.com/saadq/koa-combine-routers) - 组合多个[@koa/router](https://github.com/koajs/koa-router)实例。 ![](https://img.shields.io/github/stars/saadq/koa-combine-routers.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-combine-routers.svg?style=flat-square)
- [koa-mapper](https://github.com/d-band/koa-mapper) - 更好的路由器支持参数验证和 OpenAPI 生成。 ![](https://img.shields.io/github/stars/d-band/koa-mapper.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-mapper.svg?style=flat-square)
- [koa-params](https://github.com/segmentio/koa-params) - 对 koa-route 的 Express 样式参数支持。 ![](https://img.shields.io/github/stars/segmentio/koa-params.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-params.svg?style=flat-square)
- [koa-frouter](https://github.com/MangroveTech/koa-frouter) - File as `path`. ![](https://img.shields.io/github/stars/MangroveTech/koa-frouter.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-frouter.svg?style=flat-square)
- [koa-dec-router](https://github.com/zaaack/koa-dec-router) - 一个 ES6 装饰器 + 基于类的路由器，支持继承、覆盖、优先级、自动加载控制器等。底层使用[koa-router](https://github.com/alexmingoia/koa-router)。 ![](https://img.shields.io/github/stars/zaaack/koa-dec-router.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-dec-router.svg)
- [koa-routing](https://github.com/ivpusic/koa-routing) - 路由中间件。 ![](https://img.shields.io/github/stars/ivpusic/koa-routing.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-routing.svg?style=flat-square)
- [kroute](https://github.com/blakeembrey/kroute) - 模块化 Koa 路由器中间件，带有 Express 风格的路由和中间件挂载。 ![](https://img.shields.io/github/stars/blakeembrey/kroute.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/kroute.svg?style=flat-square)
- [koa-methodoverride](https://github.com/koa-modules/methodoverride) - HTTP 方法覆盖中间件 ![](https://img.shields.io/github/stars/koa-modules/methodoverride.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-methodoverride.svg?style=flat-square)
- [koa-simple-router](https://github.com/gyson/koa-simple-router) - 简单快速的 REST 路由中间件（支持koa 2.x） ![](https://img.shields.io/github/stars/gyson/koa-simple-router.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-simple-router.svg?style=flat-square)
- [koa-sub-domain](https://github.com/Student007/koa-sub-domain) - 处理多级和子域通配符的中间件。 ![](https://img.shields.io/github/stars/Student007/koa-sub-domain.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-sub-domain.svg?style=flat-square)
- [koa2-router](https://github.com/xinpianchang/koa2-router) - 一个Express风格的路由中间件。 ![](https://img.shields.io/github/stars/xinpianchang/koa2-router.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa2-router.svg?style=flat-square)
- [impress-router](https://github.com/magicdawn/impress-router) - Express风格的路由。 ![](https://img.shields.io/github/stars/magicdawn/impress-router.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/impress-router.svg?style=flat-square)
- [koa-bestest-router](https://github.com/TehShrike/koa-bestest-router) - Koa 的路由器中间件。无突变(Mutation-free)，少于100行  ![](https://img.shields.io/github/stars/TehShrike/koa-bestest-router.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-bestest-router.svg?style=flat-square)
- [koa-joi-controllers](https://github.com/giall/koa-joi-controllers) - 对 `koa-joi-router` 封装的控制器装饰器。 ![](https://img.shields.io/github/stars/giall/koa-joi-controllers.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-joi-controllers.svg?style=flat-square)
- [koa-ovenware](https://github.com/zedgu/koa-ovenware) - Koa 的自动模型/控制器加载器。 ![](https://img.shields.io/github/stars/zedgu/koa-ovenware.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-ovenware.svg?style=flat-square)
- [koa-forward-request](https://github.com/nswbmw/koa-forward-request) - 转发请求。![](https://img.shields.io/github/stars/nswbmw/koa-forward-request.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-forward-request.svg?style=flat-square)
- [koa-architect](https://github.com/nervgh/koa-architect) - 自动挂载和路由。 ![](https://img.shields.io/github/stars/nervgh/koa-architect.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-architect.svg?style=flat-square)

### 授权/鉴权

- [koa-jwt](https://github.com/koajs/jwt) - 校验JWT（JSON Web Tokens）的Koa中间件。 ![](https://img.shields.io/github/stars/koajs/jwt.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-jwt.svg?style=flat-square)
- [koa-passport](https://github.com/rkusa/koa-passport) - 基于Passport的鉴权中间件。 ![](https://img.shields.io/github/stars/rkusa/koa-passport.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-passport.svg?style=flat-square)
- [koa-basic-auth](https://github.com/koajs/basic-auth) - 简单的用户密码基础授权。 ![](https://img.shields.io/github/stars/koajs/basic-auth.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-basic-auth.svg?style=flat-square)
- [koa-bearer-token](https://github.com/chentsulin/koa-bearer-token) - Bearer token解析器中间件。 ![](https://img.shields.io/github/stars/chentsulin/koa-bearer-token.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-bearer-token.svg?style=flat-square)
- [koa-statelessauth](https://github.com/jchannon/koa-statelessauth) - 基于 `Authorization` header的自定义验证。 ![](https://img.shields.io/github/stars/jchannon/koa-statelessauth.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-statelessauth.svg?style=flat-square)
- [koa-weixin-token](https://github.com/nealnote/koa-weixin-token) - 微信Token服务。 ![](https://img.shields.io/github/stars/nealnote/koa-weixin-token.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-weixin-token.svg?style=flat-square)
- [koa-police](https://github.com/tuvistavie/koa-police) - 基于策略的身份验证库。 ![](https://img.shields.io/github/stars/tuvistavie/koa-police.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-police.svg?style=flat-square)
- [koa-jwt-mongo](https://github.com/miserylee/koa-jwt-mongo) - 将JWT（JSON Web Tokens）存储在mongodb中的中间件。 ![](https://img.shields.io/github/stars/miserylee/koa-jwt-mongo.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-jwt-mongo.svg?style=flat-square)
- [koa-http-auth](https://github.com/gerhut/koa-http-auth) - 简单的 HTTP 身份验证，包括基本身份验证和摘要（Digest）身份验证。 ![](https://img.shields.io/github/stars/gerhut/koa-http-auth.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-http-auth.svg?style=flat-square)
- [koa-cognito-middleware](https://github.com/uhop/koa-cognito-middleware) - 简单的使用 [AWS Cognito](https://aws.amazon.com/cognito/) [user pools](https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-user-identity-pools.html) 的鉴权。 ![](https://img.shields.io/github/stars/uhop/koa-cognito-middleware.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-cognito-middleware.svg?style=flat-square)

### 数据库

- [koa-mongo](https://github.com/MangroveTech/koa-mongo) - MongoDB中间件，支持连接池。![](https://img.shields.io/github/stars/MangroveTech/koa-mongo.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-mongo.svg?style=flat-square)
- [koa-pagination](https://github.com/seegno/koa-pagination) - 处理[Range Pagination Headers](http://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html), 使用 `Range` & `Content-Range` 实体头. ![](https://img.shields.io/github/stars/seegno/koa-pagination.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-pagination.svg?style=flat-square)
- [koa-pg](https://github.com/chilts/koa-pg) - 自动操作Pg数据库连接。 ![](https://img.shields.io/github/stars/chilts/koa-pg.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-pg.svg?style=flat-square)
- [koa-redis-pool](https://github.com/MangroveTech/koa-redis-pool) - Redis中间件，支持连接池。 ![](https://img.shields.io/github/stars/MangroveTech/koa-redis-pool.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-redis-pool.svg?style=flat-square)
- [koa-orm](https://github.com/d-band/koa-orm) - 使用sequelize & squel的ORM中间件. ![](https://img.shields.io/github/stars/exponentjs/koa-graphiql.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-orm.svg?style=flat-square)
- [koa-waterline](https://github.com/ptariche/koa-waterline) - waterline orm中间件。 ![](https://img.shields.io/github/stars/ptariche/koa-waterline.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-waterline.svg?style=flat-square)

### Graphql

- [koa-graphql](https://github.com/chentsulin/koa-graphql) - 用于创建GraphQL HTTP服务器的中间件。 ![](https://img.shields.io/github/stars/chentsulin/koa-graphql.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-graphql.svg?style=flat-square)
- [koa-graphiql](https://github.com/exponentjs/koa-graphiql) - Koa 中间件用于显示GraphiQL，一个交互式 GraphQL UI。 ![](https://img.shields.io/github/stars/exponentjs/koa-graphiql.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-graphiql.svg?style=flat-square)

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
- [koa-session2](https://github.com/Secbone/koa-session2) - Koa2 的中间件，用于获取/设置与自定义存储（如 Redis 或 mongodb）一起使用的会话。 ![](https://img.shields.io/github/stars/Secbone/koa-session2.svg?style=social&label=Star)  ![](https://img.shields.io/npm/dm/koa-session2.svg?style=flat-square)
- [koa-session-minimal](https://github.com/longztian/koa-session-minimal) - 对`koa-generic-session`的`Koa 2`重写，支持其核心功能和存储。 ![](https://img.shields.io/github/stars/longztian/koa-session-minimal.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-session-minimal.svg?style=flat-square)
- [koa-redis-session-sets](https://github.com/koajs/redis-session-sets) - 带有字段引用交叉集的 Koa Redis Session。 ![](https://img.shields.io/github/stars/koajs/redis-session-sets.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-redis-session-sets.svg?style=flat-square)

### Cookies

- [koa-cookie](https://github.com/varunpal/koa-cookie) - Cookie解析中间件。 ![](https://img.shields.io/github/stars/varunpal/koa-cookie.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-cookie.svg?style=flat-square)

### 缓存

- [koa-cash](https://github.com/koajs/cash) - Koa 的 HTTP 响应缓存。支持 Redis、内存存储等。 ![](https://img.shields.io/github/stars/koajs/cash.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-cash.svg?style=flat-square)
- [koa-etag](https://github.com/koajs/etag) - 为Koa响应提供Etag功能。 ![](https://img.shields.io/github/stars/koajs/etag.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-etag.svg?style=flat-square)
- [koa-conditional-get](https://github.com/koajs/conditional-get) - 条件Get，用于判断是否新鲜。![](https://img.shields.io/github/stars/koajs/conditional-get.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-conditional-get.svg?style=flat-square)
- [koa-cache-lite](https://github.com/mkozjak/koa-cache-lite) - 零依赖的Koa路由缓存。 ![](https://img.shields.io/github/stars/mkozjak/koa-cache-lite.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-cache-lite.svg?style=flat-square)
- [koa-router-cache](https://github.com/nswbmw/koa-router-cache) - 路由缓存中间件。![](https://img.shields.io/github/stars/nswbmw/koa-router-cache.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-router-cache.svg?style=flat-square)

### 限流

- [rate-limiter-flexible](https://github.com/animir/node-rate-limiter-flexible) - 在单进程或分布式环境中按原子增量Key限制请求以防止任何规模的 DDoS 和暴力攻击。 ![](https://img.shields.io/github/stars/animir/node-rate-limiter-flexible.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/rate-limiter-flexible.svg?style=flat-square)
- [koa-ratelimit](https://github.com/koajs/ratelimit) - 限流中间件。 ![](https://img.shields.io/github/stars/koajs/ratelimit.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-ratelimit.svg?style=flat-square)
- [koa-better-ratelimit](https://github.com/tunnckoCore/koa-better-ratelimit) - 支持自定义存储、自定义 ID、自定义错误消息和自定义头。![](https://img.shields.io/github/stars/tunnckoCore/koa-better-ratelimit.svg?style=social&label=Star)  ![](https://img.shields.io/npm/dm/koa-better-ratelimit.svg?style=flat-square)
- [koa-ip-filter](https://github.com/tunnckoCore/koa-ip-filter) - Koa 中间件，可使用glob模式、数组、字符串、正则表达式或匹配器函数过滤请求 IP 或自定义 ID。 支持自定义 403 Forbidden 消息和自定义 ID。 ![](https://img.shields.io/github/stars/tunnckoCore/koa-ip-filter.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-ip-filter.svg?style=flat-square)

### 文档

- [koa-swagger-decorator](https://github.com/Cody2333/koa-swagger-decorator) - 使用装饰器为 koa-router 自动生成 swagger 文档。 ![](https://img.shields.io/github/stars/Cody2333/koa-swagger-decorator.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-swagger-decorator.svg?style=flat-square)
- [swagger2-koa](https://github.com/carlansley/swagger2-koa) - 使用 swagger2 的 Koa 2 中间件。 ![](https://img.shields.io/github/stars/carlansley/swagger2-koa.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/swagger2-koa.svg?style=flat-square)
- [koa-docs](https://github.com/a-s-o/koa-docs) - 用于自动生成和提供API文档的Koa中间件。 ![](https://img.shields.io/github/stars/a-s-o/koa-docs.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-docs.svg?style=flat-square)
- [koa-joi-swagger](https://github.com/zaaack/koa-joi-swagger) - 使用 joi 模式验证请求和响应，并生成 swagger 文档以创建漂亮的 API 文档。 ![](https://img.shields.io/github/stars/zaaack/koa-joi-swagger.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-joi-swagger.svg?style=flat-square)
- [swagger-koa](https://github.com/janvotava/swagger-koa) - Swagger + Koa = {swagger-koa} ![](https://img.shields.io/github/stars/janvotava/swagger-koa.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/swagger-koa.svg?style=flat-square)

### 安全

- [@koa/cors](https://github.com/koajs/cors) - 跨域资源共享（CORS）for koa. ![](https://img.shields.io/github/stars/koajs/cors.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/@koa/cors.svg?style=flat-square)
- [koa-helmet](https://github.com/venables/koa-helmet) - 提供重要的安全头header，使您的应用默认更安全。 ![](https://img.shields.io/github/stars/venables/koa-helmet.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-helmet.svg?style=flat-square)
- [koa-csrf](https://github.com/koajs/csrf) - CSRF tokens。 ![](https://img.shields.io/github/stars/koajs/csrf.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-csrf.svg?style=flat-square)
- [koa-cors](https://github.com/evert0n/koa-cors) - Koa 的 CORS 中间件。 ![](https://img.shields.io/github/stars/evert0n/koa-cors.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-cors.svg?style=flat-square)
- [koa-rbac](https://github.com/yanickrochon/koa-rbac) - 用于Koa的基于角色的权限访问控制。 ![](https://img.shields.io/github/stars/yanickrochon/koa-rbac.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-rbac.svg?style=flat-square)
- [koa-lusca](https://github.com/koajs/koa-lusca) - Koa版本的lusca，用于Koa的应用安全。 ![](https://img.shields.io/github/stars/koajs/koa-lusca.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-lusca.svg?style=flat-square)
- [koa-ip](https://github.com/MangroveTech/koa-ip) - 用于Koa的Ip过滤中间件。支持白名单和黑名单。 ![](https://img.shields.io/github/stars/MangroveTech/koa-ip.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-ip.svg?style=flat-square)
- [koa-authz](https://github.com/node-casbin/koa-authz) - 用于Koa2，基于Casbin的授权中间件。 ![](https://img.shields.io/github/stars/node-casbin/koa-authz.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-authz.svg?style=flat-square)
- [koa-ip-filter](https://github.com/tunnckoCore/koa-ip-filter) - koa 的中间件，它使用 `ip-filter` 和 `micromatch` 根据 glob 模式、RegExp、字符串或 glob 数组过滤 IP。 支持自定义 403 Forbidden 消息和自定义 ID。![](https://img.shields.io/github/stars/tunnckoCore/koa-ip-filter.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-ip-filter.svg?style=flat-square)
- [koa-protect](https://github.com/may215/koa-protect) - 用于koa应用的安全模块。 ![](https://img.shields.io/github/stars/may215/koa-protect.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-protect.svg?style=flat-square)
- [koa-acl](https://github.com/Jackong/koa-acl) - 用于Koa的访问控制列表(ACL)中间件。 ![](https://img.shields.io/github/stars/Jackong/koa-acl.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-acl.svg?style=flat-square)

### 日志

- [koa-logger](https://github.com/koajs/logger) - 开发风格日志中间件。 ![](https://img.shields.io/github/stars/koajs/logger.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-logger.svg?style=flat-square)
- [cabin](https://github.com/cabinjs/cabin) - Node.js、Lad、Koa、Express 和 Passport 的日志记录/分析服务和中间件。 ![](https://img.shields.io/github/stars/cabinjs/cabin.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/cabin.svg?style=flat-square)
- [concurrency-logger](https://github.com/PabloSichert/concurrency-logger) - 分别记录 HTTP 请求/响应，将它们的并发可视化并在请求的上下文中报告日志/错误。 ![](https://img.shields.io/github/stars/PabloSichert/concurrency-logger.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/concurrency-logger.svg?style=flat-square)
- [koa-bunyan-logger](https://github.com/koajs/bunyan-logger) - 使用Bunyan请求日志的Koa中间件。 ![](https://img.shields.io/github/stars/koajs/bunyan-logger.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-bunyan-logger.svg?style=flat-square)
- [koa-log4](https://github.com/dominhhai/koa-log4js) - 基于log4js-node封装的中间件。 ![](https://img.shields.io/github/stars/dominhhai/koa-log4js.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-log4.svg?style=flat-square)
- [koa-pino-logger](https://github.com/pinojs/koa-pino-logger) - Pino日志中间件。 ![](https://img.shields.io/github/stars/pinojs/koa-pino-logger.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-pino-logger.svg?style=flat-square)
- [koa-morgan](https://github.com/koa-modules/morgan) - 基于Morgan的中间件。 ![](https://img.shields.io/github/stars/koa-modules/morgan.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-morgan.svg?style=flat-square)
- [koa-json-logger](https://github.com/rudijs/koa-json-logger) - HTTP请求/响应/错误的JSON格式的日志。 ![](https://img.shields.io/github/stars/rudijs/koa-json-logger.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-json-logger.svg?style=flat-square)
- [koa-bunyan](https://github.com/ivpusic/koa-bunyan) - 使用node-bunyan的中间件。 ![](https://img.shields.io/github/stars/ivpusic/koa-bunyan.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-bunyan.svg?style=flat-square)
- [koa-accesslog](https://github.com/koajs/accesslog) - 通用日志格式访问日志的中间件。 ![](https://img.shields.io/github/stars/koajs/accesslog.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-accesslog.svg?style=flat-square)

### 错误报告

- [koa-onerror](https://github.com/koajs/onerror) - Koa 的错误处理程序，hack ctx.onerror。 ![](https://img.shields.io/github/stars/koajs/onerror.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-onerror.svg?style=flat-square)
- [koa-error](https://github.com/koajs/error) - 错误响应中间件(支持返回text, json, html模板引擎). ![](https://img.shields.io/github/stars/koajs/error.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-error.svg?style=flat-square)
- [koa-json-error](https://github.com/koajs/json-error) - 纯 JSON 应用程序的错误处理程序。 ![](https://img.shields.io/github/stars/koajs/json-error.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-json-error.svg?style=flat-square)
- [koa-errorhandler](https://github.com/nswbmw/koa-errorhandler) - Koa 的错误处理程序中间件。 ![](https://img.shields.io/github/stars/nswbmw/koa-errorhandler.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-errorhandler.svg?style=flat-square)
- [koa-error-slack](https://github.com/rturk/koa-error-slack) - 发送 Koa 错误到 Slack。 ![](https://img.shields.io/github/stars/rturk/koa-error-slack.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-error-slack.svg?style=flat-square)

### i18n

- [koa-locales](https://github.com/koajs/locales) - i18n解决方案。 ![](https://img.shields.io/github/stars/koajs/locales.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-locales.svg?style=flat-square)
- [koa-i18n](https://github.com/koa-modules/i18n) - 基于 i18n-2 的轻量级简单翻译中间件。 ![](https://img.shields.io/github/stars/koa-modules/i18n.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-i18n.svg?style=flat-square)
- [koa-locale](https://github.com/koa-modules/locale) - 从查询参数、子域名、accept-languages或 cookie 中获取区域设置变量。 ![](https://img.shields.io/github/stars/koa-modules/locale.svg?style=social&label=Star) ![](https://img.shields.io/npm/dm/koa-locale.svg?style=flat-square)
