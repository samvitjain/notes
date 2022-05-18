---
layout: page
title: books
---

{% for book in site.books %}
  <h2>
    <a href="{{ book.url }}">
      {{ book.title }} - {{ book.author }}
    </a>
  </h2>
  
{% endfor %}
