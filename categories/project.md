---
layout: page
title: /project
permalink: categories/project/
category: project
---

## project

{% for post in site.categories[page.category] %}
  <div class="post-preview">
    <h2>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </h2>
    <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span>
    {% if post.description %}
      <p>{{ post.description }}</p>
    {% endif %}
  </div>
{% endfor %}