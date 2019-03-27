---
layout: page
title: Open business model
date: 2017-11-15
permalink: /open-business-model/
back-link: /about/
back-name: Chi siamo
update: 2018-05-17
indice: yes
image: assets/img/tangram/osd-tangram-open-business-model.png
img-logo: OBMC.svg
---
L'open business model applicato ai dati è un mix tra il concetto di "open innovation" di Henry Chesbrought e il "business model canvas" di Alexander Osterwalder:

- L'apertura (*open* appunto) consente di distribuire parte del patrimonio dati per favorire l'uso di esso da parte di soggetti esterni ai contatti dei nostri clienti; in questo modo i dati diventano strumento di relazione e interesse verso le attività e le competenze dei nostri assistiti.
- Il business model canvas ci consente di valutare quali licenze d'uso applicare ia dati, quali distribuire, verso quali segmenti e con quali canali. In breve la tattica e la strategia per trasformare i dati da asset intangibile in capitale finanziario.

#### 1 ora: 150€ + IVA
*Consulenza filosofica per definire una missione chiara e convincente*

#### 1 giornata: 1000€ + IVA
*Costruiamo assieme l'Open Business Model, il documento applicativo e l'Open Business Model Canvas*

#### 4 giorni: 3400€ + IVA
*Facciamo un'analisi dei valori e degli obiettivi, introduciamo al Masterplan e componiamo l'Open Business Model Canvas compilando poi lo schema operativo*

#### Mensile:  [mandaci una mail](mailto:contact@osd.tools)
*Interveniamo con il Masterplan management assumendo il ruolo di Temporary Product Owner*

<hr>
{% assign service = site.services | sort:"num" | reverse %}
{% for service in site.services %}
  <div class="activities-block">
    <img src="{{ site.url }}/assets/servizi/{{ service.img-logo }}" alt="logo {{ service.title }}">
    <div class="title-activity">
      <h2><a href="{{ service.url }}">{{ service.title }}</a></h2>
    </div>
  </div>
  <hr>
{% endfor %}
