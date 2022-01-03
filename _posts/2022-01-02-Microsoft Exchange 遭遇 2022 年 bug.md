---
layout: post
title: "Microsoft Exchange 遭遇 2022 年 bug"
date: 2022-01-02T16:02:16.000Z
author: Solidot
from: https://www.solidot.org/story?sid=70223
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1641139336000-->
[Microsoft Exchange 遭遇 2022 年 bug](https://www.solidot.org/story?sid=70223)
------

<div>
用户通过社交媒体<a href="https://old.reddit.com/r/sysadmin/comments/rt91z6/exchange_2019_antimalware_bad_update/">报告</a>，从 1 月 1 日起微软的 Microsoft Exchange 服务器无法发送邮件。原因被发现是 FIP-FS 扫描引擎<a href="https://it.slashdot.org/story/22/01/01/2333225/year-2022-bug-breaks-email-delivery-for-microsoft-exchange-on-premise-servers">导致的</a>。从 Exchange Server 2013 起，微软默认启用了 FIP-FS 反垃圾邮件和反恶意软件扫描引擎。微软使用了一个有符号 32 位整型变量储存日期值，其最大值为 2,147,483,647，而 2022 年日期的最小值为  2,201,010,001，大于最大值，导致了扫描引擎初始化失败，无法释放邮件。微软已经创建了<a href="https://techcommunity.microsoft.com/t5/exchange-team-blog/email-stuck-in-transport-queues/ba-p/3049447">一个脚本</a>解决这个问题。
</div>
