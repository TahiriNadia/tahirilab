---
title: "Tahiri Lab - Team"
layout: gridlay
excerpt: "Tahiri Lab: Team members"
sitemap: false
permalink: /team/
---

# Group Members

 **We are  looking for new PhD students, Postdocs, and Master's students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/openings) **!**


Jump to [Principal Investigator](#principal-investigator), [Collaborators](#collaborators), [PhD Students](#phd-students), [Master Students](#master-students), [Interns Students](#interns-students), [Alumni](#alumni), [Administrative support](#administrative-support).

## Principal Investigator
*****
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="200px" height="200px" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li style="list-style: none;"> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li style="list-style: none;"> {{ member.education1 }} </li>
  <li style="list-style: none;"> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li style="list-style: none;"> {{ member.education1 }} </li>
  <li style="list-style: none;"> {{ member.education2 }} </li>
  <li style="list-style: none;"> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li style="list-style: none;"> {{ member.education1 }} </li>
  <li style="list-style: none;"> {{ member.education2 }} </li>
  <li style="list-style: none;"> {{ member.education3 }} </li>
  <li style="list-style: none;"> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li style="list-style: none;"> {{ member.education1 }} </li>
  <li style="list-style: none;"> {{ member.education2 }} </li>
  <li style="list-style: none;"> {{ member.education3 }} </li>
  <li style="list-style: none;"> {{ member.education4 }} </li>
  <li style="list-style: none;"> {{ member.education5 }} </li>
  {% endif %}
   
   <br>
   
  {% if member.number_fellow == 2 %}
  <li> {{ member.fellow1 }} </li>
  <li> {{ member.fellow2 }} </li>
  {% endif %}
    
  {% if member.number_fellow == 3 %}
  <li style="list-style: none;"> {{ member.fellow1 }} </li>
  <li style="list-style: none;"> {{ member.fellow2 }} </li>
  <li style="list-style: none;"> {{ member.fellow3 }} </li>
  {% endif %}

    
  {% if member.number_fellow == 4 %}
  <li style="list-style: none;"> {{ member.fellow1 }} </li>
  <li style="list-style: none;"> {{ member.fellow2 }} </li>
  <li style="list-style: none;"> {{ member.fellow3 }} </li>
  <li style="list-style: none;"> {{ member.fellow4 }} </li>
  {% endif %}
    
  {% if member.number_fellow == 5 %}
  <li style="list-style: none;"> {{ member.fellow1 }} </li>
  <li style="list-style: none;"> {{ member.fellow2 }} </li>
  <li style="list-style: none;"> {{ member.fellow3 }} </li>
  <li style="list-style: none;"> {{ member.fellow4 }} </li>
  <li style="list-style: none;"> {{ member.fellow5 }} </li>
  {% endif %}
  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<!--
## Collaborators
*****
{% assign number_printed = 0 %}
{% for member in site.data.collaborator %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="11%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <br>email: <{{ member.email }}></i> 
  <ul style="overflow: hidden"> 

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
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

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
-->

## PhD Students
*****
{% assign number_printed = 0 %}
{% for member in site.data.phd %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="150px" height="150px" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  <br>
   
  {% if member.number_fellow == 2 %}
  <li> {{ member.fellow1 }} </li>
  <li> {{ member.fellow2 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %} 

## Master's Students
*****
{% assign number_printed = 0 %}
{% for member in site.data.master %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

 
<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="150px" height="150px" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  <br>
   
  {% if member.number_fellow == 2 %}
  <li> {{ member.fellow1 }} </li>
  <li> {{ member.fellow2 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Interns Students
*****
{% assign number_printed = 0 %}
{% for member in site.data.bachelor %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="150px" height="150px" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
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

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Alumni
*****
{% assign number_printed = 0 %}
{% for member in site.data.alumni_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="150px" height="150px" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }} <br> Role: {{ member.info }}</i>
  <ul style="overflow: hidden">

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

### Former visitors, BSc/ MSc students
<div class="row">

<div class="col-sm-3 clearfix">
<h4>Visitors / Interns</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-3 clearfix">
<h4>PhD students</h4>
{% for member in site.data.alumni_phd %}
{{ member.name }}
{% endfor %}
</div>
  
<div class="col-sm-3 clearfix">
<h4>Master's students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-3 clearfix">
<h4>Bachelor's Students</h4>
{% for member in site.data.alumni_bsc %}
{{ member.name }}
{% endfor %}
</div>

</div>


## Administrative Support
<a href="mailto:nadia.tahiri@gmail.com">Nadia Tahiri</a> is helping us (and other groups) with administration.
