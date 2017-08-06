---
layout: article
permalink: /auteures
title: "Auteur.e.s" 
---

<div>
<ul>
    {% for author in site.data.authors %}
    <li>
        {{ author.name }}
    </li>
    {% endfor %}
</ul>
</div>
