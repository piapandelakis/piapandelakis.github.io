---
layout: article
permalink: /auteures
title: "Auteur.e.s" 
---

<div>
<ul class="liste-auteur">
    {% for author in site.data.authors %}
    <li class="auteur-fiche">
      <a href="{{author[1].web}}">{{author[1].name}}</a> <br>
      {{author[1].bio}} 
    </li>
    {% endfor %}
</ul>
<div class="clearfloat"></div>
</div>
