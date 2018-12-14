---
title: "Test Page for Seth"
layout: splash
read_time: false
header:
  actions:
    - label: "Read More"
      url: "/about/"
excerpt: "A new page for me."
about:
  - excerpt: 'Test copy just to see how this works.'
---

{% include feature_row id="about" type="center" %}

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
