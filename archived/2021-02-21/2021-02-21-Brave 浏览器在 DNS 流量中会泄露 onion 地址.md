---
layout: post
title: "Brave 浏览器在 DNS 流量中会泄露 onion 地址"
date: 2021-02-21T00:29:42.000Z
author: Solidot
from: https://www.solidot.org/story?sid=66987
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1613867382000-->
[Brave 浏览器在 DNS 流量中会泄露 onion 地址](https://www.solidot.org/story?sid=66987)
------

<div>
Brave 浏览器在 2018 年加入了对 Tor 匿名网络的支持，Brave 用户无需安装 Tor 就能访问暗网 .onion 地址。一位安全研究员<a href="https://ramble.pw/f/privacy/2387/brave-browser-leaks-your-tor-onion-service-requests-through">报告</a>，Brave 浏览器的 Tor 模式会将 .onion 域名的查询发送到公共 DNS 服务器而不是 Tor 节点。这位研究员称其发现很容易复现，建议用户使用  Tor Browser 而不是 Brave 访问暗网。在这一发现引发广泛关注之后，Brave <a href="https://twitter.com/bcrypt/status/1362796915063021569">宣布</a>已释出补丁修复该问题。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
