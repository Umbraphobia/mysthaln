---
layout: page
title: Races
permalink: /races/
---

{% for race in site.races %}
- [{{race.title}}](..{{ race.url }})
{% endfor %}

![A Child of the Oracle](../assets/img/supremacy-knight.jpg 'A Child of the Oracle')
