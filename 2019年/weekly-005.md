
# WecTeam 前端周刊：第 005 期

## 前言

[WecTeam 前端周刊](https://github.com/wecteam/weekly)（github.com/wecteam/weekly）是由京东社交电商部维C团维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 005 期发布时间：2019-09-27。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。

## 内容

#### 1、[【原创】你还在用图片做引导蒙层？](https://mp.weixin.qq.com/s/XotuXv-EPv-VLNHJ6r7htg)

本文作者@**罗文林**。本文讲述六种思路来实现引导蒙层，在一定情况下都能满足业务需求，从不同角度来实现了引导蒙层。z-index最简单，canvas最灵活，就个人而言，更加喜欢骨架屏式的动态opacity蒙层实现，更有趣更酷。

#### 2、[【原创】前端资源治理（一）:问题及思路](https://mp.weixin.qq.com/s/7kOscvap3bBR-tTJM8ckPA)

本文作者@**李刚松**。笔者对“前端资源治理”的定义是：将前端相关的页面、js/css/图片/字体、接口、配置、监控点等的依赖关系进行收集、存储和管理，并将割裂的组件系统、配置系统、监控系统、业务系统等进行重构和整合，最终形成以页面管理为基础的统一的有序的平台，所有关联信息都能够被查询和检索，最终实现整体协作效率的提升。

#### 3、[【原创】记一次Node.js直出服务的性能优化](https://mp.weixin.qq.com/s/knx_YeT0_Pv8ffV-gN9r9Q)

本文作者@**肖睦群、李刚松**。MPM（Market Page Maker）是京东社交电商部的组件化的页面可视化搭建平台，于2016年9月份上线，平均每周150+个页面，目前已经成为社交电商部的一个核心系统。系统使用Vue.js作为组件化的基础框架,并于2017年5月份上线了Node.js直出服务。

由于很多告警问题主要是流量暴涨导致的CPU使用率过大，我们本次重点优化服务的CPU消耗性能。分析CPU消耗的方法有多种,我们选择其中操作比较简单的v8-profiler方案：安装NPM包v8-profiler，在直出服务中添加监控代码，打包发布到预发布环境进行压测，收集监控数据再进行分析。

#### 4、[深入浅出动画帧后，我再也不怕动画了](https://mp.weixin.qq.com/s/D-Nd6fAp-X0mjqYwoU0hKg)

在前端性能优化策略中，耳熟能详的手段有，雅虎 35 条军规，使用 cache，减少请求数量，使用cookie-free domain，critical asset，使用 CDN，Lazy load，PreLoad 等，这些手段其实主要都是围绕怎么样更快的拿到所需关键资源。当我们把这一步做到很好，没有可优化空间了，其实还可以从另外一个方向去做优化，那就是浏览器渲染方面。文章从动画帧角度，描述了怎么样做一些优化工作。

#### 5、[JS+Canvas 带你体验「偶消奇不消」的智商挑战](https://segmentfault.com/a/1190000020268623)

canvas实现的最强大脑小游戏了解一下。

#### 6、[Nuxt 自适应 SSR 方案: SEO 和首屏最小化优化](https://juejin.im/post/5d87433151882548e51f8b46)

什么才是完美的SSR？一方面是页面的SEO优化，另一方面是对于用户体验的极致追求，要达到更好的SEO就得直出整个页面，而要让用户获得更优质的浏览体验就得务求精确的首屏直出，两者似乎不可调和。如何在这两者间取得平衡，本文提供了一个有趣的思路。

#### 7、[设计与算法 | Google Photos Web UI](https://mp.weixin.qq.com/s/XZw5yI_PBcD7VXO0NxnyNw)

详细阐述了Google Photos的照片布局实现过程，追求极致体验的交互与设计提现的淋漓尽致。

#### 8、[打破框架的范式之争](https://mp.weixin.qq.com/s/0YuYBqD2qWf_EgKMbow1dw)

这篇文章是工业聚大佬在 9.17 的 Github 首次粉丝见面会上演讲内容的文字稿，有兴趣的可以一读。

#### 9、[Vue性能提升之Object.freeze()](https://juejin.im/post/5d5e89aee51d453bdb1d9b61)

Object.freeze()可以冻结一个对象，如果你有一个巨大的数组或Object，并且确信数据不会修改，使用Object.freeze()可以让性能大幅提升。
