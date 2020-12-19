---
layout: page
lang: pl
title: Nasze Analizy
---

<p>Grupa MOCOS (MOdelling COronavirus Spread) to międzynarodowy interdyscyplinarny zespół naukowców zajmujący się modelowaniem epidemii COVID-19.</p>

{% assign analyses = site.analysis_pl | reverse %}
<div class="posts">
{% for analysis in analyses %}
    {% if analysis.hidden != true %}	
		<article>
			<a href="{{ analysis | absolute_url }}" class="image"><img src="{{ analysis.image_teaser }}" alt="" /></a>
			<h3>{{ analysis.title }}</h3>
			<p>{{ analysis.teaser }}</p>
			<ul class="actions">
				<li><a href="{{ analysis | absolute_url }}" class="button">Więcej</a></li>
			</ul>
		</article>
	{% endif %}
{% endfor %}
</div>