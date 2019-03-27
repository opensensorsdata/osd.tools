---
layout: page
title: Indice
permalink: /sitemap/
back-link: /
back-name: Home
image: assets/img/tangram/osd_tangram_2_uomo-ombrello.png
---

{% assign sorted_pages = site.pages | sort: "title" %}
{% for page in site.pages %}
  {% if page.indice %}
   [{{ page.title }}]({{ page.url }})
  {% endif %}
{% endfor %}
