---
layout: page
title: About
description: 
keywords: Leo Xu，徐璨
comments: true
menu: 关于
permalink: /about/
---

我是徐璨，浙江工商大学统计学硕士研究生一年级在读。

现于之江实验室算法实习中。

研究方向包括：图神经网络，推荐系统，基于图的分子表征学习与分子图生成。

## 联系

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
{% if site.url contains 'mazhuang.org' %}
<li>
微信公众号：<br />
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="{{ assets_base_url }}/assets/images/myqrcode.png" alt="我的微信二维码" />
</li>
{% endif %}
</ul>


## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
