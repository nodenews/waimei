---
layout: post
title: "黑客删除了 NewsBlur 的 Mongo 数据库"
date: 2021-06-24T06:07:38.000Z
author: Solidot
from: https://www.solidot.org/story?sid=68113
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1624514858000-->
[黑客删除了 NewsBlur 的 Mongo 数据库](https://www.solidot.org/story?sid=68113)
------

<div>
黑客删除了 <a href="https://newsblur.com/" target="_blank">NewsBlur</a> 网站的所有 Mongo 数据库，将下载的 250 GB 数据作为“人质”进行勒索。NewsBlur 提供 RSS 在线阅读服务，创始人在 HN 上<a href="https://news.ycombinator.com/item?id=27613217">解释说</a>，当时他正在切换 Mongo 服务器，他的 ufw 防火墙本来设置禁止外部 IP 访问内部服务器，但由于 Docker 的问题导致了 Mongo 服务器可以公开访问，一个黑客或者脚本小子在大约 3 小时后扫描到了公开的 Mongo 数据库，因此下载并删除了数据库。NewsBlur 表示会很快通过备份恢复服务。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
