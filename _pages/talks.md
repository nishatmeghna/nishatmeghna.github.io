---
title: "Talks"
layout: gridlay
sitemap: false
permalink: /talks/
---

# Talks

{% if site.data.conference_talks %}
## Conference presentations

{% for talk in site.data.conference_talks %}
{{ forloop.index }} <strong>{{ talk.title }}</strong> <br/> <i>{{ talk.authors }}</i>, {{ talk.conf }} ({{ talk.year }}).
{% endfor %}
{% endif %}


{% if site.data.invited_talks %}
## Talks and webinars

{% for talk in site.data.invited_talks %}
{{ forloop.index }} {{ talk.name }}{% if talk.link %} (<a href="{{ talk.link }}" target="_blank">link</a>){% endif %}.
{% endfor %}
{% endif %}

{% if site.data.chairing %}
## Chairing sessions

{% for session in site.data.chairing %}
{{ forloop.index }} <strong>{{ session.title }}</strong>.
<br/>{{ session.conf }} ({{ session.year }}).
{% endfor %}
{% endif %}

