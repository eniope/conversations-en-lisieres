---
layout: home
title: "Conversations en lisières"
excerpt: "Ce carnet documente une recherche-action en cours."
permalink: /
author_profile: false
entries_layout: list
---

<div class="page-intro">

Bienvenue sur **Conversations en lisières**,  
le carnet d’un **citoyen-chercheur automissionné** qui explore les conditions de la production située de connaissances dans les milieux de vie.

</div>

---

<h2>Catégories</h2>
<ul class="taxonomy__index">
  {% for category in site.categories %}
    <li>
      <a href="{{ site.baseurl }}/categories/#{{ category[0] | slugify }}">
        {{ category[0] }} <span class="taxonomy__count">{{ category[1].size }}</span>
      </a>
    </li>
  {% endfor %}
</ul>

---

{% include posts.html %}
