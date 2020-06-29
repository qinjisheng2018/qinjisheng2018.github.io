---
layout: page
title: 友情链接
description: 没有链接的博客是孤独的
keywords: 友情链接
comments: false
menu: 友情链接
permalink: /links/
---

> 追逐大神的脚步

<ul>
{% for link in site.data.links %}
  {% if link.src == 'life' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>

> 友情链接

<ul>
{% for link in site.data.links %}
  {% if link.src == 'www' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>
