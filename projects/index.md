---
layout: page
title: "Projects"
---
{% for project in site.projects %}
  <div class="project">
    <h3><a href="{{ project.website }}" title="{{ project.title }}">{{ project.title }}</a></h3>
    <p>{{ project.content }}</p>
  </div>
{% endfor %}
