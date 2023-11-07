---
layout: page
permalink: /repositories/
title: Repositories
description: 
nav: true
nav_order: 4
---


### Visualization

{% if site.data.repositories.visualization %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.visualization %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}

### COCAL code

{% if site.data.repositories.COCAL %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.COCAL %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}