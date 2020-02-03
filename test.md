---
layout: default
title: "P-Hotels - Development"
---

# Bo billig og sentralt

Rimeligste pris får du ved å bestille her på våre nettsider

{% for hotel in site.data.hotels.hotels %}
  {% include component-hotel.html content=hotel %}
{% endfor %}
