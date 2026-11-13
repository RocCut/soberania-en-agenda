---
layout: default
title: Multimedia
---

<h1>Multimedia</h1>

<div class="cards">
{% for r in site.data.recursos %}
  <a class="card" href="{{ r.url | relative_url }}">
    <span class="card-tipo">{{ r.tipo }}</span>
    <h2>{{ r.titulo }}</h2>
    <p>{{ r.descripcion }}</p>
  </a>
{% endfor %}
</div>
