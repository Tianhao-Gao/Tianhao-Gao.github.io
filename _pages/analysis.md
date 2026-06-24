---
layout: single
title: "分析笔记"
permalink: /analysis/
author_profile: true
classes: wide
---

以下是分析方向的笔记列表。

<ul>
{% for note in site.notes %}
  {% if note.path contains 'analysis' %}
    <li><a href="{{ note.url }}">{{ note.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
