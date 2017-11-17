---
layout: default
title: Home
---

This is just the beginning. Perhaps we should put more here?

<ul>
  {% for page in site.pages %} 
      <li><a href="{{site.url}}{{ page.url }}">{{ page.title }}</a></li>
  {% endfor %}
</ul>
