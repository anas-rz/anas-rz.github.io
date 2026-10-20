---
layout: page
title: projects
permalink: /projects/
description: Open-source systems, multi-backend ML frameworks, AI systems research, and production platforms.
nav: true
nav_order: 3
display_categories: ["ML Systems", "Research", "Full-Stack"]
horizontal: false
---

<!-- Category Navigation Bar -->
<div class="mb-4 pb-2" style="display: flex; gap: 8px; flex-wrap: wrap; align-items: center;">
  <span class="small text-muted font-weight-bold" style="text-transform: uppercase; letter-spacing: 0.5px; margin-right: 4px;">Jump to:</span>
  {% for category in page.display_categories %}
    <a href="#{{ category }}" class="category-jump-pill">
      {{ category }}
    </a>
  {% endfor %}
</div>

<!-- pages/projects.md -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <div class="project-category-section mb-5" id="{{ category }}">
    <h2 class="category mb-3" style="font-weight: 700; border-bottom: 1px solid var(--global-divider-color); padding-bottom: 0.5rem; display: flex; justify-content: space-between; align-items: baseline;">
      <span>{{ category }}</span>
      {% assign categorized_projects = site.projects | where: "category", category %}
      <span class="small text-muted font-weight-normal" style="font-size: 0.82rem;">{{ categorized_projects.size }} projects</span>
    </h2>
    {% assign sorted_projects = categorized_projects | sort: "importance" %}
    <!-- Generate cards for each project -->
    {% if page.horizontal %}
    <div class="container">
      <div class="row row-cols-1 row-cols-md-2">
      {% for project in sorted_projects %}
        {% include projects_horizontal.liquid %}
      {% endfor %}
      </div>
    </div>
    {% else %}
    <div class="row row-cols-1 row-cols-md-3">
      {% for project in sorted_projects %}
        {% include projects.liquid %}
      {% endfor %}
    </div>
    {% endif %}
  </div>
  {% endfor %}

{% else %}

<!-- Display projects without categories -->
{% assign sorted_projects = site.projects | sort: "importance" %}

  <!-- Generate cards for each project -->
{% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
{% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
{% endif %}
{% endif %}
</div>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,400;1,600&display=swap');

  body,
  h1, h2, h3, h4, h5, h6,
  .category,
  .card-title, .card-text,
  button, a {
    font-family: 'Montserrat', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif !important;
  }

  .category-jump-pill {
    padding: 4px 12px;
    font-size: 0.82rem;
    font-weight: 500;
    border-radius: 9999px;
    border: 1px solid var(--global-divider-color);
    background: var(--global-code-bg-color);
    color: var(--global-text-color) !important;
    text-decoration: none !important;
    transition: all 0.2s ease;
  }
  .category-jump-pill:hover {
    border-color: var(--global-theme-color);
    color: var(--global-theme-color) !important;
    transform: translateY(-1px);
  }

  .card.hoverable {
    transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
    border: 1px solid var(--global-divider-color);
    background: var(--global-card-bg-color);
  }
  .card.hoverable:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06);
    border-color: var(--global-theme-color);
  }
</style>
