---
layout: post
title: "因 BGP 配置错误 Twitter 流量短暂路由经过俄罗斯"
date: 2022-03-30T10:57:49.000Z
author: Solidot
from: https://www.solidot.org/story?sid=71106
tags: [ Solidot ]
comments: True
categories: [ Solidot ]
---
<!--1648637869000-->
[因 BGP 配置错误 Twitter 流量短暂路由经过俄罗斯](https://www.solidot.org/story?sid=71106)
------

<div>
因俄罗斯电信公司 RTCOMM 的 BGP 配置错误，部分 Twitter 的流量<a href="https://arstechnica.com/information-technology/2022/03/absence-of-malice-russian-isps-hijacking-of-twitter-ips-appears-to-be-a-goof/" target="_blank">短暂路由经过俄罗斯</a>。周一的这起<a href="https://bgpstream.com/event/288327">事故</a>持续了约 45 分钟，直至 RTCOMM 停止广播错误路由为止。网络分析公司 Kentik 的 Doug Madory 认为这起事故的起因俄罗斯政府试图阻止本国网民访问 Twitter，但可能是由于意外，RTCOMM 的变更路由影响到了整个互联网。他认为 RTCOMM 试图通过修改 BGP 丢弃特定 IP 范围内的流量，接受错误 BGP 广播的 ISP 会将特定 Twitter IP 空间路由到俄罗斯，然后被丢弃。他不认为俄罗斯尝试发动中间人攻击。
</div>
