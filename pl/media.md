---
layout: page
lang: pl
title: Nasze Publikacje
---

<h2 id="content">Publikacje Naukowe</h2>
<p>Naszym celem jest wsparcie instytucji publicznych w sprowadzeniu epidemii
 do stanu wygasania (podkrytycznego), tj. obniżenia skali reprodukcji wirusa 
 do poziomu nieistotnego z punktu widzenia bezpieczeństwa publicznego.</p>
<div class="row">
	<div class="6u 12u$(small)">
		<h3>Bounds on the total number of SARS-CoV-2 infections: The link between severeness rate, household attack rate and the number of  undetected cases</h3>
		<p>
		Na podstawie polskiego monitoringu COVID 19 - zbioru danych 13309 pacjentów
		podajemy górne i dolne granice zależności od wieku dla odsetka osób z ciężkim przebiegiem choroby.
		Dokonujemy korekcji obciążenia zbioru w kierunku poważnych przypadków i estymujemy nieobciążone
		ograniczenia dolne i górne prawdziwej liczby chorych w Polsce na dzień 1 lipca.
		</p>
        <p>Metoda ta może być stosowana uniwersalnie we wszystkich krajach, w których odnotowano poważne przypadki 
        w gospodarstwach domowych i zapewnia sposób szacowania niezdiagnozowanych infekcji COVID 19.
        Ponadto podajemy dolną granicę wskaźnika zachorowalności gospodarstw domowych oraz
        omówić ścisłą zależność między wskaźnikiem zaatakowania gospodarstwa domowego, wskaźnikiem ciężkości
        przebiegu choroby i oszacowania odsetka osób niezdiagnozowanych.
        </p>
        <a class="button special" href="/assets/images/preprints/bounds_on_covid_infections.pdf">PRZECZYTAJ 🇬🇧</a>
	</div>
	<div class="6u 12u$(small)">
    		<h3>Mitigation and herd immunity strategy for COVID-19 is likely to fail</h3>
    		<p>
    		Na podstawie semi-realistycznej mikrosymulacji SIR dla Niemiec i Polski pokazujemy, że
            przedział parametrów R0, dla którego epidemia COVID-19 pozostaje w stanie nadkrytycznym,
            ale poniżej granicy możliwości systemu opieki zdrowotnej, aby możliwe było osiągnięcie
            odporności stadnej, jest tak wąski, że pomyślna realizacja tej strategii nie jest
            prawdopodobna. Nasza mikrosymulacja opiera się na oficjalnych danych ze spisu
            powszechnego i obejmuje skład gospodarstw domowych oraz rozkład wieku jako główne
            zmienne struktury populacji. Kontakty zewnętrzne z gospodarstwami domowymi
            charakteryzujemy się wskaźnikiem reprodukcji R*, który jest jedynym swobodnym parametrem
            modelu.
    		</p>
            <p>
            Dla domeny subkrytycznej obliczamy czas do wyginięcia i chorobowość w funkcji początkowej
            liczby osób zakażonych i R*. Dla polskiego miasta Wrocławia omawiamy również łączny
            wpływ zasięgu testów i redukcji kontaktów. Dla obu krajów szacujemy R* dla progresji
            choroby do 20 marca 2020 roku.
            </p>
            <a class="button special" href="https://www.medrxiv.org/content/10.1101/2020.03.25.20043109v1">PRZECZYTAJ 🇬🇧</a>
    </div>
</div>

<hr class="major" />

<h2 id="content">Wypowiedzi medialne</h2>

{% assign media = site.publications | reverse %}
<div class="posts">
{% for post in media %}	
		<article>
		    <small>{{ post.medium }}, {{ post.date  | date: "%Y-%m-%d" }}</small>
			<h3>{{ post.pl_title }}</h3>
			<p>{{ post.pl_desc }}</p>
			<ul class="actions">
			    {% for link in post.links %}	
                    <li><a href="{{ link.link }}" class="button">Więcej</a></li>
                {% endfor %}
            </ul>
		</article>
{% endfor %}