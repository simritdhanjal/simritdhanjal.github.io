---
layout: default
title: Blog
permalink: /blog.html
---

<div class="blog-content">
  <h1>Blog</h1>
  
  <p class="blog-intro">
    Reflections on technology, learning, and what drives us forward.
  </p>
  
  <div class="posts-list">
    {% for post in site.posts %}
      <article class="post-item">
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <time class="post-date">{{ post.date | date: "%b %-d, %Y" }}</time>
      </article>
    {% endfor %}
  </div>
</div>