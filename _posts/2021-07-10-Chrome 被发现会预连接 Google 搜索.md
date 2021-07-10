---
layout: post
title: "Chrome 被发现会预连接 Google 搜索"
date: 2021-07-10T05:54:25.000Z
author: Solidot
from: https://www.solidot.org/story?sid=68248
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1625896465000-->
[Chrome 被发现会预连接 Google 搜索](https://www.solidot.org/story?sid=68248)
------

<div>
Chrome 是基于开源的 Chromium 项目，该项目由 Google 等公司合作开发，但主要由 Google 控制和管理。对 Chromium 源代码的分析<a href="https://www.ctrl.blog/entry/chrome-google-dse-preconnect.html" target="_blank">发现了</a> PreconnectToSearch 功能，当该功能启用之后浏览器会预先打开和维护一个默认搜索引擎的连接。预连接会预先解析域名、与服务器协商和建立安全连接。所有这些都需要时间，预连接意味着可以节省时间更快的返回用户的查询结果。在比较慢的网络中，预连接能节省十几秒；在比较快的网络中能节省半秒。如果用户不执行搜索，预连接也可能会略微影响页面加载速度。但有一个问题是，Chromium 会检查默认搜索引擎设置，只在默认设置为 Google 时启用该功能。这使得其它搜索引擎在 Chrome 浏览器的搜索速度上相比 Google <a href="https://tech.slashdot.org/story/21/07/09/2056209/googles-unfair-performance-advantage-in-chrome">处于竞争劣势</a>。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
