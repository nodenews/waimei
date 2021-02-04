---
layout: post
title: "多个 Linux 发行版考虑移除 Chromium 软件包"
date: 2021-01-20T06:22:04.000Z
author: Solidot
from: https://www.solidot.org/story?sid=66710
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1611123724000-->
[多个 Linux 发行版考虑移除 Chromium 软件包](https://www.solidot.org/story?sid=66710)
------

<div>
Google Chrome Team 团队向 Linux 发行版开发者<a href="https://groups.google.com/a/chromium.org/g/embedder-dev/c/NXm7GIKTNTE/m/Qxcew5lfCAAJ">发去邮件通知</a>，从 3 月 15 日起，在构建配置中使用 google_default_client_id 和 google_default_client_secret 的第三方 Chromium 版本，它们的终端用户将无法再登陆其 Google Accounts 账号。Google 称，他们在最近的审计中发现部分基于 Chromium 的浏览器使用了原本只给 Google 使用的 Google API 和服务，其中最主要的是同步账号的 Chrome Sync API，它决定移除这些 API 的访问，声称这是为了改进用户数据安全。Linux 发行版开发者表示过去十年他们一直这么做的，如果无法使用 Google 的同步功能，那么继续维护 Chromium 软件包也没有什么价值了。Chrome 的工程总监 Jochen Eisinger 在回复中表示他们的决定不会改变。Slackware Linux 和 Arch Linux 都表示<a href="https://lists.archlinux.org/pipermail/arch-dev-public/2021-January/030263.html">考虑</a>从仓库移除 Chromium。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
