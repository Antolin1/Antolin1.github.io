---
layout: page
permalink: /teaching/
title: teaching
description: Materials for courses I teach. 
nav: true
nav_order: 6
---

# Algorithms and data structures II (Spanish)

{% if site.data.repositories.github_repos_teaching %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos_teaching %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
