
# WecTeam 前端周刊：第 002 期


## 前言

[WecTeam 前端周刊](https://github.com/wecteam/weekly)是由京东社交电商部维C团维护的技术周刊，每周从前端同学阅读的技术文章中精选而来，每周五出刊。第 002 期发布时间：2019-09-06。

更多「原创」前端技术文章，欢迎关注微信公众号「WecTeam」。

## 内容

#### 1、[【原创】Javascript抽象语法树上篇(基础篇)](https://mp.weixin.qq.com/s/Ri7DJVJa2ELFfxIRifs3tQ)

日常工作中，我们会碰到js代码解析的场景，比如分析代码中 require 了哪些包，有些什么关键API调用，大部分情况使用正则表达式来处理，可一旦场景复杂，或者依赖于代码上下文时，正则就很难处理了，这时候就要用到抽象语法树。常见的 uglify、eslint、babel、webpack 等等都是基于抽象语法树来处理的，如此强大，有必要好好了解一下。

#### 2、[【原创】Javascript抽象语法树下篇(实践篇)](https://mp.weixin.qq.com/s/Fz9H5dscj5Oy__daecAYvg)

本篇介绍AST的运用。AST应用的三个要点：

（1）需要一个解析器，将代码转换为AST。

（2）需要一个遍历器，能够遍历AST,并能够方便的对AST节点进行增删改查等操作。

（3）需要一个代码生成器，能够将AST转换为代码。

#### 3、[京东PC 首页2019 改版前端总结](https://aotu.io/notes/2019/08/26/jdindex_2019/index.html)

京东 PC 首页距离上次改版，已有2年3个月零五天。这次改版在延续17版的框架与流程的基础之上，为首页的稳定性、安全性、视觉体验、无障碍体验方面见缝插针地添了砖加了瓦。

#### 4、[伊斯坦布尔测试覆盖率的实现原理](http://www.alloyteam.com/2019/07/13481/)

单元测试无疑是一种衡量代码质量的重要手段，而测试覆盖率则是衡量测试完整性的一种手段，Istanbul 是一个基于 JavaScript 的测试覆盖率统计工具，目前被绝大多数测试框架使用。本文简单介绍其实现原理。

#### 5、[利用peerjs轻松玩转webrtc](https://www.cnblogs.com/yjmyzz/p/peerjs-tutorial.html)

非常值得一看的技术落地文章，框架上手简单明了，但如何将合适技术落地到业务中，创新更多玩法，是个值得思考的问题。

#### 6、[再看2019大前端技术趋势，Web OS概念正落地](https://developer.aliyun.com/article/711504)

前端三大框架已趋于平稳、标准化，向 Web Components 看齐；强运营背景下，移动端以前端开发为主，已成定局；5G 时代快来了，互联网的长期在线情况有可能会被打破。

#### 7、[利用"交叉观察者"这个小宝贝儿，轻松实现懒加载、吸顶、触底](https://juejin.im/post/5d665133e51d4561c83e7c83)

判断可视性的方法，基本就是监听 scroll 事件，或者是计时器循环判断来做这个判断，但是由于其高频的计算频率，会导致浏览器性能的损失，尤其是，如果一个同一个页面中，有多个地方，需要这样的判断，那么就需要绑定多个scroll事件，或者有多个计时器在轮询的话，那么对性能的损失就更为客观了;IntersectionObserver 虽然当前受限于浏览器的支持性，该方法还不能用于生产环境中，但却不影响我们去先了解一下这个令人兴奋的API。

#### 8、[Vue 项目性能优化 — 实践指南](https://juejin.im/post/5d548b83f265da03ab42471d)

从代码、Webpack、基础 Web 技术多方面讲解Vue项目的性能优化思路。

#### 9、[Webpack优化——将你的构建效率提速翻倍](https://juejin.im/post/5d614dc96fb9a06ae3726b3e)

Webpack 已经逐渐成为了前端构建体系的一大霸主，但随着业务代码不断增加，项目深度不断延伸，我们的构建时长也会因此不断增加。本文通过一个案例，向你展示如何分析构建病根、优化构建体验。

#### 10、[探秘 Vue3.0 - Composition API 在真实业务中的尝鲜姿势](https://mp.weixin.qq.com/s/Q6A0wn39mYOSXm2--Q_IOA)

Vue3.0 将抛弃之前的 Class API 的提案，选择了 Function API。目前，vue 官方 也提供了 Vue3.0 特性的尝鲜版本，前段时间叫 `vue-function-api`，目前已经改名叫 `composition-api`。
