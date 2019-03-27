---
layout: page
title: Chi siamo
permalink: /about/
back-link: /
back-name: Home
indice: yes
image: assets/img/design/data_room.png
---

OSD - opensensorsdata srl è un’azienda fondata nel 2015 da Luca Corsato, Simone Cortesi, e Andrea Raimondi. Nell’arco dei primi due anni di attività OSD ha seguito con successo numerosi [progetti di riuso del patrimonio informativo](/attivita), lavorando, tra gli altri, con  l’Istituto Centrale per il Catalogo e la Documentazione (ICCD), Ministero dei Beni Culturale e del Turismo, Centro Nazionale delle Ricerche (CNR), Comune di Venezia, Accademia dei Georgofili e Transparency International.

Consegnamo:

- [gestione]({{ site.url }}/gestire-i-dati)
- [modelli di business]({{ site.url }}/open-business-model) per il patrimonio dati.

# Il nostro [corporate profile]({{ site.url }}/corporate-profile/)



{% for author in site.data.authors %}
<div class="profile-about">
  <div class="profile-img without-decoration">
    <a href="{{ author.img }}"><img src="{{ author.img }}" alt="foto di {{ author.full_name }}"></a>
  </div>
  <div class="author-info">
    <h3>{{ author.full_name }}</h3> <small>{{ author.description }}</small>
    <p>
      <a href="http://www.twitter.com/{{ author.tw }}">@{{ author.tw }}</a>
      <a href="http://www.github.com/{{ author.tw }}">github</a>
      <a href="https://t.me/{{ author.telegram }}">telegram</a>
    </p>
  </div>
</div>

{% endfor %}

# [Manifesto](/manifesto_osd_it) • [Biblioteca](/biblioteca/)
