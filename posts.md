---
layout: page
title: Posts
description: Writing from Calum Shepherd on product management, product strategy, and building with data and AI.
---

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
