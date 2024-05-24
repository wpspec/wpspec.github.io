---
title: Welcome
layout: base.njk
---

Blog about webdev. Sometimes about my interests.

## Blog Posts
<ul>
  {% for post in collections.posts reversed %}
    <li><a href="{{ post.url }}">{{ post.data.title }}</a></li>
  {% endfor %}
</ul>
