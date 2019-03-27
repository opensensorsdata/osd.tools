---
layout: page
title: La biblioteca di OSD
date: 2017-11-14
permalink: /biblioteca/
back-link: /manifesto_osd_it/
back-name: Manifesto
update: 2018-05-17
indice: yes
image: assets/img/tangram/osd-tangram-biblioteca.png
---
[Scarica il csv da Github](https://github.com/opensensorsdata/biblioteca/blob/master/biblioteca-OSD.csv)
<ul class="biblioteca-list">
{% assign books = site.data.books | sort: 'autori' %}
{% for book in books %}
  <li>{{ book.autori }}, <i>{{ book.titolo }}</i>, {{ book.edizione}}&ordf; ed., {{ book.editore }}, {{ book.luogo }}, {{ book.anno }}, ({{ book.formato }})</li>

{% endfor %}
</ul>
