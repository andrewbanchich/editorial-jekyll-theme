---
layout: document
lang: pl
category: analiza
date: 15.05.2020
sortable_date: 20200515
title: Ocena skuteczności strategii “Testuj, Trop, Redukuj” w  wygaszaniu epidemii
teaser: "Analiza wpływu podjęcia jednoczesnych działań w trzech kierunkach: 1) testowania (Testuj), 2) śledzenia kontaktów (Trop) i 3) redukcji kontaktów (Redukuj) na położenie krzywej krytycznej oraz rozwój epidemii."
image_teaser: /assets/images/reports/20200515/infected_fraction.png
---


<h3>Podsumowanie</h3>
<p>Szeroko zakrojone testy pozwalają zainicjować kaskadę śledzenia kontaktów u jak największej liczby pacjentów. Wysoka wykrywalność kontaktów i jak najkrótszy czas ich wyszukiwania znacząco ograniczają czas i zakres zarażania. Aplikacje śledzące, jeżeli byłyby szeroko używane przez społeczeństwo, mogłyby pozwolić na znaczne przyspieszenie śledzenia kontaktów.</p>
<p>Dla Polski, tak samo jak dla każdego innego kraju, bardzo ważna jest możliwość poluzowania restrykcji kontaktów. Analizujemy, jakich narzędzi kontroli epidemii należy użyć, aby móc mniej redukować kontakty, na przykład jedynie o  20%.  Przedstawiamy też oszacowania czasu, jaki zajmie wygaśnięcie epidemii dla różnych wartości parametru modelu.</p>

<h3>Wyniki analiz</h3>

<p>Do skutecznego zwalczenia epidemii konieczne jest połączenie redukcji kontaktów z wytężonymi działaniami w kierunku skutecznego śledzenia kontaktów i szerokiego testowania. Niski poziom redukcji kontaktów wymaga większej skuteczności działań w pozostałych dwóch kierunkach. </p>
<p>Poprawienie skuteczności wykrywania kontaktów powyżej pewnego poziomu może być trudne do osiągnięcia stosując standardowe metody. Poprawę można osiągnąć poprzez skrócenie całkowitego czasu potrzebnego na wykrycie i testowanie kontaktów tak, aby wynosił poniżej 2 dni. </p>

<div style="text-align: center" class="row 90%">
    <span class="image fit"><img src="/assets/images/reports/20200515/infected_fraction.png" style="margin-bottom: 0px;"/></span>
    <small>Końcowy odsetek zakażonych w populacji w zależności od wykrywalności przypadków o łagodnym przebiegu, niezależnej od śledzenia kontaktów, q’ (oś pozioma), skuteczności śledzenia kontaktów b (oś pionowa), oraz stopnia redukcji kontaktów społecznych (panele). Wykresy zostały wykonane dla populacji Wrocławia oraz przy założeniu, że średni czas opóźnienia d wynosi 2 dni oraz że aplikacja do śledzenia kontaktów nie jest używana (u=0).</small>
</div>

<p>Z drugiej strony, zwiększenie wykrywalności przypadków o łagodnym przebiegu może być łatwiejsze do osiągnięcia niż poprawienie skuteczności śledzenia kontaktów i może być wykonane poprzez zwiększenie zakresu testowania.</p>

<div style="text-align: center" class="row 90%">
    <span class="image fit"><img src="/assets/images/reports/20200515/time_to_extinction.png" style="margin-bottom: 0px;"/></span>
    <small>Czas do końca epidemii (do ostatniego zakażenia) w zależności od wykrywalności przypadków o łagodnym przebiegu, niezależnej od śledzenia kontaktów q’ (oś pozioma), skuteczności śledzenia kontaktów b (oś pionowa), oraz stopnia redukcji kontaktów społecznych (panele). Wykresy zostały wykonane dla populacji Wrocławia oraz przy założeniu, że średni czas opóźnienia d wynosi 2 dni oraz że aplikacja do śledzenia kontaktów nie jest używana (u=0).</small>
</div>

<p>Dodatkową poprawę skuteczności śledzenia kontaktów można uzyskać stosując aplikację do śledzenia kontaktów. </p>

<div style="text-align: center" class="row 90%">
    <span class="image fit"><img src="/assets/images/reports/20200515/infected_fraction_mobileapp.png" style="display: block; margin: 0 auto;"/></span>
    <small>Końcowy odsetek zakażonych w populacji w zależności od stopnia redukcji kontaktów f, od części populacji używającej aplikacji u, oraz od dodatkowej wykrywalności lekkich przypadków q’. Wykresy zostały wykonane dla populacji Wrocławia przy założeniu, że opóźnienie śledzenia kontaktów dla nieużywających aplikacji wynosi 2 dni a dla używających 0.5 dnia, zaś  wartość prawdopodobieństwa wykrycia kontaktów wynosi b=0.6. </small>
</div>

<p>Czas do końca epidemii w największym stopniu zależy od odległości od linii krytycznej. W stanie podkrytycznym, przy większej odległości od linii krytycznej, może wynosić kilka miesięcy a przy pozostaniu na linii krytycznej epidemia będzie trwać wiele lat.</p>

<div style="text-align: center" class="row 90%">
    <span class="image fit"><img src="/assets/images/reports/20200515/time_to_extinction_mobileapp.png" style="margin-bottom: 0px;"/></span>
    <small>Średni czas do końca epidemii (do ostatniego zakażenia) w zależności od stopnia redukcji kontaktów f, od części populacji używającej aplikacji u, oraz od dodatkowej wykrywalności lekkich przypadków q’. Wykresy zostały wykonane dla populacji Wrocławia przy założeniu, że opóźnienie śledzenia kontaktów dla nieużywających aplikacji wynosi 2 dni a dla używających 0.5 dnia, zaś  wartość prawdopodobieństwa wykrycia kontaktów wynosi b=0.6.</small>
</div>

<p>Testowanie i izolowanie przypadków o łagodnym przebiegu (dodatkowo do przypadków wykrytych przy śledzeniu kontaktów osób zakażonych) jest bardzo skutecznym narzędziem w walce z epidemią. Przykładowo, dla dodatkowej wykrywalności przypadków o łagodnym przebiegu q’ na poziomie 0.5, w przypadku gdyby cała, bądź prawie cała populacja korzystałaby z aplikacji śledzącej, nie byłoby konieczności redukcji kontaktów. Uwzględniając fakt, że ok. 70% mieszkańców Polski korzysta ze smartfonów, oznacza to, że co najmniej 70% spośród nich musiałoby mi mieć zainstalowaną aplikację.</p>