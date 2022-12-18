---
title: "Vision & Language"
excerpt: "<img width='50%' src='/images/previews/ldedit.png'>"
collection: portfolio
--- 

## Publications

{% for post in site.publications reversed %}
  {% if post.categories contains 'Text-Image' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
