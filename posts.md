---
layout: page
title: Articles
description: Writing from Calum Shepherd on product management, product strategy, and building with data and AI.
---

<div class="post-list">
{% for post in site.posts %}
  <p class="post-list-item">{{ post.date | date: "%Y" }} - <a href="{{ post.url }}">{{ post.title }}</a></p>
{% endfor %}
</div>
