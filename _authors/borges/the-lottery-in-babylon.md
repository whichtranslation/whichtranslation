---
layout: page
author: Jorge Luis Borges
title: Borges - The Lottery in Babylon
work: The Lottery in Babylon
permalink: /borges/the-lottery-in-babylon/
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
{% if excerpt.citation == "[_The Lottery in Babylon_](/borges/the-lottery-in-babylon)" %}
<a href="{{ author.permalink }}">{{ author.work }}</a>:<br/>
{{ excerpt.excerpt }}
{% endif %}
{% endfor %}
{% endif %}
{% endfor %}
