---
layout: single
title: C++20 Guides
---

{% assign date = '2020-04-13T10:20:00Z' %}

C++20 Guides



- Original date - {{ date }}
- With timeago filter - {{ date | timeago }}

{% for article in site.cpp20_guides %}
  <h2>{{ article.title }}</h2>
  <p>{{ article.content | markdownify }}</p>
{% endfor %}