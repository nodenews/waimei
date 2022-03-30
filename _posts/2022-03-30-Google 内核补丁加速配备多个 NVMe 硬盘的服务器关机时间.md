---
layout: post
title: "Google 内核补丁加速配备多个 NVMe 硬盘的服务器关机时间"
date: 2022-03-30T14:02:04.000Z
author: Solidot
from: https://www.solidot.org/story?sid=71110
tags: [ Solidot ]
comments: True
categories: [ Solidot ]
---
<!--1648648924000-->
[Google 内核补丁加速配备多个 NVMe 硬盘的服务器关机时间](https://www.solidot.org/story?sid=71110)
------

<div>
Google 工程师递交的一个<a href="https://lore.kernel.org/lkml/20220328230008.3587975-1-tansuresh@google.com/">内核补丁</a>旨在解决服务器有太多 NVMe 硬盘时的<a href="https://www.theregister.com/2022/03/29/google_kernel_patch/?td=rt-3a">重启问题</a>。Linux 内核目前使用的驱动器关机功能使用的是同步机制，对于每一个驱动器，它都需要等待关机指令完成才能执行下一 步。关闭一个驱动器需要大约 4.5 秒的时间，如果一台服务器使用了 16 个 NVMe 驱动器，那么重启服务器需要等待 72 秒。Google 工程师的补丁将同步改为异步，在向第一个驱动器发出指令后立即转向下一个。异步关机将能大幅节省服务器重启所需的时间。
</div>
