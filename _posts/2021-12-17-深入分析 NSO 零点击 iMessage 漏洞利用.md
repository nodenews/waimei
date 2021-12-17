---
layout: post
title: "深入分析 NSO 零点击 iMessage 漏洞利用"
date: 2021-12-17T06:49:34.000Z
author: Solidot
from: https://www.solidot.org/story?sid=70037
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1639723774000-->
[深入分析 NSO 零点击 iMessage 漏洞利用](https://www.solidot.org/story?sid=70037)
------

<div>
Google Project Zero 安全研究人员<a href="https://googleprojectzero.blogspot.com/2021/12/a-deep-dive-into-nso-zero-click.html">公布了</a> NSO 间谍软件 Pegasus 零点击 iMessage 漏洞利用的深入分析报告，认为这是他们见过的技术最先进的漏洞利用之一。漏洞 CVE-2021-30860 被利用攻击沙特的活动人士，利用漏洞不需要用户点击链接或浏览恶意网站，苹果在 9 月的更新中修复了该漏洞。安全研究人员称，Pegasus 的第一个切入点是 iMessage，攻击者只需要 AppleID 用户名的电话号码就能启动恶意程序植入。iMessage 原生支持 GIF 图像，使用 ImageIO 库去猜测源文件的正确格式然后解析。利用伪装成 gif 图像的欺骗方法数十种图像编解码器就成为零点击 iMessage 攻击面的一部分。Pegasus 针对的是其中的 CoreGraphics PDF 解析器，在该解析器中苹果使用了来自 <a href="https://www.xpdfreader.com/download.html">Xpdf </a>的开源 JBIG2 实现，JBIG2 是压缩黑白像素的图像编解码器。JBIG2 存在一个典型的整数溢出漏洞。虽然 JBIG2 没有脚本能力，但它能模拟任意逻辑门操作的电路，Pegasus 将 pdf 伪装成 gif，利用该漏洞溢出内存之后，使用超过 7 万个 segment 命令定义逻辑位操作，创造了一个定制的虚拟机在内存中执行指令。
</div>
