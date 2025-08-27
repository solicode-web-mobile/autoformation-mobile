---
title: 📋 Toutes les métadonnées
layout: home
nav_order: 100
permalink: /all-metadata/
---

# 📋 Toutes les métadonnées de chaque page

{% for p in site.pages %}


{% for key in p %}
| {{ key[0] }} | {{ key[1] }} |
{% endfor %}

{% endfor %}
