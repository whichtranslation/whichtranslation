---
layout: page
author: Jorge Luis Borges
title: Borges - Pierre Menard, Author of the Quixote
work: Pierre Menard, Author of the Quixote
permalink: /borges/pierre-menard-author-of-the-quixote/
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
{% if excerpt.citation == "[_Pierre Menard, Author of the Quixote_](/borges/pierre-menard-author-of-the-quixote)" %}
<a href="{{ author.permalink }}">{{ author.work }}</a>:<br/>
{{ excerpt.excerpt }}
{% endif %}
{% endfor %}
{% endif %}
{% endfor %}
