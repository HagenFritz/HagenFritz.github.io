---
layout: category
title: "Construction"
category: construction
permalink: /categories/construction/
---

# Construction

{% for post in site.categories.construction %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p><em>{{ post.date | date: "%B %d, %Y" }}</em></p>
    <p>{{ post.excerpt }}</p>
  </article>
{% endfor %}
