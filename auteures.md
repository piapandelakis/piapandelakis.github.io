---
layout: archive
permalink: /auteures/
title: "Auteur.e.s" 
---

<div>
<ul class="liste-auteur">
    {% for author in site.data.authors %}
    <li class="auteur-fiche">
   		 <div class="auteur-title">
  	 		<img src="{{ site.url }}/images/{{ author[1].avatar }}" alt="{{ author.name }}" class="auteur-img" height="100">
     	 	<p><a href="{{author[1].web}}" class="auteur-name">{{author[1].name}}</a></p> 
     		<p class="auteur-bio">{{author[1].bio}}</p>
     		<p class="auteur-sujets">{{author[1].sujets}}</p>
    </li>
    {% endfor %}
</ul>
<div class="clearfloat"></div>
</div>
