---
title: Homepage
layout: base.njk
---


# Hi! I'm Isaiah.

Blogging about random stuff. Mostly webdev. Sometimes about my interests.

## Blog Posts
<ul>
  {% for post in collections.posts reversed %}
    <li><a href="{{ post.url }}">{{ post.data.title }}</a></li>
  {% endfor %}
</ul>
