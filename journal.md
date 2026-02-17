---
layout: page
title: Journal
permalink: /journal/
---

Reflections on growth, balance, and structure.

{% for post in site.categories.journal %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p><em>{{ post.date | date: "%B %d, %Y" }}</em></p>
    <p>{{ post.excerpt }}</p>
  </article>
  <hr>
{% endfor %}
