---
layout: post
title: "Cloudflare 的 cdnjs 库发现远程代码执行漏洞 "
date: 2021-07-16T07:48:38.000Z
author: Solidot
from: https://www.solidot.org/story?sid=68303
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1626421718000-->
[Cloudflare 的 cdnjs 库发现远程代码执行漏洞](https://www.solidot.org/story?sid=68303)
------

<div>
CDN 服务商 Cloudflare 的 JavaScript/CSS  库 cdnjs <a href="https://blog.ryotak.me/post/cdnjs-remote-code-execution-en/" target="_blank">发现了一个远程代码执行漏洞</a>。cdnjs 是最广泛使用的 JS 库之一，利用 cdnjs 的漏洞发动供应链攻击将会影响无数的网站。W3Techs 的统计显示，截至 7 月 15 日，cdnjs 被  12.7% 的网站使用，仅次于 Google 的 Hosted 库，Hosted 的使用率为 12.8%，而根据 cdnjs 的增长趋势它很快将会成为最广泛使用的 JS 库。研究人员在 4 月 6 日发现了漏洞，Cloudflare 在当天就做出了回应，完整补丁则在 6 月 3 日部署。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
