---
layout: page
title: Pages de l’ancien site
author: LGD
nav: true
date: 2015-10-28 18:30:00 CET
---

{% for page in site.pages %}
{% if page.wordpress_id != nil %}
- [{{ page.title }}]({{ page.url }})
{% endif %}
{% endfor %}
