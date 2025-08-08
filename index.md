---
layout: default
title: "Vishal Thummalapally"
description: "Lucky you, you found my spot on the world wide web."
---

<p class="intro-text">Lucky you, you found my spot on the world wide web.</p>

<section id="about">
  <h2>About</h2>
  <p>I'm currently a data scientist at Roblox working on pricing, economics, and forecasting 📈. I've also worked at some other places -> <a href="https://www.linkedin.com/in/vishalthummalapally/" target="_blank" rel="noopener">LinkedIn</a></p>
</section>

<section id="blog">
  <h2>Blog</h2>
  <ul class="post-list">
    {% for post in site.posts %}
      <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
    {% endfor %}
    {% if site.posts == empty %}
      <li>No posts yet — but stay tuned!</li>
    {% endif %}
  </ul>
</section>

<!--<img class="center-gif" src="https://media.giphy.com/media/o0vwzuFwCGAFO/giphy.gif" alt="retro hacker text gif"> -->
<img class="center-gif" src="{{ '/assets/img/library.gif' | relative_url }}" alt="Library animation">
