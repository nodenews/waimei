---
layout: post
title: "OpenSSL/LibreSSL 发现一个可远程利用的漏洞"
date: 2022-03-16T09:42:45.000Z
author: Solidot
from: https://www.solidot.org/story?sid=70959
tags: [ Solidot ]
comments: True
categories: [ Solidot ]
---
<!--1647423765000-->
[OpenSSL/LibreSSL 发现一个可远程利用的漏洞](https://www.solidot.org/story?sid=70959)
------

<div>
广泛使用的加密库 OpenSSL 发现了一个可远程利用的<a href="https://www.openssl.org/news/secadv/20220315.txt">高危漏洞</a>。计算模平方根的 BN_mod_sqrt() 包含 bug 会导致无限循环，它能用于发动拒绝服务攻击。OpenSSL 项目释出了 OpenSSL 3.0.2 和 1.1.1n 修复了漏洞。该漏洞是由 Google 安全研究员 Tavis Ormandy 在 2 月 24 日报告的，Googl 的 David Benjamin 和  OpenSSL 项目的 Tomáš Mráz开发了补丁。
</div>
