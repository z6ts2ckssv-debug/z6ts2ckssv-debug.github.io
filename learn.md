---
layout: page
title: Learn
permalink: /learn/
---

Thoughts inspired by studying chemistry and understanding systems.

{% for post in site.categories.learn %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p><em>{{ post.date | date: "%B %d, %Y" }}</em></p>
    <p>{{ post.excerpt }}</p>
  </article>
  <hr>
{% endfor %}
