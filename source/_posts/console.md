---
title: console
date: 2022-03-04 17:59:03
tags:
cover: https://7465-test-9g28n0kc3da62e81-1305695530.tcb.qcloud.la/my-image.gif?sign=ddb62049ab829480c5984c278fef7f5e&t=1646389269
---

![](/totop01/source/images/ad57f756ce6fc7b14.jpeg)


{% asset_img ad57f756ce6fc7b14.jpeg This is an example image %}

**`Console`** 对象提供了浏览器控制台调试的接口（如：Firefox 的 [Web Console](https://developer.mozilla.org/en-US/docs/Tools/Web_Console)）。在不同浏览器上它的工作方式可能不一样，但通常都会提供一套共性的功能。

`Console` 对象可以从任何全局对象中访问到，如 浏览器作用域上的 [`Window`](https://developer.mozilla.org/zh-CN/docs/Web/API/Window)，以及通过属性控制台作为workers中的特定变体的 [`WorkerGlobalScope`](https://developer.mozilla.org/zh-CN/docs/Web/API/WorkerGlobalScope)。可以通过 [`Window.console`](https://developer.mozilla.org/zh-CN/docs/Web/API/Window/console) 引用，也可以简单的通过 `console` 引用。例：

```
console.log("Failed to open the specified link")
```
