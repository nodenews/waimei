---
layout: post
title: "Google 修复阻止 Android 用户拨打紧急求助电话 911 的 bug"
date: 2022-01-06T03:06:02.000Z
author: Solidot
from: https://www.solidot.org/story?sid=70259
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1641438362000-->
[Google 修复阻止 Android 用户拨打紧急求助电话 911 的 bug](https://www.solidot.org/story?sid=70259)
------

<div>
上个月，一位 Google Pixel 3 用户在祖母疑似中风时尝试拨打紧急救助电话 911 结果在铃声响了一下之后就卡死了。幸好家里还有固话，因此最后没有发生更糟糕的情况。问题被发现是安装之后没有登录的微软协作工具 Teams 应用导致的。开发者对 Android 源代码的分析<a href="https://www.solidot.org/story?sid=69970" target="_blank">揭示了背后真正的原因</a>：处理紧急呼叫的 adjustAttemptsforEmergency 方法在排序重复 PhoneAccount 实例时存在一个整数溢出/下溢错误 bug。Google 现在<a href="https://android-review.googlesource.com/c/platform/packages/services/Telecomm/+/1903050">修复</a>了该 bug，<a href="https://arstechnica.com/gadgets/2022/01/google-fixes-nightmare-android-bug-that-stopped-user-from-calling-911/#p3">彻底解决了</a>阻止用户拨打 911 的 问题。
</div>
