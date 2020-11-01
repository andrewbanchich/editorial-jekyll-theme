---
layout: page
lang: de
title: Publikationen und Medien
---

<h2 id="content">Unsere Modelle und Ergebnisse</h2>
<p>Unser Ziel ist es, öffentliche Institutionen dabei zu unterstützen, die Epidemie in einen Zustand der Ausrottung (subkritisch) zu bringen, d.h. das Ausmaß der Virusvermehrung auf ein Niveau zu reduzieren, das aus Sicht der öffentlichen Sicherheit unbedeutend ist.
</p>
<div class="row">
	<div class="6u 12u$(small)">
		<h3>Grenzwerte für die Gesamtzahl der SARS-CoV-2-Infektionen: Der Zusammenhang zwischen Schweregrad, die Angriffsrate im Haushalt und die Zahl der unentdeckten Fälle</h3>
		<p>
		Auf der Grundlage des polnischen Monitorings von COVID 19 - einem Datensatz mit 13309 Patienten - geben wir Ober- und Untergrenzen der Altersabhängigkeit für den Prozentsatz der Menschen mit schweren Erkrankungen an. Wir korrigieren die Belastung des Sets für schwere Fälle und schätzen die unbelastete Unter- und Obergrenze der tatsächlichen Patientenzahl in Polen zum 1. Juli.
        </p>
        <p>Diese Methode kann universell in allen Ländern angewendet werden, in denen schwere Haushaltsfälle gemeldet wurden, und bietet eine umfassende Methode zur Erfassung nicht diagnostizierter COVID 19-Infektionen. Darüber hinaus geben wir eine Untergrenze für die Haushaltsinzidenzrate vor und erörtern den engen Zusammenhang zwischen der Haushaltsinzidenzrate, der Schweregradquote und der Schätzung der nicht diagnostizierten Rate.
        </p>
        <a class="button special" href="/assets/images/preprints/bounds_on_covid_infections.pdf">WEITER 🇬🇧</a>
	</div>
	<div class="6u 12u$(small)">
    		<h3>Linderungs- und Herdenimmunitätsstrategie für COVID-19 wird wahrscheinlich scheitern</h3>
    		<p>
    		Auf der Grundlage einer semi-realistischen SIR-Mikrosimulation für Deutschland und Polen zeigen wir, dass das R0-Parameterintervall, für das die COVID-19-Epidemie überkritisch bleibt, aber unter der Kapazitätsgrenze des Gesundheitssystems liegt, um Herdenimmunität zu erreichen, so eng ist, dass eine erfolgreiche Umsetzung dieser Strategie wahrscheinlich scheitern wird. Unsere Mikrosimulation basiert auf offiziellen Volkszählungsdaten und bezieht die Haushaltszusammensetzung und die Altersverteilung als Hauptvariablen der Bevölkerungsstruktur mit ein. Außenkontakte des Haushalts werden durch eine Out-Reproduktionszahl R* charakterisiert, die der einzige freie Parameter des Modells ist.
    		</p>
            <p>
            Für eine subkritische Domäne berechnen wir die Zeit bis zur Ausrottung und Prävalenz als Funktion der ursprünglichen Anzahl infizierter Individuen und R*. Für die polnische Stadt Breslau diskutieren wir auch die kombinierte Wirkung von Testabdeckung und Kontaktreduzierung. Für beide Länder schätzen wir R* für das Fortschreiten der Krankheit bis zum 20. März 2020.
            </p>
            <a class="button special" href="https://www.medrxiv.org/content/10.1101/2020.03.25.20043109v1">WEITER 🇬🇧</a>
    </div>
</div>

<hr class="major" />

<h2 id="content">Presseartikel</h2>

{% assign media = site.publications | reverse %}
<div class="posts">
{% for post in media %}	
		<article>
		    <small>{{ post.medium }}, {{ post.date  | date: "%Y-%m-%d" }}</small>
			<h3>{{ post.de_title }}</h3>
			<p>{{ post.de_desc }}</p>
			<ul class="actions">
			    {% for link in post.links %}	
                    <li><a href="{{ link.link }}" class="button">Weiter</a></li>
                {% endfor %}
            </ul>
		</article>
{% endfor %}