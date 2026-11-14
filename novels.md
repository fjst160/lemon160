---
layout: default
title: 作品一覧
---

# 作品一覧

<div class="wavebox">

<span class="wavebox-message">
💬 ご感想はこちら
</span>

<a class="wavebox-link"
   href="https://wavebox.me/wave/51k3vxs5906gcigl/">
🌊📦️
</a>

</div>


## 連載

{% for series in site.series %}

[{{ series.title }}]({{ site.baseurl }}{{ series.url }})（{{ series.rating }}{% if series.setting == "現パロ" %}・現パロ{% endif %}）{% if series.subtitle %}<span class="novel-subtitle">｜ {{ series.subtitle }}</span>{% endif %}

{% endfor %}

## 長編

{% for novel in site.novels %}
{% if novel.length == "長編" %}

[{{ novel.title }}]({{ site.baseurl }}{{ novel.url }})（{{ novel.rating }}{% if novel.setting == "現パロ" %}・現パロ{% endif %}）{% if novel.subtitle %}<span class="novel-subtitle">｜ {{ novel.subtitle }}</span>{% endif %}

{% endif %}
{% endfor %}

## 中編

{% for novel in site.novels %}
{% if novel.length == "中編" %}

[{{ novel.title }}]({{ site.baseurl }}{{ novel.url }})（{{ novel.rating }}{% if novel.setting == "現パロ" %}・現パロ{% endif %}）{% if novel.subtitle %}<span class="novel-subtitle">｜ {{ novel.subtitle }}</span>{% endif %}

{% endif %}
{% endfor %}

## 短編

{% for novel in site.novels %}
{% if novel.length == "短編" %}

[{{ novel.title }}]({{ site.baseurl }}{{ novel.url }})（{{ novel.rating }}{% if novel.setting == "現パロ" %}・現パロ{% endif %}）{% if novel.subtitle %}<span class="novel-subtitle">｜ {{ novel.subtitle }}</span>{% endif %}

{% endif %}
{% endfor %}

## notCP

{% for novel in site.novels %}
{% if novel.length == "notCP" %}

[{{ novel.title }}]({{ site.baseurl }}{{ novel.url }})（{{ novel.rating }}{% if novel.setting == "現パロ" %}・現パロ{% endif %}）{% if novel.subtitle %}<span class="novel-subtitle">｜ {{ novel.subtitle }}</span>{% endif %}

{% endif %}
{% endfor %}
