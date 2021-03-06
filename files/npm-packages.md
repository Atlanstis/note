# NPM 包

## 服务类

1. [serve](https://www.npmjs.com/package/serve)：创建一个轻量级的 Web 服务。

```shell
// 安装
$ yarn global add serve
// 使用，以当前目录创建一个 Web 服务
$ serve .
```

## Node.js

1. [cross-spawn](https://www.npmjs.com/package/cross-spawn)：一个跨平台执行 Node.js 脚本的插件。

```shell
// 安装
$ yarn add cross-spawn
```

```js
// 使用
const spawn = require('cross-spawn');
 
// Spawn NPM asynchronously
const child = spawn('npm', ['list', '-g', '-depth', '0'], { stdio: 'inherit' });
 
// Spawn NPM synchronously
const result = spawn.sync('npm', ['list', '-g', '-depth', '0'], { stdio: 'inherit' });
```

## webpack

1. Webpack & webpack-cli
2. 

## 脚手架

1. [plop](https://www.npmjs.com/package/plop)：小型脚手架工具

## 工具库

1. [lodash](https://www.lodashjs.com/)：一个一致性、模块化、高性能的 JavaScript 实用工具库。