---
title: Isaiah Harrison
layout: base.njk
---

# I'm a pseudo Web Developer

Blogging about random stuff. Mostly webdev, Legends Of Runeterra, other nerdy things, etc.

## Recent Blog Posts
<ul>
  {% for post in collections.posts reversed %}
    <li><a href="{{ post.url }}">{{ post.data.title }}</a></li>
  {% endfor %}
</ul>