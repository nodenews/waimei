---
layout: post
title: "Firefox 释出紧急更新修复两个正被利用的 0day"
date: 2022-03-06T11:51:51.000Z
author: Solidot
from: https://www.solidot.org/story?sid=70861
tags: [ Solidot ]
comments: True
categories: [ Solidot ]
---
<!--1646567511000-->
[Firefox 释出紧急更新修复两个正被利用的 0day](https://www.solidot.org/story?sid=70861)
------

<div>
Mozilla 释出紧急更新 <a href="https://www.mozilla.org/en-US/security/advisories/mfsa2022-09/">Firefox 97.0.2</a>，修复了两个正被利用的 0day 漏洞，Firefox 用户应尽可能快的升级。其中一个漏洞是 CVE-2022-26485，为 XSLT 参数处理中的释放后使用（Use-after-free）漏洞，正被攻击者用于远程代码执行；第二个漏洞是 CVE-2022-26486，为 WebGPU IPC 框架中的释放后使用漏洞，被用于沙盒逃逸。释放后使用漏洞是指一个应用程序本应释出其占用的内存供其它应用程序使用，但因为 bug 导致该应用程序仍然继续使用或占用内存。
</div>
