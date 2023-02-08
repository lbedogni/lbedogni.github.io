---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 2
horizontal: false
categories: [project,private-project-research]
---

Luca Bedogni research work focuses on the efficient utilization of White Space spectrum, particularly regarding the TV White Space scenario. He also worked on MAC protocols for Vehicular Networks, in the IEEE 802.11p and IEEE 1609.4 protocols.
He studies Machine-to-Machine communication over TV White Spaces, in the challenging indoor environments.

In addition, he also work on the possible utilization of TV Gray Spaces, focusing on the underlay spectrum access paradigm in Cognitive Wireless Networks, in which secondary devices might transmit on the same frequencies actually used by the primary users, by granting them a sufficient protection.

Further information about his research work can be found on:
* [Google Scholar](http://scholar.google.com/citations?user=N0ocP0EAAAAJ&hl=it)
* [Researchgate](http://www.researchgate.net/profile/Luca_Bedogni/?ev=hdr_xprf)

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