# AndroidBookmark

![](https://github.com/moyokoo/Media/blob/master/learning.png?raw=true)

> 大部分博客笔者在学习过程中收藏于书签中,最近发现书签的内容越来越多,因此编写此文档作为记录,部分是笔者自己的文章,如果写的不好还请指正.

😄**如果你有好的文章想要分享,并且符合目录的某个模块,可以提[issues](https://github.com/moyokoo/AndroidBookmark/issues)**😄

## 目录

- [面试题](#面试题)
- [JAVA](#JAVA)
- [View体系](#View体系)
- [Handler](#Handler)
- [事件分发](#事件分发)
- [Binder](#Binder)
- [Framework解析](#Framework解析)
- [Android输入系统](#Android输入系统)
- [JNI系列](#JNI系列)
- [Gradle系列](#Gradle系列)
- [源码解析](#源码解析)
  - [EventBus](#EventBus)
  - [Retrofit](#Retrofit)
  - [Glide](#Glide)
- [组件化](#组件化)
- [插件化](#插件化)
- [性能优化](#性能优化)
- [网络编程](#网络编程)
    - [知识储备](#知识储备)
    - [微信Mars通信方案](#微信Mars通信方案)
    - [IM开源项目推荐](#IM开源项目推荐)
- [代码审查](#代码审查)
- [PDF书籍分享](#PDF书籍分享)
- [工具推荐](#工具推荐)
- [养生](#养生)
- [找工作黑名单](#找工作黑名单)


## 面试题

- [Android 校招面试指南](https://lrh1993.gitbooks.io/android_interview_guide/)
- [Java 学习+面试指南](https://github.com/Snailclimb/JavaGuide)
- [一线互联网公司内部题库](http://www.jackywang.tech/AndroidInterview-Q-A/)
- [Java / Android 笔试、面试 知识整理](https://github.com/hadyang/interview)
- [Awesome-Android-Interview](https://github.com/JsonChao/Awesome-Android-Interview)
- [Android 相关的面试题及常见套路](https://github.com/android-exchange/Android-Interview)
- [一个五年Android开发者百度、阿里、聚美、映客的面试心经](http://gdky005.com/2016/07/08/%E4%B8%80%E4%B8%AA%E4%BA%94%E5%B9%B4Android%E5%BC%80%E5%8F%91%E8%80%85%E7%99%BE%E5%BA%A6%E3%80%81%E9%98%BF%E9%87%8C%E3%80%81%E8%81%9A%E7%BE%8E%E3%80%81%E6%98%A0%E5%AE%A2%E7%9A%84%E9%9D%A2%E8%AF%95%E5%BF%83%E7%BB%8F/)

## JAVA

- [java对象结构](https://blog.csdn.net/zqz_zqz/article/details/70246212)
- [Java虚拟机](http://liuwangshu.cn/tags/Java%E8%99%9A%E6%8B%9F%E6%9C%BA/)
- [JAVA多线程](http://liuwangshu.cn/tags/%E5%A4%9A%E7%BA%BF%E7%A8%8B/)
- [全面理解Java内存模型](https://blog.csdn.net/suifeng3051/article/details/52611310)
- [java 中的锁 -- 偏向锁、轻量级锁、自旋锁、重量级锁](https://blog.csdn.net/zqz_zqz/article/details/70233767/)
- [JAVA多线程之Synchronized关键字--对象锁的特点](https://www.cnblogs.com/hapjin/p/5452663.html)
- [Java并发编程：volatile关键字解析](https://www.cnblogs.com/dolphin0520/p/3920373.html)
- [java并发编程：线程安全管理类--原子操作类--AtomicBoolean](https://www.cnblogs.com/tonylovett/p/5254630.html)


## View体系

- [图解 View 测量、布局及绘制原理](https://www.jianshu.com/p/3d2c49315d68)
- [屏幕上内容究竟是怎样画出来的 —— Android View 工作原理详解](https://juejin.im/post/5c67c1e16fb9a04a05403549)

## Handler

- [Android 高级面试-1：Handler 相关](https://juejin.im/post/5c6a9a106fb9a04a0c2f0093#comment)
- [Handler-系列问题](https://www.yuque.com/elune/srueda/oqnhqy)
- [Android 消息机制 1-Handler(Java 层)](http://gityuan.com/2015/12/26/handler-message-framework/)
- [Android 消息机制 2-Handler(Native 层)](http://gityuan.com/2015/12/27/handler-message-native/)

## 事件分发

- [Android ViewGroup 事件分发机制](https://blog.csdn.net/lmj623565791/article/details/39102591)
- [Android 事件分发机制](https://www.jianshu.com/p/fc0590afb1bf)

## Binder

- [Binder 设计与实现 - 设计篇](https://blog.csdn.net/universus/article/details/6211589)
- [Binder 从 C 到 JAVA 层](https://www.yuque.com/elune/blog/eetsuc)
- [Binder 系列—开篇](http://gityuan.com/2015/10/31/binder-prepare/)

## Framework解析

关于Framework部分,非常建议在学习完毕之后去研究  [DroidPlugin](https://github.com/Qihoo360/DroidPlugin) 的实现原理,因为他hook了非常多Framework层的代码,对于掌握整个Android FrameWork层大有裨益,同时也推荐博文 [Android插件化原理解析](http://weishu.me/2016/01/28/understand-plugin-framework-overview/),在后面的插件化也会提到这篇文章

### 进程启动流程

- [init 进程启动过程](https://www.yuque.com/elune/blog/gmgxq1)
- [zygote 启动流程](https://www.yuque.com/elune/blog/bl135i) , [Android 系统启动-zygote 篇](http://gityuan.com/2016/02/13/android-zygote/)
- [SystemServer 启动流程](https://www.yuque.com/elune/blog/vexh0z) , [Android 系统启动-SystemServer 上篇](http://gityuan.com/2016/02/14/android-system-server/) , [Android 系统启动-SystemServer 下篇](http://gityuan.com/2016/02/20/android-system-server-2/)
- [理解 Android 进程创建流程](http://gityuan.com/2016/03/26/app-process-create/) , [Android 应用进程启动流程](https://www.yuque.com/elune/blog/gs02pr)
- [AMS 启动流程](https://www.yuque.com/elune/blog/qu8hg3)
- [Android 系统启动概述](https://www.yuque.com/elune/blog/gi9lz9)
- [Launcher 启动流程](https://www.yuque.com/elune/blog/ksykh3)
- [Launcher 启动-AMS 过程](https://www.yuque.com/elune/blog/bq1hmr)
- [Android 应用进程启动流程](https://www.yuque.com/elune/blog/gs02pr)

### 四大组件

- [子 Activity 组件的 startActivity 逻辑](https://www.yuque.com/elune/blog/pyd45d)
- [Activity 的暂停过程](https://www.yuque.com/elune/blog/tupip3)
- [Android 深入四大组件（六）Android8.0 根 Activity 启动过程（前篇）](http://liuwangshu.cn/framework/component/6-activity-start-1.html)
- [Android 深入四大组件（二）Service 的启动过程](http://liuwangshu.cn/framework/component/2-service-start.html)
- [ActivityThread.main 循环过程](https://www.yuque.com/elune/blog/ruy4sa)


### AMS,WMS,PMS...

- [AMS 相关重要概念](https://www.yuque.com/elune/blog/gdkuy1)
- [Launcher 启动-AMS 过程](https://www.yuque.com/elune/blog/bq1hmr)
- [WindowManagerService 全面解析](http://liuwangshu.cn/tags/WindowManagerService/)
- [创建窗口的过程](https://www.yuque.com/elune/blog/iw84e3)
- [Android 解析 WindowManagerService（一）WMS 的诞生](http://liuwangshu.cn/framework/wms/1-wms-produce.html)
- [Android包管理机制](http://liuwangshu.cn/tags/Android%E5%8C%85%E7%AE%A1%E7%90%86%E6%9C%BA%E5%88%B6/)

## Android输入系统

- [Android 输入系统](http://liuwangshu.cn/tags/Android%E8%BE%93%E5%85%A5%E7%B3%BB%E7%BB%9F/)

## JNI系列

- [Android JNI 原理分析](http://gityuan.com/2016/05/28/android-jni/)
- [Android 深入理解 JNI](http://liuwangshu.cn/tags/Android%E6%B7%B1%E5%85%A5%E7%90%86%E8%A7%A3JNI/)

## Gradle系列

- [Gradle 核心思想](http://liuwangshu.cn/tags/Gradle%E6%A0%B8%E5%BF%83%E6%80%9D%E6%83%B3/)
- [Gradle 从入门到实战 - Groovy 基础](https://blog.csdn.net/singwhatiwanna/article/details/76084580)
- [全面理解 Gradle - 执行时序](https://blog.csdn.net/singwhatiwanna/article/details/78797506)
- [全面理解 Gradle - 定义 Task](https://blog.csdn.net/singwhatiwanna/article/details/78898113)
- [拥抱 Android Studio 之五：Gradle 插件开发](http://blog.bugtags.com/2016/03/28/embrace-android-studio-gradle-plugin/)
- [Gradle 插件开发指南](https://www.jianshu.com/p/3191c3955194)

## 源码解析

### EventBus

- [EventBus 原理解析](https://juejin.im/post/5ae2e6dcf265da0b9d77f28e#heading-5)
- [EventBus 3.0进阶：源码及其设计模式 完全解析](https://www.jianshu.com/p/bda4ed3017ba)

### Retrofit

- [OKHttp 源码解析](https://www.jianshu.com/p/27c1554b7fee)
- [Retrofit 是如何工作的？](https://www.jianshu.com/p/cb3a7413b448)
- [Android网络编程（十一）源码解析Retrofit](http://liuwangshu.cn/application/network/11-retrofit2-sourcecode.html)

### Glide

- [郭霖一系列的Glide源码分析,照着看就完事了](https://blog.csdn.net/guolin_blog/article/details/53759439)



## 组件化

- [Android组件化开发实践和案例分享](https://juejin.im/post/5c46e6fb6fb9a049a5713bcc)
- [Android 组件化最佳实践](https://juejin.im/post/5b5f17976fb9a04fa775658d)
- [回归初心：极简 Android 组件化方案 — AppJoint](https://juejin.im/post/5bb9c0d55188255c7566e1e2)

## 插件化


**学习插件化预备工作:**

- [Java 反射由浅入深 | 进阶必备](https://juejin.im/post/598ea9116fb9a03c335a99a4)
- [Java Proxy 和 CGLIB 动态代理原理](http://www.importnew.com/27772.html)


**学习阶段:**

- [一系列的插件化知识点攻略(推荐)](https://github.com/tiann/understand-plugin-framework)
- [APK动态加载框架（DL）解析](https://blog.csdn.net/singwhatiwanna/article/details/39937639)
- [Android apk动态加载机制的研究](https://blog.csdn.net/singwhatiwanna/article/details/22597587)
- [Android插件化原理（一）Activity插件化](http://liuwangshu.cn/application/plug-in/1.activity.html)

### 热修复

- [Android热修复原理（一）热修复框架对比和代码修复](http://liuwangshu.cn/application/hotfix/1-code-repair.html)



## 性能优化

- [Android 性能优化必知必会](https://www.androidperformance.com/2018/05/07/Android-performance-optimization-skills-and-tools/)

### UI优化

- [Android UI卡顿监测框架BlockCanary原理分析](https://www.jianshu.com/p/e58992439793)

### 内存优化

- [Android 内存优化总结&实践](https://mp.weixin.qq.com/s/2MsEAR9pQfMr1Sfs7cPdWQ)
- [Android内存优化——常见内存泄露及优化方案](https://www.jianshu.com/p/ab4a7e353076)

### 网络优化

### 电量优化



## 网络编程

> 网络编程部分主要是根据学习IM路线进行一个总结


**首先推荐一个网站,[即时通讯网](http://www.52im.net/),网络相关知识大部分都能够找到**


### 知识储备

- [新手入门一篇就够：从零开发移动端IM(推荐)](http://www.52im.net/thread-464-1-1.html)



### 微信Mars通信方案

- [Protobuf学习](https://www.jianshu.com/p/2265f56805fa)
- [微信 Mars 策略分析](https://blog.dreamtobe.cn/mars/)
- [微信心跳机制](https://blog.dreamtobe.cn/2016/08/16/android_weak_network/)
- [Android 微信智能心跳方案](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=207243549&idx=1&sn=4ebe4beb8123f1b5ab58810ac8bc5994)
- [TCP可靠性的保证机制总结](https://blog.csdn.net/xuzhangze/article/details/80490362)


### IM开源项目推荐

- [mars](https://github.com/Tencent/mars)
- [MobileIMSDK](https://github.com/JackJiang2011/MobileIMSDK)
- [wildfirechat](https://github.com/wildfirechat)

## 代码审查

- [总结 Android 开发中必备的代码 Review 清单](https://mp.weixin.qq.com/s/0U733-oOv6HTW-tmhWi4Vw?)

## PDF书籍分享

- [Android 内核剖析.pdf](https://share.weiyun.com/54xheD8)
- [Android 系统源代码情景分析.pdf](https://share.weiyun.com/53ARvHQ)
- [Thinking In Java 第四版.pdf](https://share.weiyun.com/5KNZBM5)
- [Java 数据结构和算法.pdf](https://share.weiyun.com/5evhLug)
- [Java 编程思想第三版.pdf](https://share.weiyun.com/5sKIiac)
- [代码整洁之道.pdf](https://share.weiyun.com/5bwF4ts)
- [图解 HTTP 完整版.pdf](https://share.weiyun.com/5oGMrtr)
- [重构-改善既有代码的设计.pdf](https://share.weiyun.com/5CILfIJ)
- [算法第四版.pdf](https://share.weiyun.com/5ZJkK2E)
- [程序是怎样跑起来的.pdf](https://share.weiyun.com/5G80Xke)
- [C Primer Plus 第六版 [带书签].pdf](https://share.weiyun.com/5K1gdv1)


## 找工作黑名单

[程序员找工作黑名单，换工作和当技术合伙人需谨慎啊](https://github.com/shengxinjing/programmer-job-blacklist)


## 工具推荐

- [可视化数据结构和算法学习](https://algorithm-visualizer.org/sorting/comb-sort)
- [Tinypng-图片批量压缩](https://tinypng.com/)
- [Json格式化工具](https://jsoncompare.com/#!/simple/)
- [markdown数学公式编辑器](https://www.codecogs.com/latex/eqneditor.php)
- [APK在线反编译](http://www.decompileandroid.com/)
- [Android-OS在线源码](https://www.androidos.net.cn/)
- [Android源码查找](http://androidxref.com/7.0.0_r1/)


## 养生

- [程序员夏季养生](https://juejin.im/entry/5b356dc9f265da599c561cba)
- [日常生活中如何养护我们的肾？](https://zhuanlan.zhihu.com/p/36996845)


