---
layout: page
title: Speaker List
permalink: /speaker-list/
---

Check to make sure content loaded  
{% for a in site.data.authors %}  
Name: {{a.name}}  
Speaker? {{a.speaker}}  
{% if a.speaker %}  
{% assign author = a %}  
{% include speaker.html %}  
{% endif %}{% endfor %}  
