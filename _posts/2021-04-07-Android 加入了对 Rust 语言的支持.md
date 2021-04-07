---
layout: post
title: "Android 加入了对 Rust 语言的支持"
date: 2021-04-07T10:05:09.000Z
author: Solidot
from: https://www.solidot.org/story?sid=67419
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1617789909000-->
[Android 加入了对 Rust 语言的支持](https://www.solidot.org/story?sid=67419)
------

<div>
Google 官方安全博客<a href="https://security.googleblog.com/2021/04/rust-in-android-platform.html">宣布</a>，Android 加入了对 Rust 语言的支持。Google 称，七成的 Android 高危漏洞与内存相关，而内存安全语言是解决这一问题的最有效方法。Google 宣布 Android Open Source Project(AOSP)现在支持用 Rust 语言开发操作系统。Java 和 Kotlin 是开发 Android 应用的最佳选择，但对于操作系统的底层，Java 和 Kotlin 不是可选择的。操作系统的底层需要用系统级编程语言 C、C++ 和 Rust 等开发，对 C 和 C++ 来说，开发者负责管理内存，但管理内存时因代码库的复杂性开发者很容易犯错。Rust 语言利用编译时检查和运行时检查确保内存安全，同时它还提供了比拟  C 和 C++ 语言的性能。Google 称用 Rust 重写数千万行 C/C++ 代码是不可行的，对内存相关 bug 的分析显示，大部分 bug 都是近一两年内引入的，因此  Rust 将主要用于新的开发而不是重写成熟的 C/C++ 代码。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
