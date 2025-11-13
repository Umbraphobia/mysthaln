---
layout: page
title: Kingdoms
permalink: /kingdoms/
---

{% for kingdom in site.kingdoms %}
- [{{kingdom.title}}](..{{ kingdom.url}})
{% endfor %}

![The Stormbarrier Range](../assets/img/stormbarrier-range.jpg 'Ruined Vardessian outpost on the Stormbarrier range')
