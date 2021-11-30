---
title: "Education"
layout: gridlay
sitemap: false
permalink: /education/
---

# Education


{% if site.data.supervision_msc %}
## Supervision of MSc final projects
<div class="rowl1" style="padding-top: 10px;">

{% for student in site.data.supervision_msc %}
  {% assign pdffile = false %}
  {% if student.project_url %}
      {% if student.project_url contains '://' %}
        {% assign pdffile = student.project_url %}
      {% else %}
        {% assign pdffile = "/papers/students/" | append:  student.project_url  | append: ".pdf" %}
      {% endif %}
  {% endif %}

{{ forloop.index }}. {% if student.name_url %}<a href="{{ student.name_url }}" target="_blank">{% endif %} <strong>{{ student.name }}</strong> {% if student.name_url %}</a>{% endif %} ({{ student.year }}) {% if student.status == 'notstarted' %}<button class="btn-notstarted">NOT STARTED</button>{% endif %}{% if student.status == 'inprogress' %}<button class="btn-inprogress">IN PROGRESS</button>{% endif %}{% if student.status == 'completed' %}<button class="btn-completed">COMPLETED</button>{% endif %}{% if student.comment %} – {{ student.comment }}{% endif %}
<br/>
<i>{{ student.project }}</i>{% if pdffile %} (<a href="{{ pdffile }}" target="_blank">link</a>){% endif %}.

{% endfor %}
</div>
{% endif %}

{% if site.data.supervision_internship %}
## Supervision of internships
<div class="rowl1" style="padding-top: 10px;">

{% for student in site.data.supervision_internship %}

{{ forloop.index }}. {% if student.name_url %}<a href="{{ student.name_url }}" target="_blank">{% endif %} <strong>{{ student.name }}</strong> {% if student.name_url %}</a>{% endif %} ({{ student.year }}) {% if student.status == 'notstarted' %}<button class="btn-notstarted">NOT STARTED</button>{% endif %}{% if student.status == 'inprogress' %}<button class="btn-inprogress">IN PROGRESS</button>{% endif %}{% if student.status == 'completed' %}<button class="btn-completed">COMPLETED</button>{% endif %}{% if student.comment %} – {{ student.comment }}{% endif %}
<br/>
<i>{{ student.project }}</i>{% if student.project_url %} (<a href="{{ student.project_url }}" target="_blank">link</a>){% endif %}.

{% endfor %}
</div>
{% endif %}

{% if site.data.supervision_phd %}
## Supervision of PhD students
<div class="rowl1" style="padding-top: 10px;">

{% for student in site.data.supervision_phd %}

{{ forloop.index }}. {% if student.name_url %}<a href="{{ student.name_url }}" target="_blank">{% endif %} <strong>{{ student.name }}</strong> {% if student.name_url %}</a>{% endif %} ({{ student.year }}) {% if student.status == 'notstarted' %}<button class="btn-notstarted">NOT STARTED</button>{% endif %}{% if student.status == 'inprogress' %}<button class="btn-inprogress">IN PROGRESS</button>{% endif %}{% if student.status == 'completed' %}<button class="btn-completed">COMPLETED</button>{% endif %}{% if student.comment %} – {{ student.comment }}{% endif %}
<br/>
<i>{{ student.project }}</i>{% if student.project_url %} (<a href="{{ student.project_url }}" target="_blank">link</a>){% endif %}.

{% endfor %}
</div>
{% endif %}

{% if site.data.supervision_bsc %}
## Supervision of BSc final project groups
<div class="rowl1" style="padding-top: 10px;">

{% for student in site.data.supervision_bsc %}
  {% assign pdffile = false %}
  {% if student.project_url %}
      {% if student.project_url contains '://' %}
        {% assign pdffile = student.project_url %}
      {% else %}
        {% assign pdffile = "/papers/students/" | append:  student.project_url  | append: ".pdf" %}
      {% endif %}
  {% endif %}

{{ forloop.index }}. {% if student.name_url %}<a href="{{ student.name_url }}" target="_blank">{% endif %} <strong>{{ student.name }}</strong> {% if student.name_url %}</a>{% endif %} ({{ student.year }}) {% if student.status == 'notstarted' %}<button class="btn-notstarted">NOT STARTED</button>{% endif %}{% if student.status == 'inprogress' %}<button class="btn-inprogress">IN PROGRESS</button>{% endif %}{% if student.status == 'completed' %}<button class="btn-completed">COMPLETED</button>{% endif %}{% if student.comment %} – {{ student.comment }}{% endif %}
<br/>
<i>{{ student.project }}</i>{% if pdffile %} (<a href="{{ pdffile }}" target="_blank">link</a>){% endif %}.

{% endfor %}
</div>
{% endif %}

{% if site.data.lectures %}
## Lectures
<div class="rowl1" style="padding-top: 10px;">

{% for lecture in site.data.lectures %}
{{ forloop.index }}. {{ lecture.name }}

{% endfor %}
</div>
{% endif %}
