---
layout: post
title: "GitLab 服务器被利用发动 DDoS 攻击"
date: 2021-11-05T05:19:20.000Z
author: Solidot
from: https://www.solidot.org/story?sid=69509
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1636089560000-->
[GitLab 服务器被利用发动 DDoS 攻击](https://www.solidot.org/story?sid=69509)
------

<div>
GitLab 的自托管服务器漏洞<a href="https://therecord.media/gitlab-servers-are-being-exploited-in-ddos-attacks-in-excess-of-1-tbps/?__cf_chl_jschl_tk__=FlJZH_5NDxGQ5ozwb._RT5lSmGTrm3eVNkob5eFxdMA-1636074102-0-gaNycGzNCT0" target="_blank">被利用发动 DDoS 攻击</a>，攻击流量一度超过 1 Tbps。Google 安全工程师发现了这次 DDoS 攻击，攻击者利用了编号为&nbsp; <a href="https://nvd.nist.gov/vuln/detail/CVE-2021-22205" target="_blank" rel="noreferrer noopener nofollow">CVE-2021-22205</a> 的漏洞去控制服务器，GitLab 已在今年 4 月将其修复，但不是所有自托管服务器打上了补丁。漏洞位于 <a href="https://exiftool.org/" target="_blank" rel="noreferrer noopener nofollow">ExifTool</a> 库内，该软件库被用于移除上传到 Web 服务器中的图像元数据。GitLab 在社区版 GitLab Community Edition (CE) 和企业版 Enterprise Edition (EE)中使用了 ExifTool。有大约 6 万 GitLab 自托管服务器联网，其中一半也就是大约 3 万没有打补丁。利用漏洞的 <a href="https://github.com/CsEnox/Gitlab-Exiftool-RCE">POC</a> 在今年 6 月公布，而攻击也是始于 6 月。
</div>
