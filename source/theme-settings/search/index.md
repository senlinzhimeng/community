---
layout: docs
title: 站内搜索
group: docs-volantis-latest
order: 309
short_title: 3-9 站内搜索
sidebar: [repos, docs-volantis-latest, toc]
disqus:
  path: /wiki/volantis/
---

```yaml blog/_config.volantis.yml
search:
  enable: true
  service: hexo  # hexo, google, algolia, azure, baidu
  js: https://cdn.jsdelivr.net/gh/volantis-x/cdn-volantis@2.6.4/js/search.js
  google:
    apiKey:
    engineId:
  algolia:
    applicationID:
    apiKey:
    indexName:
  azure:
    serviceName:
    indexName:
    queryKey:
  baidu:
    apiId:
```
默认配置为 Hexo 搜索，但是需要安装插件才能使用：
```sh
npm i -S hexo-generator-search hexo-generator-json-content
```
