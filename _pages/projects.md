---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 3
---

<div class="simple-projects">
  {% for project in site.data.projects %}
    <section class="about-section">
      <h2>{{ project.title }}</h2>
      <div>
        {{ project.description | markdownify }}
      </div>
    </section>
  {% endfor %}
</div>
