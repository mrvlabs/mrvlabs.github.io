---
layout: page
title: "projects"
---

### Current projects:  
- [Griffin](./projects/griffin.md): a tiny chess solver via computational decision optimisation
- Aegis: secure, formally verifiable execution environments
- Goblins: distributed agent search by objective 
- WOPR: weekly operational plan review
- Kai: augmented "flow" intelligence
- Linux Kernel Architecture: a book on the architecture of the linux kernel
- Raindrop: a tiny cloud
- Grinch: a <thing>
- Firepods: another <thing>
- Parker: a literal parking lot
- Cryptopher: a software hsm-thing


### (TEST) Listing projects through the built in scripting
<ul>
  {% for project in site.projects %}
    <li>
      <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
    </li>
  {% endfor %}
</ul>
