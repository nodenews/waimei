---
layout: post
title: "HardenedVault白皮书：赛博堡垒锻造之路"
date: 2021-09-03T15:32:32.000Z
author: Solidot
from: https://www.solidot.org/story?sid=68809
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1630683152000-->
[HardenedVault白皮书：赛博堡垒锻造之路](https://www.solidot.org/story?sid=68809)
------

<div>
<a href="http://https://hardenedvault.net/">HardenedVault</a> 写道<i> "<a href="https://hardenedvault.net/" target="_blank">HardenedVault</a>近期发布了白皮书《<a href="https://zhuanlan.zhihu.com/p/406518045" target="_blank">赛博堡垒锻造之路</a>》，在当前的业务环境中，云和物联网网关无处不在，他们的共同点都是拥有完整的硬件和固件体系并且运行着Linux操作系统。2015<span lang="zh-CN">年时，</span>PaX/GRsecurity<span lang="zh-CN">作者接受华盛顿邮报采访并揭露了</span>Linux<span lang="zh-CN">内核安全问题后由</span>Google, RedHat, ARM, Intel组成的<span lang="zh-CN">豪华阵容发起了</span><a href="https://www.solidot.org/story?sid=48323" target="_blank">Linux<span lang="zh-CN">内核自防护计划</span></a>，可惜在6年后的今天此项目已经名存实亡，行业用户的生产环境依然每天都要面对来自Linux内核极大的安全挑战，即使如此，跟内核以下层面的威胁相比内核安全还不算是最核心的问题，Ring -1的虚拟化和Ring -2的UEFI/SMM的情况依旧不乐观，针对Ring -2的漏洞利用和持久化可让任何用户空间和内核层的检测手段失效，从防御的角度出发，芯片安全特性的开箱过程高度依赖于Ring -2和被称为<a href="https://hardenedvault.net/2021/07/16/ciso-seceng_csme.html" target="_blank">”来自Ring -3世界的恶魔“的CSM</a>E，非x86体系虽然会简单一点，但只是简单那么一点点而已。这种多元化生态所带来的是复杂性的提升，在错综复杂的关系中如果我们不能跳出当前的层面探究这些工程问题的本质，这场猫鼠游戏的结局必然是消耗了巨大的人力和财力并且最终难以达到行业对安全的预期，HardenedVault尝试借助计算机科学的力量去解决当前行业面临的安全问题，通过重新梳理从芯片，固件，操作系统到密码学中所涉及安全攻防对抗的部分形成更为有效的纵深防御体系，希望这些业界长期无法解决的尴尬问题可以通过量身打造赛博堡垒得到缓解。"</i>
</div>
