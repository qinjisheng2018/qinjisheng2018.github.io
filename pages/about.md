---
layout: page
title: 个人简介
description: XXXX
keywords: xxxx
comments: false
menu: 关于
permalink: /about/
---



## Jisheng Qin 秦吉胜

I received my PH.D degree from the **<font color="blue">School of Computer and  Information, Hohai University</font>** in 2023. My advisor was Prof. **<font color="blue">Xiaoqin Zeng</font>**. I am an teacher in School of Computer Science and Technology, **<font color="blue">Anhui University of Technology.</font>**

My current reseach interests include**<font color="blue"> community detection, meachine learning and computer vision</font>**.



## Publications [[Google Scholar]](https://scholar.google.com/)

> 1. **Qin J**, Zeng X, Wu S, et al. E-GCN: Graph Convolution with Estimated Labels [J]. Applied Intelligence, 2020, pp.1-9.









## Foundations

> XXXX







## 编程语言

{% for skill in site.data.skills %}

### {{ skill.name }}

<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>

{% endfor %}



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



