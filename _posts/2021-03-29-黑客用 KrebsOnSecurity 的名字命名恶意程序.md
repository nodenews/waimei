---
layout: post
title: "黑客用 KrebsOnSecurity 的名字命名恶意程序"
date: 2021-03-29T07:58:56.000Z
author: Solidot
from: https://www.solidot.org/story?sid=67339
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1617004736000-->
[黑客用 KrebsOnSecurity 的名字命名恶意程序](https://www.solidot.org/story?sid=67339)
------

<div>
非盈利组织 The Shadowserver Foundation <a href="https://www.shadowserver.org/news/shadowserver-special-report-exchange-scanning-5/">发现</a>了 21,248 个 Exchange 电邮服务器被植入了一个后门，而与该后门程序通信的指令控制服务器域名叫 brian[.]krebsonsecurity[.]top。知名安全博客 KrebsOnSecurity 的作者 Brian Krebs <a href="https://krebsonsecurity.com/2021/03/no-i-did-not-hack-your-ms-exchange-server/">声明</a>他与此无关。3 月 26 日 Shadowserver 注意到在入侵的 Exchange 服务器上安装新后门的尝试，后门都是安装在同一个地方 /owa/auth/babydraco.aspx。Shadowserver 的蜜罐观测到 Babydraco 后门总是执行相同的操作：运行一个 Powershell 脚本，从 159.65.136[.]128 地址上提取文件 krebsonsecurity.exe。该文件会安装 root 证书，修改系统注册表，通知 Windows Defender 不要扫描该文件。扫描显示有 21,248 台服务器被安装了 Babydraco 后门。Brian Krebs 称，黑客还在域名中包含了他的社会安全号码。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
