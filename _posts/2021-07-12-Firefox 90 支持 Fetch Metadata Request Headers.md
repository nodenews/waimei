---
layout: post
title: "Firefox 90 支持 Fetch Metadata Request Headers"
date: 2021-07-12T14:53:38.000Z
author: Solidot
from: https://www.solidot.org/story?sid=68261
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1626101618000-->
[Firefox 90 支持 Fetch Metadata Request Headers](https://www.solidot.org/story?sid=68261)
------

<div>
Mozilla<a href="https://blog.mozilla.org/security/2021/07/12/firefox-90-supports-fetch-metadata-request-headers/"> 宣布</a> Firefox 90 将支持 <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers#fetch_metadata_request_headers" target="_blank">Fetch Metadata Request Headers</a>，它能保护用户抵御多种跨源威胁如跨站请求伪造，跨站泄漏和预测跨站执行旁路攻击。新的 HTTP 请求头文件 Sec-Fetch-Site 允许 Web 应用服务器区分来自相应 Web 应用程序的同源请求和来自攻击者控制网站的跨源请求。通过检查 Sec-Fetch-* Headers 允许 Web 应用服务器拒绝或忽略恶意请求。总共有四种不同的  Sec-Fetch-* 请求头文件：Dest、Mode、Site 和 User。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
