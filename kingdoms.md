---
layout: page
title: Kingdoms
permalink: /kingdoms/
---

{% for kingdom in site.kingdoms %}
- [{{kingdom.title}}](..{{ kingdom.url}})
{% endfor %}

![Mysthaln Map](../assets/img/mysthaln-map.png 'A map of Mysthaln')
