---
title: "Zanne Lab - Team"
layout: gridlay
excerpt: "Zanne Lab: Team members"
sitemap: false
permalink: /team/
---
# Group Members

 **Looking to join our team?** [(See openings in the lab here)]({{ site.url }}{{ site.baseurl }}/vacancies)


Jump to [our team](#our-team), [recent alumni](#recent-alumni), or [past students](#past-students).

## Our Team
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

	@@ -24,9 +23,8 @@ Jump to [our team](#our-team), [recent alumni](#recent-alumni), or [past student
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="42%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <br>email: <{{ member.email }}></i> 
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
	@@ -51,14 +49,6 @@ Jump to [our team](#our-team), [recent alumni](#recent-alumni), or [past student
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

	@@ -75,7 +65,8 @@ Jump to [our team](#our-team), [recent alumni](#recent-alumni), or [past student
</div>
{% endif %}

## Recent Alumni

{% assign number_printed = 0 %}
{% for member in site.data.alumni_members %}
	@@ -87,10 +78,9 @@ Jump to [our team](#our-team), [recent alumni](#recent-alumni), or [past student
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="42%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }} <br> Role: {{ member.info }}</i>
  <br>email: <{{ member.email }}>
  <ul style="overflow: hidden">

  </ul>
	@@ -108,15 +98,3 @@ Jump to [our team](#our-team), [recent alumni](#recent-alumni), or [past student
{% if even_odd == 1 %}
</div>
{% endif %}

## Past students
<div class="row">

<div class="col-sm-4 clearfix">
<h4>Postdocs, graduate, and undergraduate students</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
