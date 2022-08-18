<div align="center">
  <h2>FAKECSS</h2>
  <p>基于Vue3的运行时css框架</p>
  <p>
    文档撰写中
  </p>
  <p>
    <img src="https://img.shields.io/badge/vue-v3.2.0%2B-%23407fbc" alt="vue">
    <img src="https://img.shields.io/codecov/c/github/so11y/fake-css" alt="codecov">
    <img src="https://github.com/so11y/fake-css/actions/workflows/main.yml/badge.svg" alt="test">
  </p>
</div>

---


### 介绍

1. fake-css是一个基于`Vue3`开发的运行时`css`库,开箱即用,零预先配置。
2. 不存在真正意义上的css文件,又如同有文件一般正常运行。
3. 从根源上解决项目包大小的问题。
4. 如果你熟悉`tailwindcss` 或者 `windicss` 等原子css,将极易上手。

### 在线体验

点击 [stackblitz](https://vitest.dev/](https://stackblitz.com/edit/vue-z4jhgv?file=src/App.vue)).

### 下载

```shell
# 通过npm或yarn安装

# npm
npm i fake-css

# yarn
yarn add fake-css
```


### 特性
1. 提供class和style解析方式
2. 搭配vue3响应式
3. 轻量
4. 模块化定义,变相scoped
5. 高度自定义解析方式
6. 支持Typescript

### 阶段

1. 目前任处于构思阶段,基本情况已经固定。



### 示例

1. 更多使用方式可以在项目中playground查看

``` html

<template>
    <!--
       1. 你在在pt_xx 这里输入你任何的数值,都将会动态解析
       2. pt (padding_top), ml (margint_left) 等等。
    -->
    <div :class="[css.pt_30]">

    </div>
</template>

```





