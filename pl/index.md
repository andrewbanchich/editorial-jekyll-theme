---
layout: default
lang: pl
title: Strona Główna
---

{% assign forecasts = site.prognosis_pl | reverse %}

{% for forecast in forecasts limit: 1 %}

<section id="banner">
    <div class="content">
      <header>
        <h1>{{ forecast.title }} </h1>
        <p>najnowsza prognoza</p>
      </header>
      <p>{{ forecast.teaser }}</p>
      <ul class="actions">
        <li><a href="{{ forecast | absolute_url }}" class="button big">Więcej</a></li>
      </ul>
    </div>
    <span class="image object">
      <img src="{{ forecast.image_teaser }}" alt="" />
    </span>
  </section>

{% endfor %}

<div class="row">
	<div class="8u 12u$(small)">
		<h3>Grupa MOCOS nagrodzona w konkursie 30 kreatywnych Wrocławian</h3>
		<p></p>
		<a class="button" href="https://www.wroclaw.pl/30-kreatywnych-wroclawia/2020/grupa-mocos">Informacja prasowa</a>
		<a class="button" href="https://www.youtube.com/watch?t=2400&v=TSNcEo1VtlU">Wystąpienie prof. Krugera</a>
	</div>
	<div class="4u$ 12u$(small)">
	    <span class="image fit">
	        <img src="/assets/images/30_kreatywnych.jpg" />
	    </span>
	</div>
</div>

<!-- Section -->
<section>
	<header class="major">
		<h2>Nasza praca, to nie tylko prognozy:</h2>
	</header>
	<div class="features">
		<article>
			<span class="icon fa-diamond"></span>
			<div class="content">
				<h3><a href="/pl/recommendations.html">Aktualne rekomendacje</a></h3>
				<p>Prezentujemy rekomendacje dla władz krajowych, regionalnych i zwykłych obywateli - jak działać, by pandemia wygasła?
				</p>
			</div>
		</article>
		<article>
			<span class="icon fa-question"></span>
			<div class="content">
				<h3><a href="https://www.socjologia.uni.wroc.pl/Aktualnosci/Ankieta-Spoleczne-uwarunkowania-postaw-wobec-epidemii-koronawirusa">Ankieta badawcza</a></h3>
				<p>Razem z Instytutem Socjologii Uniwersytetu Wrocławskiego badamy Wasze zachowania, aby lepiej modelować przebieg pandemii. Jeśli chcesz pomóc - wypełnij ankietę!</p>
			</div>
		</article>
		<article>
			<span class="icon fa-calculator"></span>
			<div class="content">
				<h3><a href="/pl/risk.html">Ocena indywidualnego ryzyka COVID-19</a></h3>
				<p>Interesuje Cię oszacowanie indywidualnego prawdopodobieństwa warunkowego śmierci lub hospitalizacji? 
				Członkowie grupy MOCOS zbudowali model ryzyka na podstawie danych z pierwszej połowy roku.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-line-chart"></span>
			<div class="content">
				<h3><a href="/pl/automatic.html">Polsko-niemiecki HUB prognoz COVID-19</a></h3>
				<p>Model grupy MOCOS jest częścią German & Polish COVID-19 Forecast HUB. Znajdziesz tam prognozy rozwoju epidemii na najbliższe 2 tygodnie dla Polski. </p>
			</div>
		</article>
	</div>
</section>

<!-- Section -->
<section>
	<header class="major">
		<h2>Analizy</h2>
	</header>

{% assign analyses = site.analysis_pl %}
<div class="posts">
{% for analysis in analyses %}	
		<article>
			<a href="{{ analysis | absolute_url }}" class="image"><img src="{{ analysis.image_teaser }}" alt="" /></a>
			<h3>{{ analysis.title }}</h3>
			<small>{{ analysis.date  | date: "%Y-%m-%d" }}</small>
			<p>{{ analysis.teaser }}</p>
			<ul class="actions">
				<li><a href="{{ analysis | absolute_url }}" class="button">Więcej</a></li>
			</ul>
		</article>
{% endfor %}
</div>

</section>
