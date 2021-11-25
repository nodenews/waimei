---
layout: post
title: "看不见的 JavaScript 后门"
date: 2021-11-10T15:14:08.000Z
author: Solidot
from: https://www.solidot.org/story?sid=69578
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1636557248000-->
[看不见的 JavaScript 后门](https://www.solidot.org/story?sid=69578)
------

<div>
本月初，剑桥大学的研究人员<a href="https://www.solidot.org/story?sid=69447">披露了</a>在源代码中隐藏人眼看不见的漏洞的攻击方法 Trojan-Source，攻击利用的是 Unicode 中的双向机制。现在，安全研究人员披露了<a href="https://certitude.consulting/blog/en/invisible-backdoor/" target="_blank">在 JavaScript 中发动类似攻击的方法</a>。在 JavaScript 中创造看不见的后门首先需要寻找能被 JS 解释为标识符/变量的不可见的 Unicode 字符，然后寻找使用不可见字符不被注意到的方法。这种方法无法通过语法高亮检测出来。攻击需要 IDE/文本编辑器能正确渲染不可见的字符。Notepad++ 和 VS Code 都能正确渲染。
</div>
