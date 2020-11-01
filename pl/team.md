---
layout: page
lang: pl
title: Zespół MOCOS
---
<p>Grupa MOCOS (MOdelling COronavirus Spread) to międzynarodowy interdyscyplinarny zespół naukowców zajmujący się modelowaniem epidemii COVID-19.</p>

<div class="row">
{% for staff_member in site.people %}
{% assign mod = forloop.index | modulo: 3 %}
<div class="4u 12u$(medium) member">
    <span class="image">
        <img src="../assets/images/team/{{ staff_member.img_name }}" alt="{{ staff_member.pl_author_name }}" />
        <h3>{{ staff_member.pl_author_name }}</h3>
        <small>{{ staff_member.pl_mocos_part }}</small>    
    </span>
  	{{ staff_member.pl_descriptions }}
</div>
{% if forloop.index > 1 and mod == 0 %}</div><div class="row">{% endif %}
{% endfor %}
</div>