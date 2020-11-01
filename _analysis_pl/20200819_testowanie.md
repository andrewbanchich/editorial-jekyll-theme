---
layout: document
lang: pl
category: analiza
date: 31.10.2020
sortable_date: 20201031
title: Symulacje wpływu testowania oraz użycia aplikacji na powstrzymanie epidemii w Polsce
teaser: Wpływ zwiększonej wykrywalności przypadków o lekkim przebiegu oraz użycia aplikacji do śledzenia kontaktów na końcowy odsetek procentowy zakażonych w populacji, na przykładzie symulowanej populacji Wrocławia.
image_teaser: /assets/images/reports/20200819/b_vs_c_q03_d1+1.svg
---

<p>Parametrami mającymi kluczowy wpływ na łączną (końcową) liczbę zakażonych są: </p>
<ul style="padding-left: 40px">
    <li>wykrywalność przypadków o lekkim przebiegu, niezależna od śledzenia kontaktów - filar "Testuj",</li>
    <li>skuteczności śledzenia kontaktów - filar "Trop",</li>
    <li>stopień ograniczenia kontaktów, wyrażony jako "o x%" względem ilości kontaktów obserwowanych w połowie marca - filar "Redukuj".</li>
</ul>

<p>Na poniższej mapie cieplnej prezentujemy wpływ skuteczności śledzenia kontaktów oraz stopnia ograniczenia kontaktów na końcowy odsetek procentowy zakażonych w populacji. </p>

<div style="text-align: center" class="row 90%">
    <span class="image fit">
        <img src="/assets/images/reports/20200819/b_vs_c_q03_d1+1.svg" style="display: block; margin: 0 auto;"/>
    </span>
    <small>Rys.1. Końcowy odsetek procentowy zakażonych w populacji dla różnych stopni ograniczenia kontaktów i skuteczności śledzenia kontaktów przy wykrywalności lekkich przypadków na poziomie 30% oraz opóźnieniu śledzenia kontaktów równych 2 dni. Obliczenia przeprowadzone na populacji Wrocławia przy założeniu, że uwzględnione parametry będa stałe w czasie.</small>
</div>

<hr />
<h3>Kierunek zmian: zwiększona wykrywalność przypadków o lekkim przebiegu</h3>

<p>Wykrywalność przypadków o lekkim przebiegu, niezależna od śledzenia kontaktów, jest silnie powiązana z tym, jak szeroko zakrojone jest testowanie populacji na obecność koronawirusa. Wpływ tej skuteczności na końcowy odsetek procentowy zakażonych w populacji można ocenić porównując wielkość obszarów żółto-czerwonych na Rys.1 (wykrywalność na poziomie 30%) i na Rys.2 (wykrywalność na poziomie 60%), tj. obszarów odpowiadających 5 lub więcej procentom zakażonych w populacji.</p>
<div style="text-align: center" class="row 90%">
    <span class="image fit">
        <img src="/assets/images/reports/20200819/b_vs_c_q06_d1+1.svg" style="display: block; margin: 0 auto;"/>
    </span>
    <small>Rys.2. Końcowy odsetek procentowy zakażonych w populacji dla różnych stopni ograniczenia kontaktów i skuteczności śledzenia kontaktów przy wykrywalności lekkich przypadków na poziomie 60% oraz opóźnieniu śledzenia kontaktów równych 2 dni. Obliczenia przeprowadzone na populacji Wrocławia przy, założeniu że uwzględnione parametry będa stałe w czasie.</small>
</div>

<p>Obszar żółto-czerwony odpowiada epidemii w stanie nad-krytycznym, tzn. o stale wzrastającej liczbie nowych zachorowań w jednostce czasu. Zwiększona wykrywalność przypadków o lekkim przebiegu jest zatem kierunkiem zmian, który mógłby istotnie zmniejszyć odsetek populacji zakażonej COVID-19.</p>


<h3>Kierunek zmian: poprawa skuteczności śledzenia kontaktów</h3>

<p>Procedura śledzenia kontaktów jest przeprowadzana zarówno w celu zidentyfikowania źródła zakażenia (wstecz), jak i dalszych osób, które potencjalnie mogły się zakazić (w przód). Procedura powtarzana jest kaskadowo dla kontaktów wykrytych w każdym poprzednim kroku, a opóźnienie pomiędzy kolejnymi krokami śledzenia jest nazywane <b>opóźnieniem śledzenia</b>. Przyjmujemy, że śledzenie kontaktów składa się z dwóch etapów: 1) znalezienia kontaktów i poddania ich domostw kwarantannie oraz 2) przeprowadzenie testów, a na każdy z tych etapów przypada połowa czasu opóźnienia. Po udanym wykryciu proces jest powtarzany w celu znalezienia kontaktów dalszego rzędu. Prawdopodobieństwo zidentyfikowania i dotarcia do każdej osoby, z którą zakażony miał kontakt oznaczamy przez <i>b</i> i nazywamy prawdopodobieństwem wykrycia kontaktów. </p>


<p>Poprawę skuteczności śledzenia kontaktów można uzyskać stosując aplikację do śledzenia kontaktów. Przyjmujemy tutaj realistyczne dla kraju wartości wykrywalności lekkich przypadków na poziomie 30% oraz skuteczności klasycznego (standardowymi procedurami, bez użycia aplikacji) śledzenia kontaktów na poziomie 60% (por. Rys. 1). </p>

<div style="text-align: center" class="row 90%">
    <span class="image fit">
        <img src="/assets/images/reports/20200819/u_vs_c_b06_q03_d1+1.svg" style="display: block; margin: 0 auto;"/>
    </span>
    <small>Rys.3. Końcowy odsetek procentowy zakażonych w populacji dla różnych stopni ograniczenia kontaktów i różnego stopnia upowszechnienia aplikacji do śledzenia kontaktów przy skuteczności klasycznego śledzenia kontaktów na poziomie 60%, wykrywalności lekkich przypadków na poziomie 30% oraz opóźnieniu śledzenia kontaktów równych 2 dni (za pomocą aplikacji lub klasycznie). Obliczenia przeprowadzone na populacji Wrocławia przy założeniu, że uwzględnione parametry będa stałe w czasie.</small>
</div>

<p>Jeżeli co najmniej połowa populacji używałaby aplikacji do śledzenia kontaktów, wpływ takiej aplikacji na sytuację epidemiologiczną w kraju byłby zauważalny: wraz ze wzrostem odsetka ludności używającej aplikacji następuje przesunięcie granicy obszaru żółto-czerwonego w prawo, czyli moglibyśmy sobie pozwolić na większą swobodę kontaktów społecznych bez negatywnego wpływu na sytuację epidemiologiczną.</p>
<p>Przedstawione mapy cieplne reprezentują sytuację, w której wartości parametrów pozostają niezmienne przez cały czas trwania epidemii. Oczywiście, w świecie rzeczywistym te wartości ulegają ciągłym zmianom. Mapy mają zatem charakter poglądowy i służą zaprezentowaniu wpływu stosowania aplikacji na sytuację epidemiologiczną w kraju. </p>
