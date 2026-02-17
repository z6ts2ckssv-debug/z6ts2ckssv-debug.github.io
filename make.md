---
layout: page
title: Make
permalink: /make/
---

DIY projects and creative experiments.

{% for post in site.categories.make %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p><em>{{ post.date | date: "%B %d, %Y" }}</em></p>
    <p>{{ post.excerpt }}</p>
  </article>
  <hr>
{% endfor %}
