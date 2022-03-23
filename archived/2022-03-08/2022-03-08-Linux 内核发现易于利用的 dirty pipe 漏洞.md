---
layout: post
title: "Linux 内核发现易于利用的 dirty pipe 漏洞"
date: 2022-03-08T15:33:08.000Z
author: Solidot
from: https://www.solidot.org/story?sid=70887
tags: [ Solidot ]
comments: True
categories: [ Solidot ]
---
<!--1646753588000-->
[Linux 内核发现易于利用的 dirty pipe 漏洞](https://www.solidot.org/story?sid=70887)
------

<div>
Web 托管公司 IONOS 的 Max Kellermann 在多次收到客户投诉日志服务器上的日志文件损坏之后展开了调查，发现 Linux 内核存在一个高危漏洞，与数年前曝出的 <a href="https://www.solidot.org/story?sid=50122" target="_blank">DirtyCow</a> 提权漏洞类似，但更容易利用。他将该漏洞命名为 <a href="https://dirtypipe.cm4all.com/">dirty pipe</a>。dirty pipe 存在于 Linux 5.8 之后的版本中，是未初始化变量导致的，它允许任何人向任意文件写入数据，即使文件是 O_RDONLY 或不可改变。它能被用于向任意进程注入代码。Linux 5.16.11、5.15.25 和 5.10.102 修复了该漏洞。
</div>
