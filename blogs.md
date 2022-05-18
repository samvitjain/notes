---
layout: page
title: blogs
---

{% for blog in site.blogs %}
  <h2>
    <a href="{{ blog.url }}">
      {{ blog.title }} - {{ blog.dateX }}
    </a>
  </h2>
  
{% endfor %}
