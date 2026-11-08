---
layout: default
title: 作品一覧
---

# 作品一覧

## 短編

{% for novel in site.novels %}
{% if novel.length == "短編" %}
- [{{ novel.title }}]({{ site.baseurl }}{{ novel.url }})（{{ novel.rating }}{% if novel.setting == "現パロ" %}・現パロ{% endif %}）
{% endif %}
{% endfor %}

## 中編

{% for novel in site.novels %}
{% if novel.length == "中編" %}
- [{{ novel.title }}]({{ site.baseurl }}{{ novel.url }})（{{ novel.rating }}{% if novel.setting == "現パロ" %}・現パロ{% endif %}）
{% endif %}
{% endfor %}

## 長編

{% for novel in site.novels %}
{% if novel.length == "長編" %}
- [{{ novel.title }}]({{ site.baseurl }}{{ novel.url }})（{{ novel.rating }}{% if novel.setting == "現パロ" %}・現パロ{% endif %}）
{% endif %}
{% endfor %}

## 連載

{% for novel in site.novels %}
{% if novel.length == "連載" %}
- [{{ novel.title }}]({{ site.baseurl }}{{ novel.url }})（{{ novel.rating }}{% if novel.setting == "現パロ" %}・現パロ{% endif %}）
{% endif %}
{% endfor %}
