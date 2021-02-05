---
layout: post
title: "Chromium 重新设计代码大幅减少 DNS 流量"
date: 2021-02-05T15:24:29.000Z
author: Solidot
from: https://www.solidot.org/story?sid=66874
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1612538669000-->
[Chromium 重新设计代码大幅减少 DNS 流量](https://www.solidot.org/story?sid=66874)
------

<div>
去年 8 月，亚太互联网络信息中心（APNIC）<a href="https://www.solidot.org/story?sid=65317">报告</a>，Chromium 浏览器中检查网络是否存在 NXDOMAIN 拦截的代码会导致大量的垃圾 DNS 查询流量。NXDOMAIN 是域名错误信息，部分 ISP 会对其进行拦截重定向。Chromium 采用的方法是每次启动、每次 IP 地址变化、每次设备 DNS 配置变更时对 3 个随机的 10 个字符长的字符串进行 DNS 查询。APNIC 称 root 服务器一半的查询流量来自于 Chromium 的检查。这相当于每天在 root 服务器系统查询 600 亿次。APNIC 现在<a href="https://blog.apnic.net/2021/02/04/how-chromium-reduces-root-dns-traffic/">报告</a>，Chromium 团队重新设计了代码停止了垃圾 DNS 查询，这一变动包含在 Chromium 87 中。在 Chromium 87 释出前，root 服务器的峰值查询流量高达每天 1430 亿次，释出后降至了每天 840 亿次，减少了 41%。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
