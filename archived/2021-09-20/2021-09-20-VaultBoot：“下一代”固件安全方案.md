---
layout: post
title: "VaultBoot：“下一代”固件安全方案"
date: 2021-09-20T01:16:37.000Z
author: Solidot
from: https://www.solidot.org/story?sid=69001
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1632100597000-->
[VaultBoot：“下一代”固件安全方案](https://www.solidot.org/story?sid=69001)
------

<div>
<a href="http://https://hardenedvault.net/">HardenedVault</a> 写道<i> "当前固件的主流方案依然是UEFI，<span style="color: rgb(18, 18, 18);">由于技术架构设计并没有考虑其</span><a href="https://link.zhihu.com/?target=https%3A//hardwear.io/netherlands-2019/presentation/roots-of-trust-attestation-keynote-talk-hardwear-io-nl-2019.pdf" target="_blank" rel="nofollow noreferrer" data-za-detail-view-id="1043">复杂的供应链</a><span style="color: rgb(18, 18, 18);">生态，tianocore/EDK2的参考实现和OEM出厂实现差异过大，通过测试和逆向分析可以发现某些厂商的OEM固件中DXE模块有大量基于SMM的实现，这也是导致固件安全的高风险环节之一，因为SMM是x86平台下Host CPU的最高权限运行模式，俗称“Ring -2"，操作系统难以检测Ring 0以下的威胁的原因很简单：根本在不同维度上作战。而OEM固件的</span><span style="color: rgb(18, 18, 18);">设计和实现的缺陷导致了诸多</span><a href="https://link.zhihu.com/?target=https%3A//github.com/hardenedlinux/Debian-GNU-Linux-Profiles/blob/master/docs/harbian_fw/harbian_chipsec.md" target="_blank" rel="nofollow noreferrer" data-za-detail-view-id="1043">固件安全风险</a>。通常厂商的OEM固件具备<span style="color: rgb(18, 18, 18);">不可审计性，由于主流的OEM并不对用户开放源代码，所以源代码级别的审计是无法实现的，漏洞的审计只能依靠二进制审计或者模糊测试进行，而没有源代码对于发现后门或者具有后门性质的调试特性会极高的增加成本，虽然Intel在2019年尝试以</span><a href="https://link.zhihu.com/?target=https%3A//software.intel.com/content/www/us/en/develop/articles/minimum-platform-architecture-open-source-uefi-firmware-for-intel-based-platforms.html" target="_blank" rel="nofollow noreferrer" data-za-detail-view-id="1043">Minimum平台</a><span style="color: rgb(18, 18, 18);">解决开放性的问题，但目前而言其覆盖度不及预期。</span></i><p><i><span style="color: rgb(18, 18, 18);">1999年冬天，洛斯阿拉莫斯国家实验室的研究员Ron Minnich发起了一个叫</span><a href="https://link.zhihu.com/?target=https%3A//coreboot.org/images/5/5c/The_real_linuxbios.pdf" target="_blank" rel="nofollow noreferrer" data-za-detail-view-id="1043">LinuxBIOS</a><span style="color: rgb(18, 18, 18);">的项目，其目标是用自由软件去替代私有的固件，LinuxBIOS设计思路是让尽量少的代码做硬件初始化的工作，当硬件初始化完成后就加载一个基于Linux内核的执行载荷，这个项目后来更名为</span><a href="https://link.zhihu.com/?target=https%3A//www.coreboot.org/" target="_blank" rel="nofollow noreferrer" data-za-detail-view-id="1043">coreboot</a><span style="color: rgb(18, 18, 18);">，今天的coreboot支持除了Linux以外的多种执行载荷，这种架构也成为了2020年代当业界重新审视固件问题和探讨”下一代“固件时的重要基础，这或许是必然性和偶然性并存所致。<a href="https://zhuanlan.zhihu.com/p/412142380" target="_blank">aultBoot 是一个专注于固件安全</a>，可信计算以及高级防御的固件载荷执行体，其设计可以在coreboot平台上发挥出最卓越的防护效果，包括CBnT和多种ACM的开箱过程都可以基于coreboot完成，此外<a href="https://zhuanlan.zhihu.com/p/412142380" target="_blank">VaultBoot完成诸多安全特性</a>，包括本地/远程证明，基于TPMv1.2/v2.0的全盘加密，测量启动等。</span></i>"</p>
</div>
