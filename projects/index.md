---
layout: page
title: "Projects"
---

{% for project in site.projects %}
  <h3><a href="{{ project.website }}" title="{{ project.title }}">{{ project.title }}</a></h3>
  <p>{{ project.content }}</p>
{% endfor %}
