---
layout: archive
title: "Expeditions"
permalink: /expeditions/
author_profile: true
---

{% include base_path %}

## Scientific Fieldwork
{% for post in site.expeditions %}
  {% include archive-single.html %}
{% endfor %}