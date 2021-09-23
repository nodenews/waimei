---
layout: post
title: "Google 探索在 Chrome 中使用 Rust"
date: 2021-09-23T02:47:57.000Z
author: Solidot
from: https://www.solidot.org/story?sid=69024
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1632365277000-->
[Google 探索在 Chrome 中使用 Rust](https://www.solidot.org/story?sid=69024)
------

<div>
Chrome 安全团队在官方博客上<a href="https://security.googleblog.com/2021/09/an-update-on-memory-safety-in-chrome.html?m=1">表示</a> Google 正探索在 Chrome 中使用 Rust 语言。Google 安全研究人员去年指出 Chrome/Chromium 项目七成以上的严重安全 bug 是内存安全问题，主要是 C 或 C++ 语言中的指针错误导致的。在致力于让 C++ 更安全的同时，Google Chrome 也在探索使用 Rust 语言。Rust 是 Mozilla 开发的内存安全语言，能在编译时发现指针错误。但让 Rust 和 C++ 语言良好合作仍然是一个开放式问题。即使 Google 立即开始用 Rust 语言为 Chrome 开发大型组件，相当大一部分的安全漏洞在几年内是不会消失的。Google 开发者表示他们开始在 Chromium 源码树中<a href="https://source.chromium.org/chromium/chromium/src/+/main:build/config/rust.gni" target="_blank">尝试</a>有限的不面向用户的 Rust 实验，但暂时不会将其用于 Chrome 产品中。
</div>
