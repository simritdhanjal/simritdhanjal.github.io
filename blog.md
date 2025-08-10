---
layout: default
title: Blog
permalink: /blog.html
---

# Blog

{% for post in site.posts %}
{{ post.date | date: "%b %-d, %Y" }} [{{ post.title }}]({{ post.url }})
{% endfor %}