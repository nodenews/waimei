---
layout: post
title: "针对 WordPress 扩展的供应链攻击"
date: 2022-01-22T12:28:16.000Z
author: Solidot
from: https://www.solidot.org/story?sid=70468
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1642854496000-->
[针对 WordPress 扩展的供应链攻击](https://www.solidot.org/story?sid=70468)
------

<div>
Jetpack 安全研究人员<a href="https://jetpack.com/2022/01/18/backdoor-found-in-themes-and-plugins-from-accesspress-themes/">发现了</a>一起利用 WordPress 扩展的供应链攻击。Jetpack 来自  WordPress 母公司 Automattic。如果网站从 <a href="https://accesspressthemes.com/about-us/">AccessPress Themes</a> 网站下载了主题扩展，那么网站有可能遭到了入侵。如果是从 WordPress.org 下载了相同的主题扩展，那么它们应该是安全的。攻击者修改的是 AccessPress Themes 网站上托管的主题扩展，悄悄植入了后门。攻击者在主题目录中加入了一个脚本 initial.php，它充当了下载程序，能从 wp-theme-connect[.]com  下载和安装后门。一旦安装后门下载程序会自毁以隐藏其活动。安全研究人员<a href="https://arstechnica.com/information-technology/2022/01/supply-chain-attack-used-legitimate-wordpress-add-ons-to-backdoor-sites/">对攻击起始时间有不同看法</a>，Jetpack 的研究人员认为供应链攻击始于去年 9 月，但另一家安全公司 Sucuri 的研究人员 Ben Martin 认为攻击可以追溯到三年前。
</div>
