---
layout: post
title: "Mozilla NSS 库发现高危漏洞"
date: 2021-12-02T14:16:34.000Z
author: Solidot
from: https://www.solidot.org/story?sid=69853
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1638454594000-->
[Mozilla NSS 库发现高危漏洞](https://www.solidot.org/story?sid=69853)
------

<div>
Google Project Zero 安全研究人员 Tavis Ormandy 在广泛使用的 Mozilla Network Security Services (NSS)签名验证库<a href="https://googleprojectzero.blogspot.com/2021/12/this-shouldnt-have-happened.html">发现了一个本应该早就发现的高危漏洞</a>：一个简单的边界检查问题会导致内存破坏（memory corruption）。NSS 至少从 2014 年开始就支持模糊测试，但 NSS 库是一个模块化库，每个不同组件是独立测试的，在测试时对输入的字符长度设置了一个任意的 10000 字节限制，而 NSS 库却对此没有限制，但它验证的签名长度超过 16384 比特时会导致内存覆写。这个问题本应该很容易发现，Google 研究人员将其命名为“<span class="c11 c8">BigSig</span>”，Mozilla 称编号为 <a href="https://www.mozilla.org/en-US/security/advisories/mfsa2021-51/">CVE-2021-43527</a> 的漏洞不影响 Firefox，但其它使用 NSS 库的软件如 Thunderbird、LibreOffice、Evolution 和 Evince 会受到影响。Google Chrome 在 2015 年前使用过 NSS 库，之后用自己的 BoringSSL 替换了 NSS。
</div>
