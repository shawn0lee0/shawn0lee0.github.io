---
layout: post
title: 微信应用号设计思考
category: project
description: 不就是个App Streaming么~
---


## 核心价值观


+ 一切以用户价值为依归---挑战不是在于说我们再多做多少事情，而是我们能够挡掉多少事情。

 - 一是没有特权的白名单；
 - 二是如果这个需求普遍，就是有很多人有很强的需求，那么系统应该有一个规则来释放这个需求，而不是通过找关系或者是白名单这样的方式来满足少数人的需求，这不在我们产品鼓励的方向中。

 - 绝不允许骚扰用户，绝不允许把用户不需要的东西推给用户。
 - 善良比聪明更重要


+  让创造发挥价值———“释放创造力”
 - 让真正有价值的东西发挥出它的价值。

+ 好的产品是用完就闪的
 - 怎么样更高效率帮助用户完成任务，而不是让用户在微信里面永远都有处理不完的事情

+ 让商业化存在于无形之中
 - 只有你的产品产生了价值才能带来回报


- - -
## 用户の窘境

现如今应用开发者所面临的最大问题就是需要能正确使用他们的应用用户。据调查显示，用户在使用移动设备时，80%的时间都花在应用程序上，且平均每个用户安装48个应用。在Google Play和App Store上，应用数量远超100万，而66%的用户打开应用的次数只有1至10次。这就意味着即使应用开发者能够成功地将自己所开发的产品安装到用户设备上，却也面临着被用户遗忘的风险，更糟糕的则是被用户卸载。

## 交互猜想

新版本的微信取消了首页下拉发送“小视频”功能。

个人猜想：用户通过下拉选择关注过的应用号，比如“Runmap” 打开应用，输入图片--返回输出轨迹向导，上推首页栏，回归微信主页面。整个流程极简！

## 准备工作



+ [Google app-indexing](https://developers.google.com/app-indexing/) `搜索仅存在应用程序上的内容`
+ [Google Principles of site design](https://developers.google.com/web/fundamentals/getting-started/principles/?hl=en)
 + [Source](https://github.com/google/WebFundamentals)
+ [Courses-Mobile Web Development Building Mobile Web Experiences](https://www.udacity.com/courses/cs256?_ga=1.196041580.131882666.1452615000)
+ [Amazon AppStream](https://aws.amazon.com/cn/appstream/)
 - 消除设备限制：无设备的 GPU、CPU、内存或物理存储限制
 - 支持多种平台：支持一个新设备，只需编写一个客户端，用以连接到您的应用程序。
 - 更新快速简单：可以升级所有客户的应用程序，而客户却什么都不用做。
 - 瞬间启动：不必再等待大文件下载和费时的安装过程。
 - 更完善的安全性：应用程序以二进制方式安全存储于 AWS 数据中心
+ [Getting Started with Amazon AppStream](http://docs.aws.amazon.com/appstream/latest/developerguide/appstream-get-started.html)

小结：WEBAPP的增强版！













![](http://photocdn.sohu.com/20151123/mp43745856_1448281470629_1_th.jpeg)