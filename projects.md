---
layout: base
title: "projects"
---

### Projects
<ul>
  {% for project in site.projects %}
    <li>
      <a href="{{ project.url | relative_url }}">{{ project.title }}</a>: {{ project.description }}
    </li>
  {% endfor %}
</ul>
