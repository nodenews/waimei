---
layout: post
title: "ImageNet 库包含了一对 NeuralHash 哈希碰撞的图像"
date: 2021-08-20T02:24:41.000Z
author: Solidot
from: https://www.solidot.org/story?sid=68608
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1629426281000-->
[ImageNet 库包含了一对 NeuralHash 哈希碰撞的图像](https://www.solidot.org/story?sid=68608)
------

<div>
NeuralHash 是苹果  CSAM 儿童色情扫描系统使用的感知哈希算法，它通过输入图像返回 96 位的哈希值，如果两个图像有相同的哈希那么这两个图像应该是相同的。然而实际上并非如此，NeuralHash 产生的哈希相同并不意味着图像相同，这就是哈希碰撞。研究人员已经<a href="https://www.solidot.org/story?sid=68596" target="_blank">演示了</a>对 NeuralHash 的原像攻击，创造出两个哈希一样但两幅完全不同的图像。该图像是人为制造出来的，那么有没有哈希相同的自然图像？图像数据库 ImageNet 被发现<a href="https://blog.roboflow.com/nerualhash-collision/" target="_blank">包含了一对 NeuralHash 哈希相同的图像</a>。
</div>
