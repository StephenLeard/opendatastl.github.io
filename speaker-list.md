---
layout: page
title: Speaker List
permalink: /speaker-list/
---

{% for a in site.data.authors %}  
{% if a.speaker %}  
{% assign author = a %}  
{% include speaker.html %}  
{% endif %}{% endfor %}  
