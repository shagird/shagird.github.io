---
layout: page
title: Research Projects
permalink: /projects/
---

{% for project in site.projects %}
## [{{ project.title }}]({{ project.url }})
<div class="project-item">
    <p>{{ project.short_description }}</p>
    {% if project.project_image %}
    <img src="{{ project.project_image }}" alt="{{ project.title }}" class="project-image">
    {% endif %}
</div>
{% endfor %}