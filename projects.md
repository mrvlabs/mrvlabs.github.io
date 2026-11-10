---
layout: base
title: "projects"
order: 2
---

<ul>
  {% for project in site.projects %}
    <li>
      <a href="{{ project.url | relative_url }}">{{ project.title }}</a>: {{ project.description }}
    </li>
  {% endfor %}
</ul>
