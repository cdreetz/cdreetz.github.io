---
layout: page
permalink: /categories/
title: Categories
---

{% for category in site.categories %}
  <li>{{ category | first }}
    <ul>
    {% for post in category.last %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
    </ul>
  </li>
{% endfor %}
