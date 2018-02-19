# vue-guide

> relearn vue.js

## 基础

### 介绍

Vue是一套用于构建用户界面的渐进式框架。

### 兼容性

Vue不支持IE8及以下版本。

### 调试工具

[Vue Devtools](https://github.com/vuejs/vue-devtools#vue-devtools)

### 安装方式

- 直接使用script标签引入
- NPM

### vue组件理念

VueJS把页面划分为一个个小组件，组件本质上是一个拥有预定义选项的vue实例。这意味着我们可以使用小型、独立的、可复用的组件构建大型应用。因此，在VueJS中，页面会被抽象为一个组件树。

Vue组件参考了[web组件规范](https://www.w3.org/wiki/WebComponents/)。Web组件规范包括Shadow DOM、Custom Elements和HTMLImports三部分。

- Shadow DOM(允许用户以一种隐藏内部实现的方式对外提供组件,这个组件会渲染到DOM树中,但常规方式无法查看到该组件元素的内部细节)
- Custom Elements(使得浏览器可以识别用户自定义的元素并且知道对应的元素行为,自定义元素名字必须包含一个破折号-)
- HTML Imports(Web Components的打包机制)
