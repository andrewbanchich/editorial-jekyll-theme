---
layout: page
lang: en
title: Publications & Media
---

<h2 id="content">Scientific Publications</h2>
<p>Our goal is to support public institutions in bringing the epidemic to a state of extinction (sub-critical), i.e. to reduce the scale of virus reproduction to a level that is insignificant from the point of view of public safety.
   </p>
<div class="row">
	<div class="6u 12u$(small)">
		<h3>Bounds on the total number of SARS-CoV-2 infections: The link between severeness rate, household attack rate and the number of  undetected cases</h3>
		<p>
		Based on the Polish monitoring of COVID 19 - a set of 13309 patients
        We give the upper and lower limits of age dependence for the percentage of people with severe disease.
        We correct the collection load for serious cases and estimate the unloaded
        Lower and upper limits of the real number of patients in Poland as of 1 July.
		</p>
        <a class="button special" href="/assets/images/preprints/bounds_on_covid_infections.pdf">More 🇬🇧</a>
	</div>
	<div class="6u 12u$(small)">
    		<h3>Mitigation and herd immunity strategy for COVID-19 is likely to fail</h3>
    		<p>
    		On the basis of a semi-realistic SIR microsimulation for Germany and Poland, we show that the R0 parameter interval for which the COVID-19 epidemic stays overcritical but below the capacity limit of the health care system to reach herd immunity is so narrow that a successful implementation of this strategy is likely to fail. Our microsimulation is based on official census data and involves household composition and age distribution as the main population structure variables. Outside household contacts are characterised by an out-reproduction number R* which is the only free parameter of the model.
    		</p>
            <p>
For a subcritical domain we compute the time till extinction and prevalence as a function of the initial number of infected individuals and R*. For the Polish city of Wroclaw we also discuss the combined impact of testing coverage and contact reduction. For both countries we estimate R* for disease progression until 20th of March 2020.
            </p>
            <a class="button special" href="https://www.medrxiv.org/content/10.1101/2020.03.25.20043109v1">More 🇬🇧</a>
    </div>
</div>

<hr class="major" />

<h2 id="content">Press Coverage</h2>

{% assign media = site.publications | reverse %}
<div class="posts">
{% for post in media %}	
		<article>
		    <small>{{ post.medium }}, {{ post.date  | date: "%Y-%m-%d" }}</small>
			<h3>{{ post.pl_title }}</h3>
			<p>{{ post.pl_desc }}</p>
			<ul class="actions">
			    {% for link in post.links %}	
                    <li><a href="{{ link.link }}" class="button">More</a></li>
                {% endfor %}
            </ul>
		</article>
{% endfor %}