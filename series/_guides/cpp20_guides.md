---
layout: single
title: C++20 Guides
author_profile: true
---

A series of C++20 guides covering the main features.

{% for article in site.cpp20_guides %}
  <h2>{{ article.title }}</h2>
  <p>{{ article.content | markdownify }}</p>
{% endfor %}