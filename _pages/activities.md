---
layout: page
title: Activities
permalink: /activities/
nav: true
nav_order: 4
---

{% if site.data.conferences and site.data.conferences.size > 0 %}
  <section class="about-section">
    <h2>Conferences</h2>
    {% include talks.liquid talks=site.data.conferences %}
  </section>
{% endif %}

{% if site.data.seminar_talks and site.data.seminar_talks.size > 0 %}
  <section class="about-section">
    <h2>Seminar Talks</h2>
    {% include talks.liquid talks=site.data.seminar_talks %}
  </section>
{% endif %}
