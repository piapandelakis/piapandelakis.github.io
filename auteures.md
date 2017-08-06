---
layout: article
permalink: /auteures
title: "Auteur.e.s" 
---

<div>
<ul>
    {% for author in site.data.authors %}
    <li>
    <a href="/auteures/" itemprop="author">
      {{author[1].name}} <br>
        </a>
    </li>
    {% endfor %}
</ul>
</div>
