---
layout: default
title: "P-Hotels - Development"
lang: nor
---

{% include component-hero.html %}

{% for hotel in site.data.hotels %}
  {% include component-hotel.html content=hotel%}
{% endfor %}
