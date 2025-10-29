---
layout: page
title: Kingdoms
permalink: /kingdoms/
---

{% for kingdom in site.kingdoms %}
- [{{kingdom.title}}](..{{ kingdom.url}})
{% endfor %}
