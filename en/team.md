---
layout: page
lang: pl
title: The MOCOS Team
---
<p>The MOCOS Group (MOdelling COronavirus Spread) is an international, interdisciplinary team of scientists involved in modelling the COVID-19 epidemic.</p>

<div class="row">
{% for staff_member in site.people %}
{% assign mod = forloop.index | modulo: 3 %}
<div class="4u 12u$(medium) member">
    <span class="image">
        <img src="../assets/images/team/{{ staff_member.img_name }}" alt="{{ staff_member.en_author_name }}" />
        <h3>{{ staff_member.en_author_name }}</h3>
        <small>{{ staff_member.en_mocos_part }}</small>    
    </span>
  	{{ staff_member.en_descriptions }}
</div>
{% if forloop.index > 1 and mod == 0 %}</div><div class="row">{% endif %}
{% endfor %}
</div>