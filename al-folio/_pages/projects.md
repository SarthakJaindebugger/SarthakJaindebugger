---
layout: page
title: Projects
permalink: /projects/
description: Research-heavy AI systems, full-stack products, and deployable ML pipelines.
nav: true
nav_order: 3
display_categories: [ai-systems, speech-multimodal, software]
horizontal: false
---

<div class="projects-intro">
  <p>Selected work focused on deployable AI: retrieval systems, speech and multimodal models, privacy-aware full-stack applications, and research pipelines that translate papers into products.</p>
</div>

<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>
