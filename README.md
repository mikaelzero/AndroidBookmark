# AndroidBookmark

## 目录

[面试题](#面试题)
 <br/>[View绘制](#View绘制)
 <br/>[Handler](#Handler)
 <br/>[事件分发](#事件分发) 
 <br/>[Binder](#Binder)
 <br/>[Framework解析](#Framework解析) 
 <br/>[JNI系列](#JNI系列) 
 <br/>[Gradle系列](#Gradle系列)
 <br/>[源码解析](#源码解析) 
 <br/>[IM](#IM)
 <br/>[代码审查](#代码审查) 
 <br/>[PDF书籍分享](#PDF书籍分享)

## 面试题

- [Android校招面试指南](https://lrh1993.gitbooks.io/android_interview_guide/)
- [Java学习+面试指南](https://github.com/Snailclimb/JavaGuide)
- [一线互联网公司内部题库](http://www.jackywang.tech/AndroidInterview-Q-A/)
- [Java / Android 笔试、面试 知识整理](https://github.com/hadyang/interview)
- [Awesome-Android-Interview](https://github.com/JsonChao/Awesome-Android-Interview)
- [Android 相关的面试题及常见套路](https://github.com/android-exchange/Android-Interview)

## View绘制

- [图解View测量、布局及绘制原理](https://www.jianshu.com/p/3d2c49315d68)
- [屏幕上内容究竟是怎样画出来的 —— Android View 工作原理详解](https://juejin.im/post/5c67c1e16fb9a04a05403549)


## Handler

- [Android 高级面试-1：Handler 相关](https://juejin.im/post/5c6a9a106fb9a04a0c2f0093#comment)
- [Handler-系列问题](https://www.yuque.com/elune/srueda/oqnhqy)
- [Android消息机制1-Handler(Java层)](http://gityuan.com/2015/12/26/handler-message-framework/)
- [Android消息机制2-Handler(Native层)](http://gityuan.com/2015/12/27/handler-message-native/)

## 事件分发

- [Android ViewGroup事件分发机制](https://blog.csdn.net/lmj623565791/article/details/39102591)
- [Android事件分发机制](https://www.jianshu.com/p/fc0590afb1bf)

## Binder

- [Binder设计与实现 - 设计篇](https://blog.csdn.net/universus/article/details/6211589)
- [Binder从C到JAVA层](https://www.yuque.com/elune/blog/eetsuc)
- [Binder系列—开篇](http://gityuan.com/2015/10/31/binder-prepare/)

## Framework解析

### 进程启动流程

- [init进程启动过程](https://www.yuque.com/elune/blog/gmgxq1)
- [zygote启动流程](https://www.yuque.com/elune/blog/bl135i) ,
- [Android系统启动-zygote篇](http://gityuan.com/2016/02/13/android-zygote/)
- [SystemServer启动流程](https://www.yuque.com/elune/blog/vexh0z) , [Android系统启动-SystemServer上篇](http://gityuan.com/2016/02/14/android-system-server/) , [Android系统启动-SystemServer下篇](http://gityuan.com/2016/02/20/android-system-server-2/)
- [理解Android进程创建流程](http://gityuan.com/2016/03/26/app-process-create/) , [Android应用进程启动流程](https://www.yuque.com/elune/blog/gs02pr)
- [AMS启动流程](https://www.yuque.com/elune/blog/qu8hg3)
- [Android系统启动概述](https://www.yuque.com/elune/blog/gi9lz9)
- [Launcher启动流程](https://www.yuque.com/elune/blog/ksykh3)
- [Launcher启动-AMS过程](https://www.yuque.com/elune/blog/bq1hmr)
- [Android应用进程启动流程](https://www.yuque.com/elune/blog/gs02pr)
- [ActivityThread.main循环过程](https://www.yuque.com/elune/blog/ruy4sa)

### 四大组件,AMS,WMS,PMS...

- [子Activity组件的startActivity逻辑](https://www.yuque.com/elune/blog/pyd45d)
- [Activity的暂停过程](https://www.yuque.com/elune/blog/tupip3)
- [Android深入四大组件（六）Android8.0 根Activity启动过程（前篇）](http://liuwangshu.cn/framework/component/6-activity-start-1.html)
- [Android深入四大组件（二）Service的启动过程](http://liuwangshu.cn/framework/component/2-service-start.html)
- [AMS相关重要概念](https://www.yuque.com/elune/blog/gdkuy1)
- [ActivityThread.main循环过程](https://www.yuque.com/elune/blog/ruy4sa)
- [Launcher启动-AMS过程](https://www.yuque.com/elune/blog/bq1hmr)
- [WindowManagerService全面解析](http://liuwangshu.cn/tags/WindowManagerService/)
- [创建窗口的过程](https://www.yuque.com/elune/blog/iw84e3)
- [Android解析WindowManagerService（一）WMS的诞生](http://liuwangshu.cn/framework/wms/1-wms-produce.html)

## JNI系列

- [Android JNI原理分析](http://gityuan.com/2016/05/28/android-jni/)
- [Android深入理解JNI](http://liuwangshu.cn/tags/Android%E6%B7%B1%E5%85%A5%E7%90%86%E8%A7%A3JNI/)

## Gradle系列

- [Gradle核心思想](http://liuwangshu.cn/tags/Gradle%E6%A0%B8%E5%BF%83%E6%80%9D%E6%83%B3/)
- [Gradle从入门到实战 - Groovy基础](https://blog.csdn.net/singwhatiwanna/article/details/76084580)
- [全面理解Gradle - 执行时序](https://blog.csdn.net/singwhatiwanna/article/details/78797506)
- [全面理解Gradle - 定义Task](https://blog.csdn.net/singwhatiwanna/article/details/78898113)
- [拥抱 Android Studio 之五：Gradle 插件开发](http://blog.bugtags.com/2016/03/28/embrace-android-studio-gradle-plugin/)
- [Gradle插件开发指南](https://www.jianshu.com/p/3191c3955194)

## 源码解析

### Retrofit

- [OKHttp源码解析](https://www.jianshu.com/p/27c1554b7fee)
- [Retrofit是如何工作的？](https://www.jianshu.com/p/cb3a7413b448)

### Glide

- [Android图片加载框架最全解析（一），Glide的基本用法](https://blog.csdn.net/guolin_blog/article/details/53759439)
- [Android图片加载框架最全解析（二），从源码的角度理解Glide的执行流程](https://blog.csdn.net/guolin_blog/article/details/53939176)
- [Android图片加载框架最全解析（三），深入探究Glide的缓存机制](https://blog.csdn.net/guolin_blog/article/details/54895665)
- [Android图片加载框架最全解析（四），玩转Glide的回调与监听](https://blog.csdn.net/guolin_blog/article/details/70215985)
- [Android图片加载框架最全解析（五），Glide强大的图片变换功能](https://blog.csdn.net/guolin_blog/article/details/71524668#t4)

### EventBus

- [EventBus 原理解析](https://juejin.im/post/5ae2e6dcf265da0b9d77f28e#heading-5)

### 组件化

- [Android 组件化最佳实践](https://juejin.im/post/5b5f17976fb9a04fa775658d)

### 插件化


## IM

- [Android网络编程之--Socket编程](https://www.jianshu.com/p/fb4dfab4eec1)
- [微信Mars策略分析](https://blog.dreamtobe.cn/mars/)
- [微信心跳机制](https://blog.dreamtobe.cn/2016/08/16/android_weak_network/)
- [Android微信智能心跳方案](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=207243549&idx=1&sn=4ebe4beb8123f1b5ab58810ac8bc5994)


## 代码审查

- [总结 Android 开发中必备的代码 Review 清单](https://mp.weixin.qq.com/s/0U733-oOv6HTW-tmhWi4Vw?)


## PDF书籍分享

- [Android内核剖析.pdf](https://share.weiyun.com/54xheD8)
- [Android系统源代码情景分析.pdf](https://share.weiyun.com/53ARvHQ)
- [Thinking In Java第四版.pdf](https://share.weiyun.com/5KNZBM5)
- [Java数据结构和算法.pdf](https://share.weiyun.com/5evhLug)
- [Java编程思想第三版.pdf](https://share.weiyun.com/5sKIiac)
- [代码整洁之道.pdf](https://share.weiyun.com/5bwF4ts)
- [图解HTTP 完整版.pdf](https://share.weiyun.com/5oGMrtr)
- [重构-改善既有代码的设计.pdf](https://share.weiyun.com/5CILfIJ)
- [算法第四版.pdf](https://share.weiyun.com/5ZJkK2E)
- [程序是怎样跑起来的.pdf](https://share.weiyun.com/5G80Xke)
- [C Primer Plus 第六版 [带书签].pdf](https://share.weiyun.com/5K1gdv1)
