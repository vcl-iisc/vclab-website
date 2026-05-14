---
title: "VCLab - Team"
layout: gridlay
excerpt: "VCLab: Team members"
sitemap: false
permalink: /team/
---

# Group Members

 **We are looking for new PostDocs, PhD students, Master students, Project Assistants and Interns to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/openings) **!**


##### Jump to [Convenor](#lab-head), [PostDocs](#postdocs), [PhD/Masters student](#phd-masters-student), [Research Project Assistants](#research-project-assistants), [Alumni](#alumni)

## Convenor
{% assign number_printed = 0 %}
{% for member in site.data.lab_head %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="35%" style="float: left; padding: 5px" />


  <h4><b>{% if member.url %}<a href="{{ member.url }}" target="_blank">{{ member.name }}</a>{% else %}{{ member.name }}{% endif %}</b></h4>

  <i><b>{{ member.info }}</b></i>
  <i><br><b>{{ member.affl }}</b></i>
  <i><br>E-Mail: {{ member.email }}</i>
  
  <ul class="list-inline list-unstyled">
    {% if member.url == nil and member.linkedin %}
        <li><a target="blank" href="{{member.linkedin}}"><i class="fa-lg fab fa-linkedin"></i></a></li>
    {% endif %}
    {% if member.google_scholar %}
        <li><a target="blank" href="{{member.google_scholar}}"><i class="fa-lg fab fa-google"></i></a></li>
    {% endif %}
  </ul>

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

## Current Members

<h3 id="postdocs">PostDocs</h3>

{% assign number_printed = 0 %}
{% for member in site.data.lab_members %}
{% if member.position=="PostDoc" %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="37%" style="float: left; padding: 5px" />
  <h5><b>{% if member.url %}<a href="{{ member.url }}" target="_blank">{{ member.name }}</a>{% else %}{{ member.name }}{% endif %}</b></h5>

  <i>{{ member.position }} ({{ member.year }}) <br></i>
  Research Area: <i>{{ member.research_area }} <br></i>
  <ul class="list-inline list-unstyled">
    {% if member.url == nil and member.linkedin %}
        <li><a target="blank" href="{{member.linkedin}}"><i class="fa-lg fab fa-linkedin"></i></a></li>
    {% endif %}
    {% if member.google_scholar %}
        <li><a target="blank" href="{{member.google_scholar}}"><i class="fa-lg fab fa-google"></i></a></li>
    {% endif %}
  </ul>

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<br>

<h3 id="phd-masters-student">PhD/Master's Students</h3>

{% assign number_printed = 0 %}
{% for member in site.data.lab_members %}
{% if member.position=="Ph. D. student" or member.position=="M. Tech. (research)" or member.position=="M. Tech. (CDS)" %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="37%" style="float: left; padding: 5px" />
  <h5><b>{% if member.url %}<a href="{{ member.url }}" target="_blank">{{ member.name }}</a>{% else %}{{ member.name }}{% endif %}</b></h5>

  <i>{{ member.position }} ({{ member.year }}) <br></i>
  Research Area: <i>{{ member.research_area }} <br></i>
  <ul class="list-inline list-unstyled">
    {% if member.url == nil and member.linkedin %}
        <li><a target="blank" href="{{member.linkedin}}"><i class="fa-lg fab fa-linkedin"></i></a></li>
    {% endif %}
    {% if member.google_scholar %}
        <li><a target="blank" href="{{member.google_scholar}}"><i class="fa-lg fab fa-google"></i></a></li>
    {% endif %}
  </ul>

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<br>

### Research Project Assistants

{% assign number_printed = 0 %}
{% for member in site.data.lab_members %}
{% if member.position=="Project Assistant" %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="37%" style="float: left; padding: 5px" />
  <h5><b>{% if member.url %}<a href="{{ member.url }}" target="_blank">{{ member.name }}</a>{% else %}{{ member.name }}{% endif %}</b></h5>

  <i>{{ member.position }} ({{ member.year }}) <br></i>
  Past: <i>{{ member.past }} <br></i>

  <ul class="list-inline list-unstyled">
    {% if member.url == nil and member.linkedin %}
        <li><a target="blank" href="{{member.linkedin}}"><i class="fa-lg fab fa-linkedin"></i></a></li>
    {% endif %}
    {% if member.google_scholar %}
        <li><a target="blank" href="{{member.google_scholar}}"><i class="fa-lg fab fa-google"></i></a></li>
    {% endif %}
  </ul>

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<br>

### Interns

{% assign number_printed = 0 %}
{% for member in site.data.lab_members %}
{% if member.position=="Intern" %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="37%" style="float: left; padding: 5px" />
  <h5><b>{% if member.url %}<a href="{{ member.url }}" target="_blank">{{ member.name }}</a>{% else %}{{ member.name }}{% endif %}</b></h5>

  <i>{{ member.position }} ({{ member.year }}) <br></i>

  <ul class="list-inline list-unstyled">
    {% if member.url == nil and member.linkedin %}
        <li><a target="blank" href="{{member.linkedin}}"><i class="fa-lg fab fa-linkedin"></i></a></li>
    {% endif %}
    {% if member.google_scholar %}
        <li><a target="blank" href="{{member.google_scholar}}"><i class="fa-lg fab fa-google"></i></a></li>
    {% endif %}
  </ul>

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Alumni

### PhD/Master's Students

<ul>
{% for member in site.data.lab_alumni %}
  {% if member.position=="Ph. D." or member.position=="M. Tech. (research)" or member.position=="M. Tech. (CDS)"%}
    {% if member.position=="M. Tech. (CDS)" %}
      {% assign work_type = "Dissertation" %}
    {% else %}
      {% assign work_type = "Thesis" %}   
    {% endif %}
    {% if member.url %}
      <li><b><a href="{{ member.url }}" target="_blank">{{ member.name }}</a></b>, {{ member.position }} ({{ member.year }}), Current: <i>{{ member.affiliation}}</i><br>{{ work_type }}: <i>{{ member.worked_on }}</i></li>
    {% else %}
      <li><b>{{ member.name }}</b>, {{ member.position }} ({{ member.year }}), Current: <i>{{ member.affiliation}}</i><br>{{ work_type }}: <i>{{ member.worked_on }}</i></li>
    {% endif %}
  {% endif %}
{% endfor %}
</ul>

### Project Assistants

<ul>
{% for member in site.data.lab_alumni %}
  {% if member.position=="Project Assistant" %}
    {% if member.url %}
      <li><b><a href="{{ member.url }}" target="_blank">{{ member.name }}</a></b>, {{ member.position }} ({{ member.year }}), Current: <i>{{ member.affiliation}}</i> </li>
    {% else %}
      <li><b>{{ member.name }}</b>, {{ member.position }} ({{ member.year }}), Current: <i>{{ member.affiliation}}</i> </li>
    {% endif %}
  {% endif %}
{% endfor %}
</ul>

### Interns

<ul>
{% for member in site.data.lab_alumni %}
  {% if member.position=="Intern" %}
    {% if member.url %}
      <li><b><a href="{{ member.url }}" target="_blank">{{ member.name }}</a></b>, {{ member.position }} ({{ member.year }}), Current: <i>{{ member.affiliation}}</i> </li>
    {% else %}
      <li><b>{{ member.name }}</b>, {{ member.position }} ({{ member.year }}), Current: <i>{{ member.affiliation}}</i> </li>
    {% endif %}
  {% endif %}
{% endfor %}
</ul>
