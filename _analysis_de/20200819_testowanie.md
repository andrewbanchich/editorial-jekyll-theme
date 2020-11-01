---
layout: document
lang: de
category: analysis
date: 31.10.2020
sortable_date: 20201031
title: Simulationen der Auswirkungen von Tests und Anwendung zur Eindämmung der Epidemie in Polen
teaser: Die Auswirkungen der verstärkten Erkennung von leichten Fällen und des Einsatzes von mobilen Anwendungen zur Ermittlung von Kontaktpersonen auf den endgültigen Prozentsatz der infizierten Bevölkerung, basierend auf der simulierten Bevölkerung von Wrocław.
image_teaser: /assets/images/reports/20200819/b_vs_c_q03_d1+1.svg
---

<p>Parameter, die einen entscheidenden Einfluss auf die gesamte (endgültige) Zahl der Infizierten haben, sind:</p>
<ul style="padding-left: 40px">
    <li>leichtlaufende Fallerkennung, unabhängig von der Kontaktverfolgung - die Säule "Testen",</li>
    <li>die Wirksamkeit der Kontaktverfolgung - die Säule "Zurückverfolgen",</li>
    <li>der Grad der Kontaktreduzierung, ausgedrückt als "um x%" im Verhältnis zur Anzahl der Mitte März
        beobachteten Kontakte - Säule "Reduzieren".</li>
</ul>

<p>Die folgende Heatmap stellt die Auswirkungen der Kontaktverfolgungseffizienz und Kontaktreduzierung
    auf den endgültigen Prozentsatz der infizierten Bevölkerung dar.</p>

<div style="text-align: center">
    <img src="/assets/images/reports/20200819/b_vs_c_q03_d1+1.svg" style="display: block; margin: 0 auto;"/>
    <small>Abb.1: Endgültiger Prozentsatz der infizierten Bevölkerung für verschiedene Grade der Kontaktreduktion
        und Effizienz der Kontaktverfolgung mit Erkennung leichter Fälle bei 30% und einer Verzögerung der
        Kontaktverfolgung von 2 Tagen. Berechnungen für die Bevölkerung von Wrocław unter der Annahme, dass die
        berücksichtigten Parameter im Laufe der Zeit konstant bleiben.</small>
</div>

<hr />
<h3>Richtung der Veränderung: verstärkte Erkennung von Fällen mit leichtem Verlauf</h3>

<p>Der Nachweis von leichten Fällen, unabhängig von der Ermittlung von Kontaktpersonen, hängt stark davon ab,
    wie umfangreich die Tests auf Coronaviren in der Bevölkerung sind. Die Auswirkung dieser Wirksamkeit
    auf den endgültigen Prozentsatz der infizierten Bevölkerung kann beurteilt werden, indem man die Größe
    der gelb-roten Bereiche in Abb.1 (30% Entdeckungsrate) und Abb.2 (60% Entdeckungsrate) vergleicht,
    d.h. Bereiche, die 5 oder mehr Prozent der infizierten Bevölkerung entsprechen.</p>
<div style="text-align: center">
    <img src="/assets/images/reports/20200819/b_vs_c_q06_d1+1.svg" style="display: block; margin: 0 auto;"/>
    <small>Abb.2: Endgültiger Prozentsatz der infizierten Bevölkerung für verschiedene Grade der Kontaktreduktion
        und Effizienz der Kontaktverfolgung mit Erkennung leichter Fälle bei 60% und einer Verzögerung der Kontaktverfolgung
        von 2 Tagen. Berechnungen, die an der Population von Wrocław durchgeführt wurden, unter der Annahme,
        dass die berücksichtigten Parameter im Laufe der Zeit konstant bleiben.</small>
</div>
<p>Der gelb-rote Bereich entspricht einer Epidemie in einem überkritischen Zustand, d.h. mit einer ständig
    steigenden Zahl von neuen Fällen pro Zeiteinheit. Eine verbesserte Nachweisbarkeit von leichten Fällen
    ist daher eine Richtung der Veränderung, die den Prozentsatz der COVID-19-infizierten Bevölkerung deutlich
    reduzieren könnte.</p>
