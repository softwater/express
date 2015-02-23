[![Express Logo](https://i.cloudup.com/zfY6lL7eFa-3000x3000.png)](http://expressjs.com/)

  该项目fork自：https://github.com/strongloop/express。

  该项目用于学习之用，相对于原项目有修改。

  Fast, unopinionated, minimalist web framework for [node](http://nodejs.org).

 [node](http://nodejs.org)的快速，unopinionated，简约的web框架。

  [![NPM Version][npm-image]][npm-url]
  [![NPM Downloads][downloads-image]][downloads-url]
  [![Build Status][travis-image]][travis-url]
  [![Test Coverage][coveralls-image]][coveralls-url]

```js
var express = require('express')
var app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
```

## Installation

```bash
$ npm install express
```

## Features

  * Robust routing（强大的路由选择）
  * Focus on high performance（专注于高性能）
  * Super-high test coverage（超高水平的测试覆盖）
  * HTTP helpers (redirection, caching, etc)（http工具，如重定向，缓存等）
  * View system supporting 14+ template engines（支持14个以上的模版引擎）
  * Content negotiation（上下文转让）
  * Executable for generating applications quickly（快速生成应用程序可执行文件）

## Docs & Community

  * [Website and Documentation](http://expressjs.com/) - [[website repo](https://github.com/strongloop/expressjs.com)]
        [[中文文档](http://expressjs.jser.us/)]
  * [#express](https://webchat.freenode.net/?channels=express) on freenode IRC
  * [Github Organization](https://github.com/expressjs) for Official Middleware & Modules
  * Visit the [Wiki](https://github.com/strongloop/express/wiki)
        [[我的翻译]]
  * [Google Group](https://groups.google.com/group/express-js) for discussion
  * [Русскоязычная документация](http://jsman.ru/express/)
  * [한국어 문서](http://expressjs.kr) - [[website repo](https://github.com/Hanul/expressjs.kr)]

**PROTIP** Be sure to read [Migrating from 3.x to 4.x](https://github.com/strongloop/express/wiki/Migrating-from-3.x-to-4.x) as well as [New features in 4.x](https://github.com/strongloop/express/wiki/New-features-in-4.x).

**PROTIP** 一定要阅读[Migrating from 3.x to 4.x](https://github.com/strongloop/express/wiki/Migrating-from-3.x-to-4.x) 和 [New features in 4.x](https://github.com/strongloop/express/wiki/New-features-in-4.x).

## Quick Start（快速入门）

  The quickest way to get started with express is to utilize the executable [`express(1)`](https://github.com/expressjs/generator) to generate an application as shown below:

  最快的启动express的方法是使用可执行的[`express(1)`](https://github.com/expressjs/generator)生成一个应用程序，如下：

  Install the executable. The executable's major version will match Express's:

  安装可执行文件。可执行文件的版本要与express的相同。

```bash
$ npm install -g express-generator@4
```

  Create the app:

  创建app：

```bash
$ express /tmp/foo && cd /tmp/foo
```

  Install dependencies:

  安装依赖包：

```bash
$ npm install
```

  Start the server:

  启动服务：

```bash
$ npm start
```

  在浏览器中输入localhost:3000查看效果。

## Philosophy（宗旨，哲学理念）

  The Express philosophy is to provide small, robust tooling for HTTP servers, making
  it a great solution for single page applications, web sites, hybrids, or public
  HTTP APIs.

  express的宗旨是提供小体积，健壮的http服务工具，使之成为单页面应用，网站，hybrids，公共http访问接口的强大解决方案。

  Express does not force you to use any specific ORM or template engine. With support for over
  14 template engines via [Consolidate.js](https://github.com/tj/consolidate.js),
  you can quickly craft your perfect framework.

  express不会强制你使用任何特定的orm和模板引擎。通过[Consolidate.js](https://github.com/tj/consolidate.js)
  支持14种以上的模板引擎，可以快速的制作完美的框架。

## Examples

  To view the examples, clone the Express repo and install the dependancies:

  查看示例，请克隆express仓库和安装依赖包：

```bash
$ git clone git://github.com/strongloop/express.git --depth 1
$ cd express
$ npm install
```

  Then run whichever example you want:

  然后运行任何你想运行的示例：

```bash
$ node examples/content-negotiation
```

## Tests

  To run the test suite, first install the dependancies, then run `npm test`:

  运行测试套件，请先安装依赖包，然后运行 `npm test`：

```bash
$ npm install
$ npm test
```

## People

The original author of Express is [TJ Holowaychuk](https://github.com/tj) [![TJ's Gratipay][gratipay-image-visionmedia]][gratipay-url-visionmedia]

The current lead maintainer is [Douglas Christopher Wilson](https://github.com/dougwilson) [![Doug's Gratipay][gratipay-image-dougwilson]][gratipay-url-dougwilson]

[List of all contributors](https://github.com/strongloop/express/graphs/contributors)

## License

  [MIT](LICENSE)

[npm-image]: https://img.shields.io/npm/v/express.svg?style=flat
[npm-url]: https://npmjs.org/package/express
[downloads-image]: https://img.shields.io/npm/dm/express.svg?style=flat
[downloads-url]: https://npmjs.org/package/express
[travis-image]: https://img.shields.io/travis/strongloop/express.svg?style=flat
[travis-url]: https://travis-ci.org/strongloop/express
[coveralls-image]: https://img.shields.io/coveralls/strongloop/express.svg?style=flat
[coveralls-url]: https://coveralls.io/r/strongloop/express?branch=master
[gratipay-image-visionmedia]: https://img.shields.io/gratipay/visionmedia.svg?style=flat
[gratipay-url-visionmedia]: https://gratipay.com/visionmedia/
[gratipay-image-dougwilson]: https://img.shields.io/gratipay/dougwilson.svg?style=flat
[gratipay-url-dougwilson]: https://gratipay.com/dougwilson/
