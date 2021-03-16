---
layout: post
title: "将 GTA Online 的加载时间减少七成"
date: 2021-03-01T05:22:56.000Z
author: Solidot
from: https://www.solidot.org/story?sid=67058
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1614576176000-->
[将 GTA Online 的加载时间减少七成](https://www.solidot.org/story?sid=67058)
------

<div>
Rockstar 在 2013 年发售的《<a href="https://en.wikipedia.org/wiki/Grand_Theft_Auto_V#Sales">侠盗猎车手 V</a>》是史上最畅销的游戏之一，截至 2021 年 2 月它售出了超过 1.4 亿份拷贝。让《侠盗猎车手 V》畅销不衰的原因除了游戏本身出色的主线故事外，更为重要的原因是它的在线模式《GTA Online》，至今仍然在更新的《GTA Online》带来的收入比游戏本身更高，以至于 Rockstar 准备在今年推出独立版本。但许多玩家发现进入游戏界面之后，加载故事模式只要几秒钟，而加载《GTA Online》则需要几分钟。Rockstar 的开发者至今一直没有解决或重视该问题，但这极其影响游戏体验。有开发者<a href="https://nee.lv/2021/02/28/How-I-cut-GTA-Online-loading-times-by-70/">对此展开了分析</a>，发现在长达数分钟的加载时间内 CPU 单个核心的负荷几乎跑满，而网络、磁盘和 GPU 的使用率基本上都为零。那么是什么原因导致 CPU 成为瓶颈。进一步分析发现，原因是游戏需要解析一个 10MB 大小的 JSON 文件，而解析器本身有很大的问题。这位开发者对其进行了一番优化，成功将加载时间缩短了 69.4%。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
