---
layout: post
title: "Firefox 87 将默认移除 HTTP 反向链接"
date: 2021-03-23T04:55:24.000Z
author: Solidot
from: https://www.solidot.org/story?sid=67283
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1616475324000-->
[Firefox 87 将默认移除 HTTP 反向链接](https://www.solidot.org/story?sid=67283)
------

<div>
Mozilla <a href="https://blog.mozilla.org/security/2021/03/22/firefox-87-trims-http-referrers-by-default-to-protect-user-privacy/">宣布</a>，为了保护用户隐私，即将发布的 Firefox 87 将默认从反向链接头文件中移除路径和字符串信息，以防止用户敏感信息泄露。反向链接提供了用户跳到另一个网站的源地址，网站利用反向链接可以收集用户信息和进行分析优化。但问题是 HTTP 反向链接头文件通常会包含用户的隐私信息，透露了用户正在阅读的哪一篇指向网站的文章，甚至有时候会包含用户账号信息。从 Firefox 87 起，Mozilla 将在反向链接中保留域名，移除特定文章的路径和其它可能包含用户隐私信息的字符串。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
