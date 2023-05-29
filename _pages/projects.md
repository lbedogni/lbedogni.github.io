---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 2
horizontal: false
categories: [project,private-project-research]
---

Luca Bedogni research work focuses on span across several domains, including the Internet of Things, Digital Twins, Crowdsensing systems and the privacy issues which lie therein. On these topics he has co-authored more than 70 scientific papers on international conferences and journals, and he participated and actively participates in national and international research projects. 

Further information about his research work can be found on:
* [Google Scholar](http://scholar.google.com/citations?user=N0ocP0EAAAAJ&hl=it)
* [Researchgate](http://www.researchgate.net/profile/Luca_Bedogni/?ev=hdr_xprf)

Below there is a list of research topics and projects he has participated or is participating in.

<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>