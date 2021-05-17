---
layout: post
title: "Marvin Minsky 的通用图灵机发现 0day 漏洞"
date: 2021-05-17T05:58:40.000Z
author: Solidot
from: https://www.solidot.org/story?sid=67786
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1621231120000-->
[Marvin Minsky 的通用图灵机发现 0day 漏洞](https://www.solidot.org/story?sid=67786)
------

<div>
瑞典的一位计算机科学家在 Marvin Minsky 设计的通用图灵机（Universal Turing Machine）中<a href="https://www.theregister.com/2021/05/11/turing_machine_0day_no_patch_available/">发现</a>了一个 0day 漏洞，允许任意代码执行。这一发现应该没什么“实际意义”。瑞典皇家理工学院的 Pontus Johnson 教授在预印本网站 ArXiv 发表了他的<a href="https://arxiv.org/abs/2105.02124">研究报告</a>，解释了漏洞。通用图灵机被认为是计算机的最简单最抽象模型。Minsky 的 1968 年通用图灵机实现被发现缺乏输入验证，能被利用执行任意代码。该漏洞被分配了编号 <a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32471" target="_blank">CVE-2021-32471</a>，目前没有补丁也没有方法阻止漏洞利用。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
