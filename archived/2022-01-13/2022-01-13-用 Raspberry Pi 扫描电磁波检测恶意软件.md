---
layout: post
title: "用 Raspberry Pi 扫描电磁波检测恶意软件"
date: 2022-01-13T10:20:46.000Z
author: Solidot
from: https://www.solidot.org/story?sid=70354
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1642069246000-->
[用 Raspberry Pi 扫描电磁波检测恶意软件](https://www.solidot.org/story?sid=70354)
------

<div>
法国计算机科学与随机系统研究所的一组研究人员使用单板电脑 Raspberry Pi <a href="https://gizmodo.com/raspberry-pi-can-detect-malware-by-scanning-for-electro-1848339130">创建了</a>一个反恶意软件系统，该系统可扫描设备中的电磁波。该安全设备使用示波器（Picoscope 6407）和连接到Raspberry Pi 2B 的 H-Field 传感器检测受到攻击的计算机发出的特定电磁波中的异常情况，研究人员称这种技术已被用于“获得关于恶意软件类型和身份的准确信息。” 检测系统依靠卷积神经网络（CNN）确定收集到的数据是否表明威胁存在。使用这种技术，研究人员声称可以记录 10 万条被真正恶意软件样本感染的物联网设备的测量轨迹，并以高达 99.82% 的准确率预测三种通用恶意软件和一种良性恶意软件。最重要的是，不需要任何软件，你在扫描的设备也不需要以任何方式进行操作。因此用混淆技术隐藏恶意代码，瞒过恶意软件检测软件的尝试不会成功。研究人员在<a href="https://hal.archives-ouvertes.fr/hal-03374399/document" target="_blank">论文</a>中写道：“我们的方法不需要对目标设备进行任何修改。它可以独立于可用资源进行部署，无需任何开销。而且我们的方法的优点在于，恶意软件作者几乎无法探测并规避它。”
</div>
