---
layout: page
author: Jorge Luis Borges
title: Borges - Tlön, Uqbar, Orbis Tertius
work: Tlön, Uqbar, Orbis Tertius
permalink: /borges/tlon-uqbar-orbis-tertius/
---

Collected in:

* [_Ficciones_](ficciones)
* [_Labyrinths_](labyrinths) 
* [_Everything and Nothing_](everything-and-nothing)
* [_Collected Fictions_](collected-fictions)

Excerpts:

{% for author in site.authors %}
{% if author.author == page.author %}
{% for excerpt in author.excerpts %}
{% if excerpt.citation == "_Tlön, Uqbar, Orbis Tertius_ - opening" %}
<a href="{{ author.permalink }}">{{ author.work }}</a>:<br/>
{{ excerpt.excerpt }}
{% endif %}
{% endfor %}
{% endif %}
{% endfor %}
