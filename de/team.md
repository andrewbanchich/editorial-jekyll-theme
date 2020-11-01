---
layout: page
lang: de
title: Zespół MOCOS
---
<p>Die MOCOS-Gruppe (MOdelling COronavirus Spread) ist ein internationales, interdisziplinäres Team von Wissenschaftlern, die an der Modellierung der COVID-19-Epidemie beteiligt sind.</p>

<div class="row">
{% for staff_member in site.people %}
{% assign mod = forloop.index | modulo: 3 %}
<div class="4u 12u$(medium) member">
    <span class="image">
        <img src="../assets/images/team/{{ staff_member.img_name }}" alt="{{ staff_member.de_author_name }}" />
        <h3>{{ staff_member.de_author_name }}</h3>
        <small>{{ staff_member.de_mocos_part }}</small>    
    </span>
  	{{ staff_member.de_descriptions }}
</div>
{% if forloop.index > 1 and mod == 0 %}</div><div class="row">{% endif %}
{% endfor %}
</div>