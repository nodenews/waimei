---
layout: post
title: "Linux Glibc 安全修正创造了新的更严重的 bug"
date: 2021-08-17T12:00:01.000Z
author: Solidot
from: https://www.solidot.org/story?sid=68575
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1629201601000-->
[Linux Glibc 安全修正创造了新的更严重的 bug](https://www.solidot.org/story?sid=68575)
------

<div>
广泛使用的 GNU C Library (glibc)在六月份释出了一个安全修正，但这个补丁却<a href="https://www.zdnet.com/article/linux-glibc-security-fix-created-a-nastier-linux-bug/">创造了</a>新的更严重的 <a href="https://access.redhat.com/security/cve/cve-2021-38604" target="_blank">bug</a>。glibc 原先的漏洞其实是很难利用的，需要许多先决条件才有可能利用 bug 崩溃程序。但打上补丁之后的 glibc 却被发现创造了一个更容易被利用的 bug。CloudLinux TuxCare Team 的研究员 Nikita Popov 在检查补丁时发现了问题，新的 bug 容易诱发段错误（segmentation fault），导致使用 glibc 的程序崩溃，产生一个拒绝服务问题。新 bug 比旧 bug 更容易诱发。修正第二个 bug 的补丁已经释出并整合到 glibc 库中。使用者最好尽快升级到最新的稳定版本 glibc 2.34。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
