---
layout: default
title: Home
---

This is just the beginning. Perhaps we should put more here? The answer is: **_YES,_** we should do that.

<ul>
  {% for page in site.pages %} 
      <li><a href="{{site.url}}{{site.baseurl}}{{ page.url }}">{{ page.title }}</a></li>
  {% endfor %}
</ul>
