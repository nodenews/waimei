---
layout: post
title: "为什么 uBlock Origin 在 Firefox 上效果最佳"
date: 2021-04-10T03:00:26.000Z
author: Solidot
from: https://www.solidot.org/story?sid=67450
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1618023626000-->
[为什么 uBlock Origin 在 Firefox 上效果最佳](https://www.solidot.org/story?sid=67450)
------

<div>
uBlock Origin 作者 Raymond Hill <a href="https://github.com/gorhill/uBlock/wiki/uBlock-Origin-works-best-on-Firefox">解释了</a>为什么他的广告屏蔽扩展在 Firefox 上工作效率最佳。uBlock Origin 支持 Firefox 和基于 Chromium 的浏览器如 Chrome。他称，Firefox 支持曝光利用 CNAME记录伪装成第一方的第三方服务；只有 Firefox 支持 webRequest.filterResponseData() API，允许在浏览器对 HTML 文档解析前过滤响应体；只有 Firefox 支持在 uBlock Origin 启动后发送网络请求；Firefox 能可靠的阻止预取，基于 Chromium 的浏览器无法这么做，因为浏览器给予网站的优先权高于用户设置；Firefox 版本的 uBlock Origin 使用  WebAssembly 作为核心的过滤代码路径。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
