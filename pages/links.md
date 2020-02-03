---
layout: page
title: Links
description: 没有链接的博客是孤独的
keywords: 友情链接
comments: true
menu: 链接
permalink: /links/
---

> 欢迎其他 Blog /公众号/自媒体与我联系加入友情链接

{% for link in site.data.links %}
  {% if link.src == 'life' %}

* [{{ link.name }}]({{ link.url }})
  {% endif %}
{% endfor %}

{% for link in site.data.links %}
  {% if link.src == 'www' %}
* [{{ link.name }}]({{ link.url }})
  {% endif %}
{% endfor %}
