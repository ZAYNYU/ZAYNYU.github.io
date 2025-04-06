---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

## Experience
{% for post in site.experience reversed %}
  {% include archive-single.html %}
{% endfor %}

## Projects
{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}


