---
layout: post
title: "英特尔新侧信道攻击：Lord of the Ring(s)"
date: 2021-03-11T10:26:52.000Z
author: Solidot
from: https://www.solidot.org/story?sid=67175
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1615458412000-->
[英特尔新侧信道攻击：Lord of the Ring(s)](https://www.solidot.org/story?sid=67175)
------

<div>
伊利诺伊香槟的三位研究人员在预印本网站 arXiv 发表<a href="https://arxiv.org/abs/2103.03443">论文</a>，披露了针对英特尔 CPU 的最新侧信道攻击，该攻击被命名为 <a href="https://github.com/FPSG-UIUC/lotr" target="_blank">Lord of the Ring(s)</a>。随着芯片上的功能模块越来越多，英特尔为其 CPU 引入了片内总线，以实现各个模块之间的高速通信，它先后引入了 Ring Bus 和 Mesh Bus。最新侧信道攻击针对的就是 Ring Bus 的环形总线。研究人员首先逆向工程了 Ring Bus 的通信协议，设法构建了一个跨核心的隐蔽信道，利用环争用的细粒度时态模式去推动应用程序的秘密。从有漏洞的 EdDSA 和 RSA 实现中提取出密钥比特。对于 AMD 的 Zen 架构使用的片内总线 Infinity Fabric，研究人员表示需要进一步的研究，但相信他们的技术能应用于其它平台。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
