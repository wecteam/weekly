## 前言

WecTeam 前端周刊（<https://github.com/wecteam/weekly>）是由 WecTeam 维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 102 期发布时间：2021-10-29。

WecTeam（维C团）是京东旗下京喜事业群的前端技术团队，主要专注于前端工程化、Web 性能优化、小程序开发、Severless、多端复用、可视化搭建等前沿技术研究。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。


## 周刊文章

### 1、[领域驱动设计(DDD)能给前端带来什么](https://mp.weixin.qq.com/s/fCP9Y9naiDvz6lQk3JZVlA)

拓宽视野，领域驱动设计了解一下？

### 2、[自如客APP裸眼3D效果的实现](https://juejin.cn/post/6989227733410644005?from=main_page)

通过一些创新，提升了整个界面美感。

### 3、[Flutter难点问题之GPU后台Crash](https://mp.weixin.qq.com/s/KVux8rYCPXcvDODUskinBQ)

本文介绍了后台访问 GPU 导致 App 后台被杀的修复方案。通过在主线程接收 App 退到后台的通知（退到后台即表示 GPU 不可用），并设置一个 bool 变量，在实际渲染的线程中根据 bool 变量，来进行分支处理：GPU 可用时照常使用 GPU 渲染；GPU 不可用时降级用 CPU 渲染。一般使用 SyncSwitch 时，语义都带GpuDisabled ，因此 SetIfTrue 中才是 CPU 渲染的降级调用。