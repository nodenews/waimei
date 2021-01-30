---
layout: post
title: "Windows 0day 漏洞能损坏硬盘"
date: 2021-01-15T12:08:20.000Z
author: Solidot
from: https://www.solidot.org/story?sid=66670
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1610712500000-->
[Windows 0day 漏洞能损坏硬盘](https://www.solidot.org/story?sid=66670)
------

<div>
一个未修复的 Windows 0day 漏洞能<a href="https://answers.microsoft.com/en-us/windows/forum/all/windows-10-bug-that-can-corrupt-hard-drives/8de351c7-6297-4006-8870-d8c7b113d6c7" target="_blank">允许</a>攻击者使用一行命令损坏 NTFS 格式化的硬盘。安全研究人员表示不清楚硬盘遭到破坏的原因。该漏洞影响 2018 年 4 月发布的 Windows 10&nbsp;build 1803，以及之后发布的 1809、1903、1909、2004 和最新的 20H2。漏洞能被低权限的用户账号触发。触发漏洞的单行命令可以被隐藏在 Windows 快捷方式文件、压缩文件、批处理文件等载体中。当漏洞被触发，用户会看到错误信息“文件或目录已损坏且不可读”，Windows 10 会立即要求用户重启以修复受损的硬盘卷，重启时 Windows 磁盘检查工具会开始检查磁盘。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
