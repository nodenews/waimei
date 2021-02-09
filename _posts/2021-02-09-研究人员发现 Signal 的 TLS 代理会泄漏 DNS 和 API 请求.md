---
layout: post
title: "研究人员发现 Signal 的 TLS 代理会泄漏 DNS 和 API 请求"
date: 2021-02-09T01:12:55.000Z
author: Solidot
from: https://www.solidot.org/story?sid=66897
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1612833175000-->
[研究人员发现 Signal 的 TLS 代理会泄漏 DNS 和 API 请求](https://www.solidot.org/story?sid=66897)
------

<div>
<a href="mailto:realducksoft@gmail.com">DuckSoft</a> 写道<i> "最近，端到端加密消息平台 Signal 被伊朗政府封杀。为了帮助其用户绕过伊朗的审查制度，该公司提出了一个 <a href="https://signal.org/blog/help-iran-reconnect/">TLS 代理</a> 的变通方法。</i><i>继 “Signal 无视代理漏洞，称“这不是风险” 事件”（<a href="https://www.solidot.org/story?sid=66889">Solidot</a>）后，有研究人员<a href="https://community.signalusers.org/t/traffic-not-routed-to-tls-proxies-can-expose-users-to-censors/27479">发现</a>（<a href="https://web.archive.org/web/20210208105906/https://community.signalusers.org/t/traffic-not-routed-to-tls-proxies-can-expose-users-to-censors/27479 " target="_blank">存档</a>），Signal 的&nbsp; Android 应用的最新测试版未能将所有流量路由到 TLS 代理。应用中存在 DNS 泄漏，这对于审查人员来说，了解哪些 IP 地址连接到 Signal 将易如反掌。</i><i></i><p><i>研究人员还报告了其他的流量泄漏问题，包括检查更新等 API 不会走代理等。"</i></p><p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
