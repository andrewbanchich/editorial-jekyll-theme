---
layout: default
lang: de
title: Hauptseite
---

{% assign forecasts = site.prognosis_de | reverse %}

{% for forecast in forecasts limit: 1 %}

<section id="banner">
    <div class="content">
      <header>
        <h1>{{ forecast.title }} </h1>
        <p>aktuellste Prognose</p>
      </header>
      <p>{{ forecast.teaser }}</p>
      <ul class="actions">
        <li><a href="{{ forecast | absolute_url }}" class="button big">Weiter</a></li>
      </ul>
    </div>
    <span class="image object">
      <img src="{{ forecast.image_teaser }}" alt="" />
    </span>
  </section>

{% endfor %}

<!-- Section -->
<section>
	<header class="major">
		<h2>Unsere Arbeit, das sind nicht nur Prognosen:</h2>
	</header>
	<div class="features">
		<article>
			<span class="icon fa-calculator"></span>
			<div class="content">
				<h3><a href="/de/risk.html">COVID-19 Individuelle Risikobewertung</a></h3>
				<p>Sind Sie daran interessiert, die individuelle Wahrscheinlichkeit eines bedingten Todes oder eines Krankenhausaufenthalts abzuschätzen? 
                Die MOCOS-Mitglieder haben ein Risikomodell erstellt, das auf Daten aus der ersten Jahreshälfte basiert.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-line-chart"></span>
			<div class="content">
				<h3><a href="/de/automatic.html">COVID-19 Deutsch & Polnisch Forecast HUB</a></h3>
				<p>Das MOCOS-Modell ist Teil des deutsch-polnischen COVID-19-Prognose-HUB. Sie finden dort Prognosen für die Entwicklung der Epidemie für die nächsten 2 Wochen für Polen.</p>
			</div>
		</article>
	</div>
</section>

<!-- Section -->
<section>
	<header class="major">
		<h2>Analysen</h2>
	</header>

{% assign analyses = site.analysis_de | reverse %}
<div class="posts">
{% for analysis in analyses %}	
		<article>
			<a href="{{ analysis | absolute_url }}" class="image"><img src="{{ analysis.image_teaser }}" alt="" /></a>
			<h3>{{ analysis.title }}</h3>
			<p>{{ analysis.teaser }}</p>
			<ul class="actions">
				<li><a href="{{ analysis | absolute_url }}" class="button">Mehr</a></li>
			</ul>
		</article>
{% endfor %}
</div>

</section>
