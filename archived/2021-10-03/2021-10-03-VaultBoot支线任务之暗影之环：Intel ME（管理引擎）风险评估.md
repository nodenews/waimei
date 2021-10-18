---
layout: post
title: "VaultBoot支线任务之暗影之环：Intel ME（管理引擎）风险评估"
date: 2021-10-03T12:37:36.000Z
author: Solidot
from: https://www.solidot.org/story?sid=69131
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1633264656000-->
[VaultBoot支线任务之暗影之环：Intel ME（管理引擎）风险评估](https://www.solidot.org/story?sid=69131)
------

<div>
<a href="http://https://hardenedvault.net/">HardenedVault</a> 写道<i> "<span style="color: rgb(18, 18, 18); font-family: -apple-system, BlinkMacSystemFont, &quot;Helvetica Neue&quot;, &quot;PingFang SC&quot;, &quot;Microsoft YaHei&quot;, &quot;Source Han Sans SC&quot;, &quot;Noto Sans CJK SC&quot;, &quot;WenQuanYi Micro Hei&quot;, sans-serif; background-color: rgb(255, 255, 255);">”复杂性“的概念本身就过于复杂难以简单的解释，而安全领域的从业者则每天都在和"复杂性"打交道，有些威胁和风险相对容易理解和找出已知风险的应对之策，虽然这通常会很耗时，但有些风险并不是那么容易理解，要制定防护措施的难度更甚，<a href="https://zhuanlan.zhihu.com/p/416458457" target="_blank">Intel ME</a>属于这一类 。早在2008年，Intel就将ME（管理引擎）引入芯片组，它比操作系统具有更高的特权，这意味着操作系统级别的安全检测方案对ME几乎是无效的，更重要的是，绝大部分用户都不知道他们的计算机中有一个独立的“小电脑”存在（请翻阅</span><a href="https://zhuanlan.zhihu.com/p/406518045" class="internal" data-za-detail-view-id="1043" style="text-decoration-line: none; cursor: pointer; border-bottom: 1px solid rgb(128, 128, 128); font-family: -apple-system, BlinkMacSystemFont, &quot;Helvetica Neue&quot;, &quot;PingFang SC&quot;, &quot;Microsoft YaHei&quot;, &quot;Source Han Sans SC&quot;, &quot;Noto Sans CJK SC&quot;, &quot;WenQuanYi Micro Hei&quot;, sans-serif; background-color: rgb(255, 255, 255);">HardenedVault白皮书</a><span style="color: rgb(18, 18, 18); font-family: -apple-system, BlinkMacSystemFont, &quot;Helvetica Neue&quot;, &quot;PingFang SC&quot;, &quot;Microsoft YaHei&quot;, &quot;Source Han Sans SC&quot;, &quot;Noto Sans CJK SC&quot;, &quot;WenQuanYi Micro Hei&quot;, sans-serif; background-color: rgb(255, 255, 255);">中图灵完备性的章节）。安全研究方面，2009 年 Alexander Tereshkin和 Rafal Wojtczuk证明了植入Ring -3 rootkit的可能性（注：在此上下文下“Ring”的概念为，应用：Ring 3，Linux 内核：Ring 0，虚拟化：Ring -1，BIOS/UEFI/SMM：Ring -2，Intel ME： Ring -3）。赛博堡垒近日发布了一份关于<a href="https://zhuanlan.zhihu.com/p/416458457" target="_blank">Intel ME的风险评估报告</a>，其中对ME的制造模式，威胁模型，防护能力，攻击路径以及漏洞后门等方面进行了<a href="https://zhuanlan.zhihu.com/p/416458457" target="_blank">详细的描述</a>。</span>"</i>
</div>
