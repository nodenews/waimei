---
layout: post
title: "Chrome 和 Firefox 的版本号即将突破三位数"
date: 2022-02-17T14:35:41.000Z
author: Solidot
from: https://www.solidot.org/story?sid=70695
tags: [ Solidot ]
comments: True
categories: [ Solidot ]
---
<!--1645108541000-->
[Chrome 和 Firefox 的版本号即将突破三位数](https://www.solidot.org/story?sid=70695)
------

<div>
Chrome 和 Firefox 将在几个月内版本号超过 100。对于依赖浏览器版本号执行业务逻辑的网站来说，<a href="https://hacks.mozilla.org/2022/02/version-100-in-chrome-and-firefox/">这有可能会导致问题</a>。为什么版本号从两位数增加到三位数会出现问题？当浏览器版本号 12 年前从一位数增加到两位数时，User-Agent 解析库发现了很多问题。部分解析库可能含有硬编码的假设或 bug，没有考虑版本号突破三位数的情况。在版本号突破两位数后，很多解析库改进了解析逻辑，因而突破三位数造成的问题估计会更少。Firefox 计划在 3 月 8 日发布 Firefox 100 的首个 Nightly 版本，5 月 3 日发布正式版本。而 Chrome 将在 3 月 29 日发布 v100 版本。
</div>
