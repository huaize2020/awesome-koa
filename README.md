[English](./README-en.md) | 简体中文

## 目录

- [目录](#目录)
- [官方文档](#官方文档)
- [框架](#框架)
- [中间件](#中间件)
  - [JSON](#json)
  - [JSONP](#jsonp)
  - [模板引擎](#模板引擎)
  - [文件服务](#文件服务)
  - [Session](#session)
  - [日志](#日志)
  - [错误报告](#错误报告)
  - [i18n](#i18n)

## 官方文档

- [官网](https://koajs.com/)
- [仓库](https://github.com/koajs/koa)
- [Wiki](https://github.com/koajs/koa/wiki)

## 框架

- [Egg](https://github.com/eggjs/egg) - 一款自带工作流引擎的Node.js全栈框架。
- [ThinkJS](https://github.com/thinkjs/thinkjs) - 支持ES2015 +的框架, 支持TypeScript。
- [lad](https://github.com/ladjs/lad) - 最好的Node.js框架，由前Express和Koa团队成员创建。
- [CabloyJS](https://github.com/zhennann/Cabloy) - 一款自带工作流引擎的Node.js全栈框架, 基于koa + egg + vue + framework7.
- [koatty](https://github.com/Koatty/koatty) - Koa2 + Typescript = Koatty。使用Typescript装饰器实现了控制反转和面向切面编程。

## 中间件

### JSON

- [koa-json](https://github.com/koajs/json) - 将 JSON 打印美化的响应中间件。
- [koa-json-filter](https://github.com/koajs/json-filter) - 该中间件允许客户端只过滤他们需要的响应，减少线路上的流量。
- [koa-json-mask](https://github.com/nemtsov/koa-json-mask) - 该中间件允许客户端只过滤他们需要的响应，减少线路上的流量。
- [koa-is-json](https://github.com/koajs/is-json) - 检查 koa 主体是否应该被解析为 JSON。

### JSONP

- [koa-jsonp](https://github.com/kilianc/koa-jsonp) - 支持GET/POST JSONP流的中间件。
- [koa-safe-jsonp](https://github.com/koajs/koa-safe-jsonp) - 安全的Koa JSONP插件。
- [koa-response-jsonp](https://github.com/keenwon/koa-response-jsonp) - KOA JSONP中间件。

### 模板引擎

- [koa-ejs](https://github.com/koajs/ejs) - Koa视图渲染中间件，支持ejs所有特性。
- [koa-react-view](https://github.com/koajs/react-view) - Koa视图渲染中间件，用于在服务端渲染React组件。

### 文件服务

- [koa-static](https://github.com/koajs/static) - 静态文件服务中间件。
- [koa-send](https://github.com/koajs/send) - 传送静态文件。

### Session

- [koa-session](https://github.com/koajs/session) - 简单基于Cookie的Session中间件。
- [koa-generic-session](https://github.com/koajs/generic-session) - 基于内存、redis或其他的Session存储中间件。
- [koa-redis](https://github.com/koajs/koa-redis) - 使用Redis的Koa Session。
- [koa-redis-session-sets](https://github.com/koajs/redis-session-sets) - 带有字段引用交叉集的 Koa Redis Session。

### 日志

- [koa-logger](https://github.com/koajs/logger) - 开发风格日志中间件。
- [koa-bunyan-logger](https://github.com/koajs/bunyan-logger) - 使用Bunyan请求日志的Koa中间件。
- [koa-accesslog](https://github.com/koajs/accesslog) - 通用日志格式访问日志的中间件。

### 错误报告

- [koa-error](https://github.com/koajs/error) - 错误响应中间件(支持返回text, json, html模板引擎).
- [koa-onerror](https://github.com/koajs/onerror) - Koa 的错误处理程序，hack ctx.onerror。
- [koa-json-error](https://github.com/koajs/json-error) - 纯 JSON 应用程序的错误处理程序。
- [koa-errorhandler](https://github.com/nswbmw/koa-errorhandler) - Koa 的错误处理程序中间件。
- [koa-error-slack](https://github.com/rturk/koa-error-slack) - 发送 Koa 错误到 Slack。

### i18n

- [koa-locale](https://github.com/koa-modules/locale) - 从查询参数、子域名、accept-languages或 cookie 中获取区域设置变量。
- [koa-i18n](https://github.com/koa-modules/i18n) - 基于 i18n-2 的轻量级简单翻译中间件。
