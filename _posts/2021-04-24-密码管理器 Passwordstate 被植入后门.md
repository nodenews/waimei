---
layout: post
title: "密码管理器 Passwordstate 被植入后门"
date: 2021-04-24T05:36:50.000Z
author: Solidot
from: https://www.solidot.org/story?sid=67592
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1619242610000-->
[密码管理器 Passwordstate 被植入后门](https://www.solidot.org/story?sid=67592)
------

<div>
密码管理器 Passwordstate 的开发商 Click Studios <a href="https://arstechnica.com/gadgets/2021/04/hackers-backdoor-corporate-password-manager-and-steal-customer-data/" target="_blank">通知客户</a>，恶意攻击者入侵了它的升级机制，在客户电脑上安装了一个恶意文件。名为 moserware.secretsplitter.dll 的恶意文件包含了 <a href="https://github.com/moserware/SecretSplitter" target="_blank">SecretSplitter</a> 的一份拷贝和恶意代码 Loader。恶意代码会尝试将 Passwordstate 数据发送到攻击者控制的服务器上。入侵发生在 4 月 20 日 8:33 am UTC 到 4 月 22 日 12:30 am 之间，攻击者的服务器在 4 月 22 日 7:00 am UTC 关闭。这次入侵的严重性在于 Passwordstate 是主要出售给企业级客户，用于管理防火墙、VPN 和其它企业应用的密码，有多达 2.9 万客户受到影响。这是最新一起的供应链攻击案件。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
