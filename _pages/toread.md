---
layout: page
title: To Read Papers
permalink: /toread/
description: Collection of papers on split computing, edge intelligence, and IoT to read and analyze
nav: true
nav_order: 3
---

<!-- _pages/toread.md -->
<div class="publications">
<h2>Split Computing & Edge Intelligence Papers</h2>
<p>This collection contains papers on split computing, edge intelligence, distributed inference, and IoT edge computing.</p>

{% assign papers = site.static_files | where: "path", "files/" | sort: "name" %}

{% for paper in papers %}
  {% assign filename = paper.path | split: "/" | last %}
  {% if filename contains ".md" %}
    {% assign title = filename | replace: ".md", "" | replace: "-", " " %}
    <div class="publication-entry">
      <h3><a href="{{ paper.path | relative_url }}">{{ title }}</a></h3>
    </div>
  {% endif %}
{% endfor %}

</div>