# vue ssr 服务器端渲染例子

*最近在学习vue ssr，官方文档有的地方未给出实际例子，我将学习过程做的一些demo整理了一下，汇集于此，可供大家参考*

```bash
$ git clone ...
$ cd vue-ssr-exapmple
$ npm install
```

## [demo1 基本例子](./demo1)

```bash
$ npm run demo1
```
ssr与服务器集成的基本例子，对应[官方文档](https://ssr.vuejs.org/zh/basic.html)

## [demo2 组件生命周期钩子函数](./demo2)

```bash
$ npm run demo2
```
vue组件在服务器端渲染，生命周期钩子函数执行情况，对应[官方文档](https://ssr.vuejs.org/zh/universal.html)

## [demo3 源码结构](./demo3)

```bash
$ npm run demo3
```
利用webpack打包的一个基本的源码结构实现, 对应[官方文档](https://ssr.vuejs.org/zh/structure.html)

## [demo4 路由和代码分割](./demo4)

```bash
$ npm run demo4
```

webpack 打包路由和代码分割的实现，对应[官方文档](https://ssr.vuejs.org/zh/routing.html)

## [demo5 数据预取和状态](./demo5)

```bash
$ npm run demo5
```

数据预取和状态demo实现，对应[官方文档](https://ssr.vuejs.org/zh/data.html)

## [demo5-mixin 数据预取和状态——匹配要渲染的视图后，再获取数据 & Store 代码拆分(Store Code Splitting)](./demo5-mixin)

```bash
$ npm run demo5-mixin
```

数据预取和状态demo实现，对应[官方文档](https://ssr.vuejs.org/zh/data.html)

## [demo6 客户端混合](./demo6)

```bash
$ npm run demo6
```

一个混合失败的例子实现，对应[官方文档](https://ssr.vuejs.org/zh/hydration.html)

## [demo7 Bundle Renderer 的构建配置](./demo7)

```bash
# production
$ npm run demo7
# dev
$ npm run demo7:dev
```

ssr实现热加载，对应官方文档，[Bundle Renderer 指引](https://ssr.vuejs.org/zh/bundle-renderer.html)，[构建配置](https://ssr.vuejs.org/zh/build-config.html)

# [demo8 CSS 管理](./demo8)

```bash
$ npm run demo8
```
css 提取实现，对应官方文档，[css 管理](https://ssr.vuejs.org/zh/css.html)

# [demo9 Head 管理](./demo9)

```bash
$ npm run demo9
```

ssr动态Head改变实现方案，对应官网文档，[Head 管理](https://ssr.vuejs.org/zh/head.html)

