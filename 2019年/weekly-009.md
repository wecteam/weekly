# WecTeam 前端周刊：第 009 期

## 前言

[WecTeam 前端周刊](https://github.com/wecteam/weekly)（github.com/wecteam/weekly）是由京东社交电商部维C团维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 009 期发布时间：2019-11-01。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。

## 周刊文章

#### 1、[【原创】手写一个四则运算表达式转换成AST的方法（下）](https://mp.weixin.qq.com/s/lHYZja_EFRl4s5UQH-kL3w)

本文作者@吴冠禧。[上篇](https://mp.weixin.qq.com/s/HMggcevKJ9afZFqHgm0e5A)我们利用「有限状态机」成功实现了「词法分析」，本篇将进入到「语法分析」及后续部分。

#### 2、[【原创】WebAssembly实战-在浏览器中使用ImageMagick](https://mp.weixin.qq.com/s/FiJYBjestHUk22z_nSYwrQ)

本文作者@刘辉。ImageMagick 是著名的 C/C++ 图形工具库，有命令行上的 `PhotoShop` 之称，支持包括 psd，ai 等超过 200 种格式图像的各种处理，本次我们把 `ImageMagick` 移植到前端，用它来在浏览器中完成各种图像处理操作。

#### 3、[现代浏览器观察者 Observer API 指南](https://juejin.im/post/5db10695e51d452a091fde90)

本文介绍了现代浏览器支持的四种不同类型的观察者（交叉观察者，变动观察者，视图观察者，性能观察者），这四个观察者，都非常适合集成到监控系统。

#### 4、[自动化 Web 性能分析之 Puppeteer 爬虫实践](https://juejin.im/post/5d90ca605188252ca056c44c)

Puppeteer 是一个 Node 库，它提供了一整套高级 API 来通过 DevTools 协议控制 Chromium 或 Chrome。正如其翻译为“操纵木偶的人”一样， 你可以通过 Puppeteer 的提供的 API 直接控制 Chrome，模拟大部分用户操作来进行 UI 测试或者作为爬虫访问页面来收集数据。

#### 5、[「前端进阶」高性能渲染十万条数据(虚拟列表)](https://juejin.im/post/5db684ddf265da4d495c40e5)

在工作中，有时会遇到需要一些不能使用分页方式来加载列表数据的业务情况，对于此，我们称这种列表叫做长列表。比如，在一些外汇交易系统中，前端会实时的展示用户的持仓情况(收益、亏损、手数等)，此时对于用户的持仓列表一般是不能分页的。

在高性能渲染十万条数据(时间分片)一文中，提到了可以使用时间分片的方式来对长列表进行渲染，但这种方式更适用于列表项的DOM结构十分简单的情况。本文会介绍使用虚拟列表的方式，来同时加载大量数据。

#### 6、[爱奇艺直播 WebAssembly 优化之路](https://mp.weixin.qq.com/s/LRGNOuFwHXALs_lhPyN3Zw)

在WebAssembly出现之前，JavaScript是浏览器里可以运行的唯一的编程语言。而WebAssembly技术使浏览器运行别的语言编写的程序变成了可能。
本篇文章是爱奇艺在WebAssembly上的实践总结。

#### 7、[面向传统，Serverless 进化之路](https://zhuanlan.zhihu.com/p/87940654)

主要讲述的是阿里集团内部逐步迁移到 Serverless 体系的过程以及思考，在 JSConf China 上做过分享。

#### 8、[Flutter在京东7FRESH的业务实践](https://mp.weixin.qq.com/s/N2W3u0Od7WgLretuE5T8RA)

讲述了京东7FRESH团队在他们业务中的Flutter实践，总结了期间遇到的一些问题以及对应的解决方案，最终向我们呈现了Flutter实践所达到的收益。

#### 9、[webpack 5 之持久化缓存指南](https://mp.weixin.qq.com/s/oB5eYax_NndcM5IinPgzNQ)

继 webpack v5-beta0 发布后，官方又发布了持久化缓存指南。
