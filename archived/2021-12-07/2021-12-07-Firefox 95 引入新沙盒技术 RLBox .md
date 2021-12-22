---
layout: post
title: "Firefox 95 引入新沙盒技术 RLBox "
date: 2021-12-07T05:23:33.000Z
author: Solidot
from: https://www.solidot.org/story?sid=69897
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1638854613000-->
[Firefox 95 引入新沙盒技术 RLBox](https://www.solidot.org/story?sid=69897)
------

<div>
Mozilla <a href="https://hacks.mozilla.org/2021/12/webassembly-and-back-again-fine-grained-sandboxing-in-firefox-95/">介绍了</a>即将发布的 Firefox 95 引入的新沙盒技术 RLBox。RLBox 由 Mozilla 与加州圣迭戈和德州大学的研究人员联合开发，旨在简单高效的隔离子组件，加强浏览器的安全性。<a href="https://plsyssec.github.io/rlbox_sandboxing_api/sphinx/" target="_blank">RLBox</a> 使用 WebAssembly 技术去隔离潜在含有 bug 的代码，方法是将这些代码编译到 WebAssembly 然后再编译到原生码，这种编译转换限制不可信的代码访问程序的其它部分，限制其访问指定区域之外的内存。目前这项技术已用于隔离五个模块：<a href="https://scripts.sil.org/cms/scripts/page.php?site_id=projects&amp;item_id=graphite_home" target="_blank">Graphite</a>、<a href="http://hunspell.github.io/" target="_blank">Hunspell</a>、<a href="https://xiph.org/ogg/" target="_blank">Ogg</a>、<a href="https://libexpat.github.io/" target="_blank">Expat</a> 和 <a href="https://github.com/google/woff2" target="_blank">Woff2</a>，Firefox 将这些模块视为不信任的代码，因此即使其中含有 0day 漏洞也不会影响整体的浏览器。下一个版本将隔离另外两个模块 Expat 和 Woff2。
</div>
