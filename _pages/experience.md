---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
---

{% assign sorted_experience = site.experience | sort: "order" %}
{% for post in sorted_experience %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p><em>{{ post.excerpt }}</em></p>
{% endfor %}

