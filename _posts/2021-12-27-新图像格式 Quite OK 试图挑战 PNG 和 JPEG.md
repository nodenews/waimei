---
layout: post
title: "新图像格式 Quite OK 试图挑战 PNG 和 JPEG"
date: 2021-12-27T05:32:01.000Z
author: Solidot
from: https://www.solidot.org/story?sid=70140
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1640583121000-->
[新图像格式 Quite OK 试图挑战 PNG 和 JPEG](https://www.solidot.org/story?sid=70140)
------

<div>
开发者 Dominic Szablewski <a href="https://www.theregister.com/2021/12/21/quite_ok_image_format/" target="_blank">创建了</a>一种新的图像格式 <a href="https://qoiformat.org/" target="_blank">Quite OK (QOI)</a>，他认为现有的文件格式如 PNG、JPEG、MPEG、MOV 和 MP4 设计上过于复杂繁琐，而且编解码器过于陈旧，需要庞大的库和计算量，很难处理。新格式 QOI 对图像的压缩效果虽然不如优化过的 PNG 编码器，但它能无损将图像压缩到与 PNG 类似大小，同时提供 20 到 50 倍的编码速度和 3 到 4 倍的解码速度。Szablewski 称他的编解码器参考代码只需要 300 行 C 代码，规格要求只有一页纸长。但其他开发者已经<a href="https://tech.slashdot.org/story/21/12/25/0618218/quite-ok-image-format-qoi-coming-to-a-graphics-program-near-you">注意到 QOI 的许多问题</a>，其中最重要的可能是它缺乏冗余，如果一个像素在传输或储存中损坏，会影响到整个图像的其它部分。
</div>
