---
layout: post
title: "12 年历史的 Polkit 高危漏洞影响主要 Linux 发行版"
date: 2022-01-26T04:32:17.000Z
author: Solidot
from: https://www.solidot.org/story?sid=70508
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1643171537000-->
[12 年历史的 Polkit 高危漏洞影响主要 Linux 发行版](https://www.solidot.org/story?sid=70508)
------

<div>
安全公司 Qualys 的研究人员在类  Unix 系统权限管理工具 Polkit 中发现了一个 root 提权漏洞，允许非特权用户获得系统的 root 权限。该漏洞被命名为 <a href="https://blog.qualys.com/vulnerabilities-threat-research/2022/01/25/pwnkit-local-privilege-escalation-vulnerability-discovered-in-polkits-pkexec-cve-2021-4034" target="_blank">PwnKit</a>，已存在了 12 年之久。从 2009 年起，Polkit 包含了一个内存破坏（memory-corruption）漏洞，利用漏洞比较简单，甚至部分账号能百分之百实现。已在存有漏洞的系统获得立足点的攻击者可以滥用该漏洞确保恶意负荷或指令能以系统最高权限执行。安全研究人员是在去年 11 月发现该漏洞的，在主要 Linux 发行版修复漏洞之后将其披露。Qualys 没有公布漏洞利用概念验证代码，但发布了一则漏洞利用<a href="https://vimeo.com/669715589?embedded=true&amp;source=vimeo_logo&amp;owner=42884007">视频</a>。
</div>
