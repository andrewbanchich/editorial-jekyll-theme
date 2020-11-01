---
layout: document
lang: de
category: analysis
date: 15.05.2020
sortable_date: 20200515
title: Bewertung der Wirksamkeit der Strategie "Testen, Verfolgen, Reduzieren" zur Ausrottung der Epidemie
teaser: "Analyse der Auswirkungen von gleichzeitigen Aktionen in drei Richtungen: 1) Testen, 2) Kontaktverfolgung
                                     und 3) Kontaktverringerung (Reduzieren) auf die Lage der kritischen Kurve und die Entwicklung der
                                     Epidemie. Umfassende Tests ermöglichen es, eine Kaskade der Kontaktverfolgung bei möglichst vielen
                                     Patienten einzuleiten. Eine hohe Kontakterkennung und die kürzestmögliche Kontaktsuchzeit reduzieren
                                     den Zeitpunkt und das Ausmaß der Infektion erheblich. Tracking-Anwendungen könnten, wenn sie von der
                                     Öffentlichkeit umfassend genutzt werden, die Ermittlung von Kontaktpersonen erheblich beschleunigen."
image_teaser: /assets/images/reports/20200515/infected_fraction.png
---


<h3>Zusammenfassung</h3>
<p>Für Polen, wie für jedes andere Land auch, ist es sehr wichtig, die Beschränkungen für Kontakte lockern zu
    können. Wir analysieren, welche Instrumente der Virenbekämpfung eingesetzt werden sollten, um die
    Kontakte weniger zu reduzieren, zum Beispiel um nur 20%.  Wir bieten auch Schätzungen der Zeit, die
    für verschiedene Werte des Modellparameters bis zum Ablauf einer Epidemie benötigt wird.</p>

<h3>Analyseergebnisse</h3>

<p>Um die Epidemie wirksam bekämpfen zu können, ist es notwendig, die Kontaktreduzierung mit intensiven Bemühungen
    um eine effektive Kontaktverfolgung und umfangreiche Tests zu verbinden. Ein geringes Maß an Kontaktreduzierung
    erfordert wirksamere Maßnahmen in den beiden anderen Richtungen.</p>
<p>Die Verbesserung der Kontakterkennung über ein bestimmtes Niveau hinaus kann mit Standardmethoden schwierig
    zu erreichen sein. Die Verbesserung kann erreicht werden, indem die Gesamtzeit für die Erkennung und Prüfung
    von Kontakten auf weniger als 2 Tage reduziert wird. </p>
<div style="text-align: center">
    <img src="/assets/images/reports/20200515/infected_fraction.png" style="margin-bottom: 0px;"/>
    <small>Endgültiger Prozentsatz der infizierten Bevölkerung in Abhängigkeit von der Erkennung milder, kontaktunabhängiger
        Fälle, q' (horizontale Achse), der Wirksamkeit der Kontaktverfolgung b (vertikale Achse) und dem Grad
        der Reduzierung sozialer Kontakte (Panels). Die Diagramme wurden für die Bevölkerung von Wrocław und
        unter der Annahme erstellt, dass die durchschnittliche Verzögerungszeit d 2 Tage beträgt und dass
        die mobile Anwendung zur Kontaktverfolgung nicht verwendet wird (u=0).</small>
</div>

<p>Auf der anderen Seite kann eine Erhöhung der Erkennung leichterer Fälle einfacher erreicht werden als eine
    Verbesserung der Kontaktverfolgung und kann durch eine Erweiterung des Testumfangs erreicht werden.</p>
<div style="text-align: center">
    <img src="/assets/images/reports/20200515/time_to_extinction.png" style="margin-bottom: 0px;"/>
    <small>Zeit bis zum Ende der Epidemie (bis zur letzten Infektion) in Abhängigkeit vom Nachweis leichter
        Fälle, unabhängig von der Ermittlung von Kontaktpersonen q' (horizontale Achse), der Wirksamkeit der
        Ermittlung von Kontaktpersonen b (vertikale Achse) und dem Grad der Verringerung sozialer Kontakte (Panels).
        Die Diagramme wurden für die Bevölkerung von Wrocław und unter der Annahme erstellt, dass die
        durchschnittliche Verzögerungszeit d 2 Tage beträgt und dass die mobile Anwendung zur Kontaktverfolgung
        nicht verwendet wird (u=0).</small>
</div>

<p>Die Effizienz der Kontaktverfolgung kann weiter verbessert werden, indem die mobile Anwendung zur Kontaktverfolgung verwendet wird. </p>

<div style="text-align: center">
    <img src="/assets/images/reports/20200515/infected_fraction_mobileapp.png" style="display: block; margin: 0 auto;"/>
    <small>Der endgültige Prozentsatz der infizierten Bevölkerung in Abhängigkeit vom Grad der Kontaktreduktion f,
        von dem Teil der Bevölkerung, der die mobile Anwendung u verwendet, und von der zusätzlichen Erkennung von
        leichten Fällen q'. Die Diagramme wurden für die Population von Wrocław unter der Annahme erstellt,
        dass die Verzögerung der Ermittlung von Kontaktpersonen für Nicht-Benutzer 2 Tage und für diejenigen, die
        die Anwendung nutzen, 0,5 Tage beträgt und die Wahrscheinlichkeit der Kontakterkennung b=0,6 ist.</small>
</div>

<p>Die Zeit bis zum Ende der Epidemie hängt am stärksten von der Entfernung von der kritischen Linie ab.
    Im subkritischen Zustand, mit einem größeren Abstand von der kritischen Linie, kann es mehrere Monate
    dauern, und wenn wir an der kritischen Linie bleiben, wird die Epidemie viele Jahre andauern.</p>
<div style="text-align: center">
    <img src="/assets/images/reports/20200515/time_to_extinction_mobileapp.png" style="margin-bottom: 0px;"/>
    <small>Durchschnittliche Zeit bis zum Ende der Epidemie (bis zur letzten Infektion) in Abhängigkeit vom
        Grad der Kontaktreduktion f, dem Teil der Bevölkerung, der die mobile Anwendung u verwendet, und dem
        zusätzlichen Nachweis von leichten Fällen q'. Die Diagramme wurden für die Population von Wrocław
        unter der Annahme erstellt, dass die Verzögerung bei der Ermittlung von Kontaktpersonen für
        Nicht-Benutzer 2 Tage und für Benutzer 0,5 Tagen beträgt und die Wahrscheinlichkeit der Kontakterkennung
        b=0,6 ist.</small>
</div>
<p>Das Testen und Isolieren von Fällen mit einem milden Verlauf (zusätzlich zu den Fällen, die bei der
    Rückverfolgung der Kontakte infizierter Personen festgestellt werden) ist ein sehr wirksames Mittel zur
    Bekämpfung der Epidemie. Würde z.B. die gesamte oder fast die gesamte Bevölkerung die Tracking-Anwendung für
    die zusätzliche Erkennung von leichten Fällen q' bei 0,5 verwenden, wäre es nicht notwendig, die Kontakte
    zu reduzieren. Berücksichtigt man die Tatsache, dass etwa 70% der polnischen Bevölkerung Smartphones
    benutzen, bedeutet dies, dass mindestens 70% von ihnen die Anwendung installiert haben müssten.</p>