---
title: "Projects"
permalink: /projects/
---

A selection of research software and experiments.

{% assign items = site.projects | sort: 'date' | reverse %}
<ul>
{% for p in items %}
  <li><a href="{{ p.url | relative_url }}">{{ p.title }}</a> — {{ p.summary }}</li>
{% endfor %}
</ul>
