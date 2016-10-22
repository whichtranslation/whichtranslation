---
layout: page
author: Jorge Luis Borges
title: Borges - Death and the Compass
work: Death and the Compass
permalink: /borges/death-and-the-compass/
---

Collected in:

* [_Ficciones_](/borges/ficciones)
* [_Labyrinths_](/borges/labyrinths) 
* [_Everything and Nothing_](/borges/everything-and-nothing)
* [_Collected Fictions_](/borges/collected-fictions)

Excerpts:

{% for author in site.authors %}
{% if author.author == page.author %}
{% for excerpt in author.excerpts %}
{% if excerpt.citation == "[_Death and the Compass_](/borges/death-and-the-compass)" %}
<a href="{{ author.permalink }}">{{ author.work }}</a>:<br/>
{{ excerpt.excerpt }}
{% endif %}
{% endfor %}
{% endif %}
{% endfor %}
