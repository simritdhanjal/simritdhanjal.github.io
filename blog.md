---
layout: default
title: Blog
permalink: /blog.html
---

# Blog

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%B %-d, %Y" }}</small></li>
{% endfor %}
</ul>