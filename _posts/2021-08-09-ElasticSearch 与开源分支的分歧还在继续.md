---
layout: post
title: "ElasticSearch 与开源分支的分歧还在继续"
date: 2021-08-09T13:59:51.000Z
author: Solidot
from: https://www.solidot.org/story?sid=68495
tags: [ Solidot ]
categories: [ Solidot ]
---
<!--1628517591000-->
[ElasticSearch 与开源分支的分歧还在继续](https://www.solidot.org/story?sid=68495)
------

<div>
因亚马逊 AWS 服务利用 ElasticSearch 牟利，开发 Elasticsearch 和 Kibana 的公司 Elastic 在今年早些时候宣布更改许可证，新版本将不再使用 Apache License, Version 2.0 (ALv2) 而是使用 Elastic License 和 Server Side Public License。亚马逊 AWS 随后<a href="https://www.solidot.org/story?sid=68269">宣布</a>创建 Elasticsearch 分支 OpenSearch 和 Kibana 分支 OpenSearch Dashboards，源代码托管在 GitHub 上，继续采用 ALv2 许可证。过去几周，Elastic <a href="https://thenewstack.io/this-week-in-programming-the-elasticsearch-saga-continues/" target="_blank">再次冲击 AWS 及自己的客户</a>：官方的 Elasticsearch 开源客户端库中加入了新的<a href="https://github.com/elastic/elasticsearch-py/pull/1623">逻辑</a>，拒绝连接到 OpenSearch 以及开源版本的  Elasticsearch 7，只允许应用连接到商业付费版本。AWS 再次成为了开源社区的救星，它承诺将会释出一组新的开源客户端，支持连接到 OpenSearch 或 Elasticsearch。AWS 称在开放和互操作性的精神下，它的版本将会支持 Elastic 的产品，它建议用户暂时不要更新到最新版本。<p><img src="https://img.solidot.org//0/446/liiLIZF8Uh6yM.jpg" height="120" style="display:block"/></p>
</div>
