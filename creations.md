---
layout: page
title: "Creations"
permalink: /creations/
---

Here is a collection of my non-technical projects, writings, and explorations.

<hr>

{% for item in site.creations %}
<div class="project-card">
  <h3>
    <a href="{{ item.link }}" target="_blank" rel="noopener noreferrer">{{ item.title }}</a>
  </h3>
  <p>{{ item.content | strip_html }}</p>
  <p><a href="{{ item.link }}" target="_blank" rel="noopener noreferrer" class="btn">View on GitHub</a></p>
</div>
{% endfor %}