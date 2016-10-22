---
layout: page
author: Jorge Luis Borges
title: Borges - The Garden of Forking Paths
work: The Garden of Forking Paths
permalink: /borges/the-garden-of-forking-paths/
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
{% if excerpt.citation == "[_The Garden of Forking Paths_](/borges/the-garden-of-forking-paths)" %}
<a href="{{ author.permalink }}">{{ author.work }}</a>:<br/>
{{ excerpt.excerpt }}
{% endif %}
{% endfor %}
{% endif %}
{% endfor %}
