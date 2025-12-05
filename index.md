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

🧭 **Ici, vous trouverez :**  
- ce que je fais au présent pour le futur,  
- pourquoi je le fais,  
- comment je le fais — depuis ma trajectoire de bibliothèque vivante,  
- et selon une culture des précédents.

Ce blog est un espace de mise en clarté, de documentation située, et de navigation partagée.

Bonne traversée — et bienvenue dans cette quête sans carte, mais non sans repères.

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
