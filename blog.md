---
layout: default
title: "Blog"
permalink: /blog/
---

<h2>Blog</h2>
<ul class="post-list">
  {% for post in site.posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
  {% if site.posts == empty %}
    <li>No posts yet — but stay tuned!</li>
  {% endif %}
</ul>