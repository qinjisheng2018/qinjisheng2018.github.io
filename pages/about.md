---
layout: page
title: 个人简介
description: XXXX
keywords: xxxx
comments: false
menu: 关于
permalink: /about/
---





## 联系方式

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">{{ website.name }}</a></li>
{% endfor %}
{% if site.url contains 'qinjisheng.top' %}
<li>
微信公众号：<br />
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="{{ assets_base_url }}/assets/images/qrcode.jpg" alt="计算机初学者" />
</li>
{% endif %}
</ul>


## 其他方面

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
