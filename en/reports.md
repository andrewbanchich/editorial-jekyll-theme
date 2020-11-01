---
layout: page
lang: en
title: Reports
---

{% assign media = site.reports | reverse %}
<div class="posts">
{% for post in media %}	
		<article>
		    <small>{{ post.date  | date: "%Y-%m-%d" }}</small>
			<h3>{{ post.en_title }}</h3>
			<p>{{ post.en_desc }}</p>
			<ul class="actions">
			    {% for link in post.links %}	
                    <li><a href="{{ link.link }}" class="button">{{ link.type }}</a></li>
                {% endfor %}
            </ul>
		</article>
{% endfor %}