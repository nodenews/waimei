---
layout: post
title: "Greg Kroah-Hartman 发布两个实验性稳定内核"
date: 2021-02-06T14:44:09.000Z
author: Solidot
from: https://www.solidot.org/story?sid=66879
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1612622649000-->
[Greg Kroah-Hartman 发布两个实验性稳定内核](https://www.solidot.org/story?sid=66879)
------

<div>
内核开发者在设计版本号时从未考虑过一个内核版本的小版本号更新会超过 255，因此当版本号大于 256 时可能会出现溢出。稳定版内核维护者 Greg Kroah-Hartman <a href="https://lwn.net/Articles/845207/">释出了</a>两个“实验性”稳定内核：4.9.256 和 4.4.256。它们只包含一个补丁变化，就是版本号，发布这两个版本就是为了观察小版本号数字溢出是否会导致任何用户空间问题。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
