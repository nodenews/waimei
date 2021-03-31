---
layout: post
title: "WireGuard 将进入 FreeBSD 内核"
date: 2021-03-16T06:58:20.000Z
author: Solidot
from: https://www.solidot.org/story?sid=67219
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1615877900000-->
[WireGuard 将进入 FreeBSD 内核](https://www.solidot.org/story?sid=67219)
------

<div>
WireGuard 作者 Jason Donenfeld <a href="https://lists.zx2c4.com/pipermail/wireguard/2021-March/006494.html">宣布</a> FreeBSD 13 <a href="https://arstechnica.com/gadgets/2021/03/in-kernel-wireguard-is-on-its-way-to-freebsd-and-the-pfsense-router/">有了</a> WireGuard VPN 协议的内核实现。诸多路由器使用的是基于 BSD 的发行版，WireGuard 内核实现对它们有很大的帮助。WireGuard 内核实现的工作最早始于 2020 年 2 月，FreeBSD 开发者 Matt Macy 受  Netgate 委托开始了相关的工作，将近一年之后 Macy 的工作进入了 FreeBSD 13.0-RELEASE 的内核，但 Donenfeld 本人评估之后认为代码还没有做好准备。问题是 Netgate 已经宣布即将发布的 pfSense 2.5 将加入对 WireGuard 的支持。Donenfeld 之后与 FreeBSD 核心开发者 Kyle Evans 和 Matt Dunwoodie 合作花了一周的时间修正代码问题。鉴于目前的情况，即将发布的 FreeBSD 13.0-RELEASE 预计不会启用 WireGuard 模块，正式启用要等到下一个版本 13.1。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
