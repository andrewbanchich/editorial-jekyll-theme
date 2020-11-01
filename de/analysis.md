---
layout: page
lang: de
title: Analysen
---

{% assign analyses = site.analysis_de | reverse %}
<div class="posts">
{% for analysis in analyses %}	
		<article>
			<a href="{{ analysis | absolute_url }}" class="image"><img src="{{ analysis.image_teaser }}" alt="" /></a>
			<h3>{{ analysis.title }}</h3>
			<p>{{ analysis.teaser }}</p>
			<ul class="actions">
				<li><a href="{{ analysis | absolute_url }}" class="button">Więcej</a></li>
			</ul>
		</article>
{% endfor %}
</div>