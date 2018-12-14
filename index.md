---
title: "technicallyseth dot com"
layout: splash
read_time: false
header:
  overlay_image: /assets/images/graph.png
excerpt: "My way of jotting down and organizing thoughts on technology, trends, and what I'd like to build."
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
