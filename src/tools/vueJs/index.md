---
type: tools
subType: vueJs
title: vueJs
date: 2017/12/27
---


## Vue.js 是什么

Vue (读音 /vjuː/，类似于 **view**) 是一套用于构建用户界面的**渐进式框架**。与其它大型框架不同的是，Vue 被设计为可以自底向上逐层应用。Vue 的核心库只关注视图层，不仅易于上手，还便于与第三方库或既有项目整合。
另一方面，当与[现代化的工具链]以及各种[支持类库](https://github.com/vuejs/awesome-vue#libraries--plugins)结合使用时，Vue 也完全能够为复杂的单页应用提供驱动。


## 原理

核心在于 **[虚拟dom](https://reactjs.org/docs/faq-internals.html#what-is-the-virtual-dom)**。通过虚拟dom实现组件视图和数据的初始化绑定。使得开发者后续将主要工作放在数据的维护上，而不是dom操作上（这点写过zepto或者jquery的同学应该深有体会！）。
当然vueJs还提供了很多其他的语法糖：计算属性、输入绑定（v-model）、模板语法等


## 适用情况

 > 大中型项目（当然喜欢reactJs的同学也可以考虑reactJs,两者没有本质区别了！）。

 > 高度可复用的页面组件化
 
 > dom交互复杂或者说反向操作比较多等
 
 
 <small>
 **译者注**
[1] 更多更全面的教程和语法API可以移步 [vueJs官网](https://cn.vuejs.org)。
 </small>