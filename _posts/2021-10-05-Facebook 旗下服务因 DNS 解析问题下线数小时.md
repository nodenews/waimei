---
layout: post
title: "Facebook 旗下服务因 DNS 解析问题下线数小时"
date: 2021-10-05T00:57:15.000Z
author: Solidot
from: https://www.solidot.org/story?sid=69137
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1633395435000-->
[Facebook 旗下服务因 DNS 解析问题下线数小时](https://www.solidot.org/story?sid=69137)
------

<div>
Facebook 平台包括 WhatsApp 和 Instagram 因 DNS 解析问题<a href="https://blog.cloudflare.com/october-2021-facebook-outage/" target="_blank">下线了五个小时</a>，问题被认为是路由配置错误导致的。<i>10 月 4 日 16:50 UTC 左右，1.1.1.1 公共 DNS 服务器提供商 Cloudflare 注意到 Facebook、WhatsApp 和 Instagram 的域名突然停止解析，社交巨头的所有 IP 都无法抵达，就好像 Facebook 的数据中心同时从互联网上断开。Facebook 通过 BGP 向其他网络广播其存在，在 16:40 UTC ，Facebook 发出了一系列路由变更，问题跟着产生了，它停止广播其 DNS 前缀路由，DNS 服务器下线，Facebook 相关域名停止解析随后影响到其他 DNS 服务器，Facebook 事实上从互联网上消失了。21:00 UTC 左右，Facebook 重新广播其路由信息，到 21:20 UTC 其服务恢复正常。</i>为什么问题持续了如此长的时间？根据社交网络上未经证实的<a href="https://old.reddit.com/r/sysadmin/comments/q181fv/looks_like_facebook_is_down/hfda42z/">消息</a>：在路由问题发生之后，能物理接触系统的工程师与有权限登陆系统的工程师与知道如何解决问题的工程师之间存在协调方面的问题。
</div>
