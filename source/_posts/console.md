---
title: console
date: 2022-03-04 17:59:03
tags:
cover: https://7465-test-9g28n0kc3da62e81-1305695530.tcb.qcloud.la/my-image.gif?sign=ddb62049ab829480c5984c278fef7f5e&t=1646389269
---

<img src="./console/7d9a0b3a233368afc38ae348851a6ba6.jpg" style="zoom:50%;" />

![](/images/7d9a0b3a233368afc38ae348851a6ba6.jpg)

**`Console`** 对象提供了浏览器控制台调试的接口（如：Firefox 的 [Web Console](https://developer.mozilla.org/en-US/docs/Tools/Web_Console)）。在不同浏览器上它的工作方式可能不一样，但通常都会提供一套共性的功能。

`Console` 对象可以从任何全局对象中访问到，如 浏览器作用域上的 [`Window`](https://developer.mozilla.org/zh-CN/docs/Web/API/Window)，以及通过属性控制台作为workers中的特定变体的 [`WorkerGlobalScope`](https://developer.mozilla.org/zh-CN/docs/Web/API/WorkerGlobalScope)。可以通过 [`Window.console`](https://developer.mozilla.org/zh-CN/docs/Web/API/Window/console) 引用，也可以简单的通过 `console` 引用。例：

```
console.log("Failed to open the specified link")
```

### 方法

- [`Console.assert()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/assert)

  如果第一个参数为 `false` ，则将消息和堆栈跟踪记录到控制台。

- [`Console.clear()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/clear)

  清空控制台，并输出 `Console was cleared`。

- [`Console.count()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/count)

  以参数为标识记录调用的次数，调用时在控制台打印标识以及调用次数。

- [`Console.countReset()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/countReset)

  重置指定标签的计数器值。

- [`Console.debug()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/debug)

  在控制台打印一条 `"debug"` 级别的消息。

- [`Console.dir()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/dir)

  显示一个由特定的 Javascript 对象列表组成的可交互列表。这个列表可以使用三角形隐藏和显示来审查子对象的内容。.

- [`Console.dirxml()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/dirxml)

  打印 XML/HTML 元素表示的指定对象，否则显示 JavaScript 对象视图。

- [`Console.error()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/error)

  打印一条错误信息，使用方法可以参考 [string substitution](https://developer.mozilla.org/en-US/docs/Web/API/console#using_string_substitutions)。

- `Console.exception()` Non-Standard Deprecated

  `error()` 方法的别称。

- [`Console.group()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/group)

  创建一个新的内联 [group](https://developer.mozilla.org/en-US/docs/Web/API/console#using_groups_in_the_console), 后续所有打印内容将会以子层级的形式展示。调用 `groupEnd()`来闭合组。

- [`Console.groupCollapsed()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/groupCollapsed)

  创建一个新的内联 [group](https://developer.mozilla.org/en-US/docs/Web/API/console#using_groups_in_the_console)。使用方法和 `group()` 相同，不同的是，`groupCollapsed()` 方法打印出来的内容默认是折叠的。调用`groupEnd()`来闭合组。

- [`Console.groupEnd()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/groupEnd)

  闭合当前内联 [group](https://developer.mozilla.org/en-US/docs/Web/API/console#Using_groups_in_the_console)。

- [`Console.info()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/info)

  打印资讯类说明信息，使用方法可以参考 [string substitution](https://developer.mozilla.org/en-US/docs/Web/API/console#using_string_substitutions)。

- [`Console.log()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/log)

  打印内容的通用方法，使用方法可以参考 [string substitution](https://developer.mozilla.org/en-US/docs/Web/API/console#using_string_substitutions)。

- [`Console.profile()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/profile) Non-Standard

  Starts the browser's built-in profiler (for example, the [Firefox performance tool](https://firefox-source-docs.mozilla.org/devtools-user/performance/index.html)). You can specify an optional name for the profile.

- [`Console.profileEnd()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/profileEnd) Non-Standard

  Stops the profiler. You can see the resulting profile in the browser's performance tool (for example, the [Firefox performance tool](https://firefox-source-docs.mozilla.org/devtools-user/performance/index.html)).

- [`Console.table()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/table)

  将列表型的数据打印成表格。

- [`Console.time()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/time)

  启动一个以入参作为特定名称的[计时器](https://developer.mozilla.org/en-US/docs/Web/API/console#Timers)，在显示页面中可同时运行的计时器上限为10,000.

- [`Console.timeEnd()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/timeEnd)

  结束特定的 [计时器](https://developer.mozilla.org/en-US/docs/Web/API/console#Timers) 并以毫秒打印其从开始到结束所用的时间。

- [`Console.timeLog()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/timeLog)

  打印特定 [计时器](https://developer.mozilla.org/en-US/docs/Web/API/console#timers) 所运行的时间。

- [`Console.timeStamp()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/timeStamp) Non-Standard

  添加一个标记到浏览器的 [Timeline](https://developer.chrome.com/devtools/docs/timeline) 或 [Waterfall](https://developer.mozilla.org/en-US/docs/Tools/Performance/Waterfall) 工具。

- [`Console.trace()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/trace)

  输出一个 [stack trace](https://developer.mozilla.org/en-US/docs/Web/API/console#stack_traces)。

- [`Console.warn()`](https://developer.mozilla.org/zh-CN/docs/Web/API/Console/warn)

  打印一个警告信息，可以使用 [string substitution](https://developer.mozilla.org/en-US/docs/Web/API/console#using_string_substitutions) 和额外的参数。