<hr />
<h3>Richtung des Wandels: Verbesserung der Kontaktverfolgung</h3>

<p>Das Verfahren zur Ermittlung von Kontaktpersonen wird sowohl zur Identifizierung der Infektionsquelle (rückwärts)
    als auch zur Identifizierung weiterer Personen, die sich möglicherweise infiziert haben (vorwärts),
    durchgeführt. Das Verfahren wird in Kaskade für Kontakte wiederholt, die in jedem vorherigen Schritt
    erkannt wurden, und die Verzögerung zwischen den nachfolgenden Verfolgungsschritten wird <b>Verfolgungsverzögerung</b>
    genannt. Wir gehen davon aus, dass die Nachverfolgung von Kontakten aus zwei Phasen besteht: 1) Kontakte
    zu finden und in Quarantäne zu stellen und 2) Tests durchzuführen, und für jede dieser Phasen gibt es die
    Hälfte der Verzögerungszeit. Nach erfolgreicher Entdeckung wird der Prozess wiederholt, um weitere
    Kontakte zu finden. Die Wahrscheinlichkeit, jede Person, mit der die infizierte Person Kontakt hatte,
    zu identifizieren und zu erreichen, wird mit <i>b</i> gekennzeichnet und als Wahrscheinlichkeit der
    Erkennung von Kontakten bezeichnet.</p>


<p>Die Effizienz der Kontaktverfolgung kann verbessert werden, indem die mobilen Anwendungen zur Kontaktverfolgung
    verwendet werden. Wir gehen hier für das Land von realistischen Werten der Detektion von leichten Fällen
    auf dem Niveau von 30% und der Effektivität der klassischen (Standardverfahren, ohne Einsatz der Applikation)
    Kontaktverfolgung auf dem Niveau von 60% aus (siehe Abb. 1).</p>

<div style="text-align: center">
    <img src="/assets/images/reports/20200819/u_vs_c_b06_q03_d1+1.svg" style="display: block; margin: 0 auto;"/>
    <small>Abb.3: Endgültiger Prozentsatz der infizierten Bevölkerung für verschiedene Grade der Kontaktverringerung
        und verschiedene Grade der Verbreitung von mobilen Anwendungen zur Ermittlung von Kontaktpersonen mit einer
        Wirksamkeit der klassischen Ermittlung von Kontaktpersonen in Höhe von 60 %, Erkennung leichter Fälle
        in Höhe von 30 % und Verzögerung der Ermittlung von Kontaktpersonen um 2 Tage (mit der mobilen
        Anwendung oder klassisch). Berechnungen, die an der Population von Wrocław durchgeführt wurden, unter
        der Annahme, dass die berücksichtigten Parameter im Laufe der Zeit konstant bleiben.</small>
</div>

<p>Wenn mindestens die Hälfte der Bevölkerung die mobile Anwendung zur Verfolgung von Kontakten nutzen würde, wären
    die Auswirkungen einer solchen Anwendung auf die epidemiologische Situation im Land spürbar: Mit steigendem
    Prozentsatz der Bevölkerung, die die Anwendung nutzt, verschiebt sich die Grenze des gelb-roten Bereichs nach
    rechts, so dass wir uns mehr Freiheit für soziale Kontakte ohne negative Auswirkungen auf die epidemiologische
    Situation leisten könnten.</p>
<p>Die vorgestellten Heatmaps stellen eine Situation dar, in der die Werte der Parameter während der gesamten
    Dauer der Epidemie unverändert bleiben. Natürlich ändern sich diese Werte in der realen Welt ständig.
    Die Karten haben daher illustrativen Charakter und dienen dazu, die Auswirkungen des Antrags auf die
    epidemiologische Situation im Land darzustellen. </p>