<p align="center">
<img style="padding-right: 20px"src="https://www.dengwb.com/static/logo/owl.png" width="120px"/>
<img src="https://www.dengwb.com/static/logo/Dengwb.png" width="100px"/>
</p>

<p font-size="40px" align="center">基于 Vue 和 Webpack 构建的移动端UI组件库</p>

<p align="center">
  <a href="https://github.com/vuejs/vue" rel="nofollow" target="_blank">
    <img src="https://img.shields.io/badge/vue-2.5.16-brightgreen.svg" alt="vue">
  </a>

  <a href="https://www.npmjs.com/package/owl-ui" rel="nofollow" target="_blank">
    <img src="https://img.shields.io/npm/v/owl-ui.svg?style=flat" alt="npm">
  </a>
    
  <a href="https://github.com/dengwb1991/owl-ui/blob/master/LICENSE" rel="nofollow" target="_blank">
    <img src="https://img.shields.io/npm/l/owl-ui.svg" alt="LICENSE">
  </a>

  <a href="https://github.com/dengwb1991/owl-ui/commits/master" rel="nofollow" target="_blank">
    <img src="https://img.shields.io/github/last-commit/dengwb1991/owl-ui.svg?style=flat-square" alt="commit">
  </a>

  <a href="https://www.npmjs.com/package/owl-ui" rel="nofollow" target="_blank">
    <img src="https://img.shields.io/npm/dt/owl-ui.svg" alt="downloads">
  </a>

  <a href="https://github.com/dengwb1991/owl-ui/stargazers" rel="nofollow" target="_blank">
    <img src="https://img.shields.io/github/stars/dengwb1991/owl-ui.svg?style=social&label=Stars" alt="star">
  </a>

  <a href="https://travis-ci.org/dengwb1991/owl-ui" rel="nofollow" target="_blank">
    <img src="https://api.travis-ci.org/dengwb1991/owl-ui.svg?branch=master" alt="build">
  </a>
</p>

### 文档链接

[官网](http://owl-ui.dengwb.com)

[示例（移动端体验较好）](http://owl-ui.dengwb.com/examples)

<img src="https://owl-ui.dengwb.com/static/images/qr-code.png"/>

### 开发心得链接

[从0到1开发组件库](https://juejin.im/post/5c6504d06fb9a049c6445a25)

### 安装

```bash
npm install owl-ui -S
```

### 使用

```js
import 'owl-ui/lib/flexible' // Mobile adaptive solution
import Vue from 'vue'

import Owl from 'owl-ui'
import 'owl-ui/lib/styles/owl-ui.css'

Vue.use(Owl)
```

### 按需加载

```js
import 'owl-ui/lib/flexible'
import Vue from 'vue'

import Button from 'owl-ui/lib/button/button.js'
import 'owl-ui/lib/button/button.css'

Vue.use(Button)
```

### 开发

```bash
git clone git@github.com:dengwb1991/owl-ui.git

cd owl-ui

npm install 

npm run dev

# 启动文档开发

npm run docs
```

### 命令介绍

```bash

npm run dev             #启动组件开发

npm run docs            #启动文档开发

npm run prod            #组件构建

npm run build           #整体构建

npm run build:style     #样式构建

npm run build:icon      #svg转化为iconfont

npm run build:docs      #文档构建

npm run build:example   #示例构建

npm run build:component #按需组件构建

npm run lint            #eslint测试

npm run unit            #组件单元测试

npm run test            #eslint测试 & 组件单元测试
```
