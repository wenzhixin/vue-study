## 起步

使用 npm 安装需要的组件，入门 Hello Vue。

**要求：**

* 安装需要的 node_modules，整个课程中，我们使用了 jQuery、Boostrap、和 Vue2 进行开发学习。
使用以下命令进行安装：
```
npm install
```

### 知识点

* 打开 `1/index.html`，我们引入了 jQuery、Boostrap、和 Vue2，基本框架为：

```html
<div class="container" id="app">
    <h3>{{message}}</h3>
</div>
```

```js
new Vue({
    el: '#app',
    data: {
        message: 'Hello Vue.js'
    }
});
```

* `el` 为实例提供挂载元素。对应我们页面中 id="app"，表示整个 div 都是 vue 来管理。

* `data` Vue 实例的数据对象，把需要的数据都定义在 data 中。

* 绑定除了使用 {{}}，还可以使用 `v-bind`，如 `title="{{message}}"` 或 `v-bind:title="message"`。


### 任务

* 修改 message 的数据，认识数据绑定
* 增加 title 属性，对比使用 `{{}}` 和 `v-bind` 的区别
