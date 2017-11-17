---
layout: default
title: Home
---

This is just the beginning. Perhaps we should put more here?

<ul>
  {% for page in site.pages %} 
      <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endfor %}
</ul>
