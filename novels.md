---
layout: default
title: 作品一覧
---
<div class="wavebox">

<div class="wavebox-message">
💬 ご感想はこちら
</div>

<a href="https://wavebox.me/wave/51k3vxs5906gcigl/">
▶ Wavebox
</a>

</div>


# 作品一覧

## 連載

{% for novel in site.novels %}
{% if novel.length == "連載" %}
- [{{ novel.title }}]({{ site.baseurl }}{{ novel.url }})（{{ novel.rating }}{% if novel.setting == "現パロ" %}・現パロ{% endif %}）
{% endif %}
{% endfor %}


## 長編

{% for novel in site.novels %}
{% if novel.length == "長編" %}
- [{{ novel.title }}]({{ site.baseurl }}{{ novel.url }})（{{ novel.rating }}{% if novel.setting == "現パロ" %}・現パロ{% endif %}）
{% endif %}
{% endfor %}


## 中編

{% for novel in site.novels %}
{% if novel.length == "中編" %}
- [{{ novel.title }}]({{ site.baseurl }}{{ novel.url }})（{{ novel.rating }}{% if novel.setting == "現パロ" %}・現パロ{% endif %}）
{% endif %}
{% endfor %}


## 短編

{% for novel in site.novels %}
{% if novel.length == "短編" %}
- [{{ novel.title }}]({{ site.baseurl }}{{ novel.url }})（{{ novel.rating }}{% if novel.setting == "現パロ" %}・現パロ{% endif %}）
{% endif %}
{% endfor %}


## notCP

{% for novel in site.novels %}
{% if novel.length == "notCP" %}
- [{{ novel.title }}]({{ site.baseurl }}{{ novel.url }})（{{ novel.rating }}{% if novel.setting == "現パロ" %}・現パロ{% endif %}）
{% endif %}
{% endfor %}

