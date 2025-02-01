---
layout: archive
title: "Posts in Category 1"
which_category: category1
---

<h1>{{ page.title }}</h1>

<ul>
  {% for post in site.categories.category1 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
