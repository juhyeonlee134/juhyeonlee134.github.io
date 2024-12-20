---
layout: page
title: /unity
permalink: categories/unity/
category: unity
---

## unity

<ul>
  {% for post in site.categories['unity'] %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>