---
layout: page
title: Speaker List
permalink: /speaker-list/
---
{% for a in site.data.authors %}{% if a.speaker == 'Yes' %}
{% assign author = a %}
{% include speaker.html %}
{% endif %}{% endfor %}
