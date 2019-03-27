---
layout: page
title: Attività
permalink: /attivita/
back-link: /servizi/
back-name: Servizi
indice: yes
image: assets/img/tangram/osd-tangram-attivita.png
---

Vogliamo costruire opportunità di innovazione concrete basate su nuove metodologie di business. Lavoriamo per trasformare il modo in cui le aziende, le istituzioni, e gli enti di ricerca pensano e gestiscono il proprio patrimonio informativo. Crediamo di poter cambiare radicalmente il modo in cui i nostri clienti pensano al loro business, alla sua crescita e all’impatto che avranno nel futuro.



{% assign activities = site.activities | sort: 'order' %}
{% for item in activities %}
  <div class="activities-block">
    <img src="{{ site.url }}/assets/img/projects/logos/{{ item.img-logo }}" alt="logo {{ item.title }}">
    <div class="title-activity">
      <h4><a href="{{ item.url }}">{{ item.title }}</a></h4>
    </div>
  </div>
  <hr>
{% endfor %}
