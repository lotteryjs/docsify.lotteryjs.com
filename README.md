# Home

> 也许这里会有一些你感兴趣的东西。

> 分析一款不依赖于任何框架的产品，也许会对你有用。（也许没什么卵用🤣）

> 因为我工作中会经常书写 Markdown 文档，所以我希望对这个工具 ([docsify](https://github.com/docsifyjs/docsify)) 有足够的了解😀。

### Local preview in your browser

```sh
git clone https://github.com/lotteryjs/docsify.lotteryjs.com.git
cd docsify.lotteryjs.com
docker-compose up -d
```

[http://localhost:4000](http://localhost:4000)

### To-Do List 

Everything start with `this._init()`

9 步（逻辑记忆）

- config (加载配置)
  - 合并配置(window.$docsify)
  - 处理 script 标签中的 `data-*` 属性配置
  - 处理 `loadSidebar` 配置项(侧边栏)
  - 处理 `loadNavbar` 配置项(导航栏)
  - 处理 `coverpage` 配置项(封面)
  - 处理 `repo` 配置项(GitHub角标)
  - 处理 `name` 配置项(文档名称)
- initLifecycle(Init hooks)
  - 定义 `docsify` 实例各个阶段的 hooks，方便扩展
  
- initPlugin(Install plugins)
- callHook(`init` hook)
- initRouter(Add router)
- initRender(Render base DOM)
- initEvent(Bind events)
- initFetch(Fetch data)
- callHook(`mounted` hook)



#### Docsify Core


### Mind maps

1. Docsify Mixin：为 Docsify() 注入原型方法。

![Docsify](./images/naotu/1.Docsify.png)

2. Docsify.prototype._init

![Docsify.prototype._init](./images/naotu/2.Docsify.prototype._init.png)

### Refs

* [docs-ssr](https://github.com/lotteryjs/docs-ssr)
* [Docsify 深入源码](https://mp.weixin.qq.com/s/Sb0bMNz1PdmGgFF_W5sZDA?)