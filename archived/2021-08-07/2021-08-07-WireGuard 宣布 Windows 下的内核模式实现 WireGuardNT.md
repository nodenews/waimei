---
layout: post
title: "WireGuard 宣布 Windows 下的内核模式实现 WireGuardNT"
date: 2021-08-07T06:49:54.000Z
author: Solidot
from: https://www.solidot.org/story?sid=68483
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1628318994000-->
[WireGuard 宣布 Windows 下的内核模式实现 WireGuardNT](https://www.solidot.org/story?sid=68483)
------

<div>
WireGuard 项目<a href="https://lists.zx2c4.com/pipermail/wireguard/2021-August/006887.html">宣布了</a> Windows 下  VPN 协议的内核模式实现 <a href="https://www.wireguard.com/install/">WireGuardNT</a>。WireGuard 在 Windows 下的早期实现是一个用 Go 语言开发的用户空间实现 wireguard-go。它在当时需要关联一个虚拟网络设备，WireGuard 作者 Jason Donenfeld 不满意 OpenVPN 项目提供的虚拟网络接口 tap-windows，因此从头实现了他自己的 <a href="https://www.wintun.net/">Wintun</a>。Wintun 相对于 tap-windows 而言是一大改进，OpenVPN 项目之后自己也实现了对 Wintun 的支持。但 wireguard-go 仍然需要持续的在内核空间和用户空间之间上下文切换。为了移除这一性能瓶颈，虚拟网卡和加密等整个堆栈都需要移到内核。测量<a href="https://arstechnica.com/gadgets/2021/08/wireguard-goes-fully-windows-native-with-experimental-wireguardnt-driver/#p3">显示</a>，内核模式实现 WireGuardNT 比用户空间实现 wireguard-go 要快 10-25%。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
