---
layout: page
title: Magic
permalink: /magic/
---

Magic in Mysthaln flows from **living bonds** between humans and animals. When a human forms a successful **soul-link** with an animal, both beings awaken latent arcane potential. Each species grants a **unique magical discipline**, shaping the caster’s abilities. As the bond deepens, the animal gains **growing intelligence, emotion, and communication**, while the human gains expanding magical control.

A bond can only be severed by **death**. When one partner dies, the other suffers **severe emotional and mental trauma**, and the animal’s awakened mind begins to **fade back into instinct**.

Below are known magical disciplines by animal type:

| Animal Type | Examples | Magic |
|--------|--------|---|{% for animal in site.magic %}
| [{{animal.title}}](..{{animal.url}}) | {{animal.animals}} | {{animal.magic}} |{% endfor %}
