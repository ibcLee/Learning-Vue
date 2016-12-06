# Learning-Vue
Vue.js get Started!

### 指令
`v-bind`指令被用来响应地更新html属性

`v-on`指令用于监听DOM事件

### 缩写
#### `v-bind`缩写
```html
<!-- 完整语法 -->
<a v-bind:href="url"></a>
<!-- 缩写 -->
<a :href="url"></a>
```
#### `v-on`缩写
```html
<!-- 完整语法 -->
<a v-on:click="doSomething"></a>
<!-- 缩写 -->
<a @click="doSomething"></a>
```
#### 內联样式
`v-bind:style`

#### 条件渲染
`v-show`不支持`<template>`语法，有`v-show`的元素会始终渲染并保持在DOM中，`v-show`是简单的切换元素的css属性`display`

#### 对象迭代`v-for`
#### 整数迭代`v-for`

#### 事件修饰符
* `.stop`
* `.prevent`
* `.capture`
*  `.self`
#### 按键别名
* `.enter`
* `.tab`
* `.delete`
* `.esc`
* `.space`
* `.up`
* `.down`
* `.left`
* `.right`

#### 修饰符
`.lazy`在`change`事件中同步
`.number`自动将用户的输入值转为Number类型（如果原值的转换结果为NaN则返回原值）
`.trim`自动过滤用户输入的首位空格
