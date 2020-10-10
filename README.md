![cooltext363596337964428](assets/cooltext363596337964428.png)

# X-engine 简介

x-engine 是一个跨端模块管理框架，它的定位就是是客户端的 spring，管理 bean（模块）。

![image-20200929021827767](assets/image-20200929021827767.png)

x-engine 的目的并不是做“另一个跨平台”框架，

因为这样的框架太多了，从时间上，先是 cordova，到 react-native, 到 flutter。

总结下来就这几种模式：

native + web  : cordova 

h5 -> native  : reactie-native  weex 

self-render   : flutter

native + web- : 小程序

除了 cordova 年久失修外，这些模式都有一个"特性", 绑定 UI 框架。这给某些已存在的 UI 技术栈的集成带来了一定的困难。 如果仅仅是尝尝鲜，那对他们的集成与扩展又会是一件非常麻烦的事。

x-engine 可以在一定程度上解决选择困难症的问题。 怎么快速切换，组合模块也是 x-engine 要解决的问题。



## MicroApp

x-engine 官方带了一个微应用（MicroApp）的模块， 它是一套正在开发中的基于 H5 的 Hybrid 解决方案。

支持的功能包含：

- 原生离线更新，微应用离线更新，
- 原生网络，原生 nav，等。

而这些功能的支持，也是 MicroApp 模块整合其他模块所获得的。

如果你觉得 h5 性能不好，你甚至可以切换到 react-native 模块进行开发。



所以：

x-engine 并不会试图再去造一套 “小程序” DSL，而是利用独立模块的能力集合成一个支持小程序的产品--微应用，微应用全力拥抱 H5 / SPA 标准。 这也意味着 Vue，React，Angular 任何 H5 / SPA 的开发框架都可以是我们选型对象。 

x-engine 将会全面开源，包括核心源码。在出问题时，你能跟踪到任何一端直到不属于我们的源码。 





# 工程地址

引擎: [iOS](https://github.com/zkty-team/x-engine-module-engine/tree/master/iOS) [android](https://github.com/zkty-team/x-engine-module-engine/tree/master/android)

业务模板:[hybrid-tempalte](https://github.com/zkty-team/x-engine-hybrid-template)

模块模板:[module-template](https://github.com/zkty-team/x-engine-module-template)

# 项目管理

https://zktyfe.worktile.com/tasks/projects/5f164ffa478dbd1d67107712

