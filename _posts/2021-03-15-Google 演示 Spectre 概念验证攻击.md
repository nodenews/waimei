---
layout: post
title: "Google 演示 Spectre 概念验证攻击"
date: 2021-03-15T14:18:27.000Z
author: Solidot
from: https://www.solidot.org/story?sid=67210
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1615817907000-->
[Google 演示 Spectre 概念验证攻击](https://www.solidot.org/story?sid=67210)
------

<div>
Google <a href="https://security.googleblog.com/2021/03/a-spectre-proof-of-concept-for-spectre.html">演示了</a>实用的 Spectre 概念验证攻击，<a href="https://github.com/google/security-research-pocs/tree/master/spectre.js">代码</a>发布在 GitHub 上，演示发布在网站 <a href="https://leaky.page/">leaky.page</a> 上。2018 年 1 月，Google Project Zero 和奥地利格拉茨技术大学的研究人员披露了与预测执行相关的处理器漏洞 Spectre，利用基于时间的旁路攻击，允许恶意进程获得其他程序在内存中的数据。Google 的概念验证攻击针对的是运行在 Linux 系统上的 Chrome 88 的 V8 JS 引擎，使用的 CPU 是英特尔的 Core i7-6500U Skylake。Google 表示，可以进行微调让攻击能工作在不同的 CPU、浏览器版本和操作系统上，包括苹果的 M1 ARM CPU。概念验证攻击能以 1kB/s 的速度泄露数据。Google 称，虽然浏览器开发商已经实现了网站隔离等缓解措施，但这并不能阻止 Spectre 的漏洞利用，只是防止保存在内存中的敏感数据被攻击者读取。预防 Spectre 攻击还需要 Web 开发者<a href="https://blog.chromium.org/2021/03/mitigating-side-channel-attacks.html">部署</a>应用程序级别的缓解措施。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
