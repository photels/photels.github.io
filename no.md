---
layout: default
title: "P-Hotels - Development"
lang: no
---

{% include component-hero.html %}

{% for hotel in site.data.hotels %}
  {% include component-hotel.html content=hotel %}
{% endfor %}

{% include component-facilities.html %}

{% include component-footer.html %}
