---
layout: post
title: "Fuck GFW｜ClubHouse被封后如何翻墙听？Shadowrocket上的相关设置"
date: 2021-02-10T05:28:12.000Z
author: 翻翻更健康
from: https://chinadigitaltimes.net/chinese/662531.html
tags: [ 中国数字时代 ]
categories: [ 中国数字时代 ]
---
<!--1612934892000-->
[Fuck GFW｜ClubHouse被封后如何翻墙听？Shadowrocket上的相关设置](https://chinadigitaltimes.net/chinese/662531.html)
------

<div>
<p><strong>一.将 ClubHouse 相关域名加入代理</strong></p><p>点击 Shdowrocket 底栏的“配置”，点击“default.conf&quot;，选择“编辑纯文本”将下面的规则复制黏贴进去，然后点击右上角“保存”。</p><p><img src="https://telegra.ph/file/6edb266753254ecbcaef5.png" alt="cdtimg" /></p><p>点击底栏的“配置”，再点击“default.conf&quot;</p><p><img src="https://telegra.ph/file/372d8ba0ccd6328c6f8ea.png" alt="cdtimg" /></p><p>选择”编辑纯文本“</p><p><img src="https://telegra.ph/file/86effaae1761751d6ef51.png" alt="cdtimg" /></p><blockquote><p>DOMAIN-SUFFIX,clubhouseapi.com,PROXY</p><p>DOMAIN-SUFFIX,clubhouseprod.s3.amazonaws.com,PROXY</p><p>DOMAIN-SUFFIX,clubhouse.pubnub.com,PROXY</p><p>DOMAIN-SUFFIX,maintenance.joinclubhouse.com,PROXY</p><p>DOMAIN-SUFFIX,ap3.agora.io,PROXY</p></blockquote><p><strong>编辑注：</strong>ap3.agora.io是声网旗下的域名，这一主站域名（agora.io）已在中国备案，备案号为沪ICP备14053584。这或许了clubhouse使用的某种“安全风险”。</p><p><img src="https://chinadigitaltimes.net/chinese/files/2021/02/image-1612934426440.png" alt="cdtimg" /></p><p>将上面的规则复制粘贴进去，点击右上角”保存“</p><p><strong>二.关闭 Shadowrocket 的 UDP 转发，设置》》》UDP》》》关闭“开启转发”</strong> </p><p><em>如果节点对 UDP 支持不友好，建议关闭 UPD 转发；如果节点 UDP 转发 OK，UDP 转发可以不关闭。</em></p><p><img src="https://telegra.ph/file/ec00fb9dc64e1147d8f6b.png" alt="cdtimg" /></p><p><img src="https://telegra.ph/file/1dbc5e06e77ffc4c4e797.png" alt="cdtimg" /></p><p>The post <a rel="nofollow" href="https://chinadigitaltimes.net/chinese/662531.html">Fuck GFW｜ClubHouse被封后如何翻墙听？Shadowrocket上的相关设置</a> appeared first on <a rel="nofollow" href="https://chinadigitaltimes.net/chinese">中国数字时代</a>.</p>
</div>
