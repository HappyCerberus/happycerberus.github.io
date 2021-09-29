---
layout: home
author_profile: true
---

Welcome to My Home Page

{% assign date = '2020-04-13T10:20:00Z' %}

- Original date - {{ date }}
- With timeago filter - {{ date | timeago }}

{% for article in site.cpp20 %}
  <h2>{{ article.title }}</h2>
  <p>{{ article.content | markdownify }}</p>
{% endfor %}