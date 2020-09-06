---
layout: page
title: Indice dei contenuti
subtitle: Qui troverai sicuramente ciò che stai cercando
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
