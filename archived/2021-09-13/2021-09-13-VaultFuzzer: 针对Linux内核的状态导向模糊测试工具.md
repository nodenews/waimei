---
layout: post
title: "VaultFuzzer: 针对Linux内核的状态导向模糊测试工具"
date: 2021-09-13T15:49:54.000Z
author: Solidot
from: https://www.solidot.org/story?sid=68915
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1631548194000-->
[VaultFuzzer: 针对Linux内核的状态导向模糊测试工具](https://www.solidot.org/story?sid=68915)
------

<div>
<a href="http://https://hardenedvault.net/">HardenedVault</a> 写道<i> "在模糊测试领域，2010年代的前半段和后半段几乎被<a href="https://github.com/kernelslacker/trinity" target="_blank">Trinity</a>和<a href="https://github.com/google/syzkaller/" target="_blank">Syzkaller</a>两大工具垄断，经过了数年的发展，syzkaller作为通用QA测试基本能满足Linux内核主线的迭代开发需求，但针对特定子系统的深度探索是远远无法达到高稳定性要求的行业，比如金融，工控，车联网，云计算等行业都会出现几种情况，1）引入第三方内核代码，通常这些代码都是安全漏洞的高危地带，即使不开源，通过逆向工程也可满足安全分析的需求：2）某些行业应用依赖于特定内核子系统中的特定模块，通用型QA无法快速的实现其代码覆盖率：3）应用程序中不完备的回归测试，即应用的运行并没有完成对内核稳定性的基本测试。为了更好的解决这些问题，HardenedVault开发了<a href="https://zhuanlan.zhihu.com/p/410003705" target="_blank">基于状态导向的 fuzzer : VaultFuzzer</a> , VaultFuzzer方案兼容现有的syzkaller框架，最大的优势在于可以把客户的业务需求和特定内核子系统给关联起来，这样的模糊测试可以为业务系统带来更强的稳定性。"</i>
</div>
