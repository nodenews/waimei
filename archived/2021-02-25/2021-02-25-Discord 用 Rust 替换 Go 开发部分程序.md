---
layout: post
title: "Discord 用 Rust 替换 Go 开发部分程序"
date: 2021-02-25T06:37:57.000Z
author: Solidot
from: https://www.solidot.org/story?sid=67028
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1614235077000-->
[Discord 用 Rust 替换 Go 开发部分程序](https://www.solidot.org/story?sid=67028)
------

<div>
流行游戏聊天服务 Discord <a href="https://blog.discord.com/why-discord-is-switching-from-go-to-rust-a190bbca2b1f">透露</a>，该公司用 Rust 语言开发了客户端和服务端组件，在切换到 Rust 实现之后性能有了显著改进。Discord 称在某些领域 Rust 是首要选择的语言。它此前用 Go 语言开发了名为 Read States 的服务，但因为性能问题该服务难以满足产品需求，Go 实现的 Read States 每隔数分钟就会出现延迟飙升。问题与 Go 的内存模式和垃圾收集有关，而 Rust 没有垃圾收集。对比发现&nbsp; Rust 实现的版本在没怎么优化的情况下性能就超过了优化过的 Go 实现版本。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
