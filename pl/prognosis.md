---
layout: page
lang: pl
title: null
---

{% assign forecasts = site.prognosis_pl | reverse %}


{% for forecast in forecasts limit:1 %}
<section id="banner">
<div class="content">
  <header>
    <h1>{{ forecast.title }} </h1>
    <p>najnowsza prognoza</p>
  </header>
  <p>{{ forecast.teaser }}</p>
</div>
<span class="image object">
  <img src="{{ forecast.image_teaser }}" alt="" />
</span>
</section>

<div class="row">
    {{ forecast.content }}
</div>

{% endfor %}

<hr />

<h2>Archiwalne prognozy</h2>

<div class="posts">
{% for analysis in forecasts offset:1 %}
		<article>
			<a href="{{ analysis | absolute_url }}" class="image"><img src="{{ analysis.image_teaser }}" alt="" /></a>
			<h3>{{ analysis.title }}</h3>
			<p>{{ analysis.teaser }}</p>
			<small style="font-variant: all-small-caps">{{ analysis.date | date: "%Y-%m-%d" }}</small>
			<ul class="actions">
				<li><a href="{{ analysis | absolute_url }}" class="button">Więcej</a></li>
			</ul>
		</article>
{% endfor %}
</div>