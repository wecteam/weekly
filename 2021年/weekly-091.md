## 前言

WecTeam 前端周刊（<https://github.com/wecteam/weekly>）是由 WecTeam 维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 091 期发布时间：2021-07-30。

WecTeam（维C团）是京东旗下京喜事业群的前端技术团队，主要专注于前端工程化、Web 性能优化、小程序开发、Severless、多端复用、可视化搭建等前沿技术研究。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。

## 周刊文章

### 1、[京东mPaaS移动日志建设与应用](https://mp.weixin.qq.com/s/CGM1tALyn_TeaFa3iEeeWQ)

移动日志系统使用了 Linux 系统中提供的 mmap 作为日志文件的载体。目前业内流行的 XLOG 日志组件、MMKV、美团 Logan 均采用了此方案，其最大的优势就是高效 I/O、低损耗、跨进程等优势。

### 2、[iOS 底层原理：界面优化](https://mp.weixin.qq.com/s/Jy3QCqC_9XPUGKJ-4A2QzQ)

界面优化主要是解决卡顿问题。优化界面流畅度，提升用户体验度。本文从原理讲解，对监控卡顿、优化等方案都做了详细讲解。其中优化主要是讲如何对 CPU 和 GPU 减负，使用了预排版、预解码、预渲染、按需加载、异步渲染等技术方案。
