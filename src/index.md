---
title: Isaiah Harrison
layout: base.njk
---


# Hi! I'm Isaiah Harrison

Blogging about random stuff. Mostly webdev.

## Recent Blog Posts
<ul>
  {% for post in collections.posts reversed %}
    <li><a href="{{ post.url }}">{{ post.data.title }}</a></li>
  {% endfor %}
</ul>
