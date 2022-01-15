---
layout: post
title: "lurch/OMEMO密码工程协议审计"
date: 2021-12-31T04:12:58.000Z
author: Solidot
from: https://www.solidot.org/story?sid=70203
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1640923978000-->
[lurch/OMEMO密码工程协议审计](https://www.solidot.org/story?sid=70203)
------

<div>
<a href="http://https://hardenedvault.net/">HardenedVault</a> 写道<i> "<a href="https://eprint.iacr.org/2020/1231" target="_blank">vault1317</a><span style="color: rgb(18, 18, 18);">是一款为<a href="https://zhuanlan.zhihu.com/p/406518045" target="_blank">高级威胁防护背景下</a>设计的密码工程通信协议，在OTRv3/v4和Signal协议基础上加强了通信节点的元数据保护，即保护机器的隐私。在此基础上提供加密通信过程的可抵赖性，以保证在通信节点任意一方进行背叛行为（向第三方披露通信内容）和长寿命密钥泄漏的情况下也无法留下加密证据。<a href="https://zhuanlan.zhihu.com/p/451974583" target="_blank">vault1317的目标并非保护人类隐私</a>，而是通信节点（机器）的隐私。当赛博堡垒设计vault1317第二阶段邦联化特性过程中收到了密码朋克社区的诸多建议，从威胁模型的角度，<a href="https://zhuanlan.zhihu.com/p/451974583" target="_blank">数字军火商</a>不会放弃任意高度依赖密码工程的领域，</span><span style="color: rgb(18, 18, 18);">更重要的是，邦联化作为去中心化特性的关键要素必须进行<a href="https://zhuanlan.zhihu.com/p/451974583" target="_blank">架构级审计</a>，vault1317协议的当前邦联化是通过XMPP，经过技术评估赛博堡垒最终选择了基于lurch，</span>lurch<span style="color: rgb(18, 18, 18);">是一个实现了</span>XEP 0384<span style="color: rgb(18, 18, 18);">（OMEMO）加密协议</span>修订版<span style="color: rgb(18, 18, 18);"> 的</span>pidgin<span style="color: rgb(18, 18, 18);">插件。OMEMO是一个基于axolotl协议的实现，在lurch中 axolotl的实现基于</span>libsignal-protocol-c<span style="color: rgb(18, 18, 18);">，axc则是基于libsignal-protocol-c进行了高阶封装的实现。</span><span style="color: rgb(18, 18, 18);">由于lurch上下游的依赖，<a href="https://zhuanlan.zhihu.com/p/451974583" target="_blank">审计目标</a>除了lurch本身也包括两个支持库axc和libomemo，审计过程中发现的缺陷已经修复。</span>"</i>
</div>
