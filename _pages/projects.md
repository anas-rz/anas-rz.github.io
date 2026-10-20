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

<!-- pages/projects.md -->
<div class="projects">
  <!-- Interactive Category Filter Bar -->
  <div class="project-filter-bar mb-4" style="display: flex; flex-wrap: wrap; gap: 8px; margin-top: 0.5rem; margin-bottom: 2rem;">
    <button type="button" class="project-filter-pill active" data-filter="all">All Projects</button>
    <button type="button" class="project-filter-pill" data-filter="ML Systems">ML Systems</button>
    <button type="button" class="project-filter-pill" data-filter="Research">Research &amp; Papers</button>
    <button type="button" class="project-filter-pill" data-filter="Full-Stack">Full-Stack</button>
  </div>

{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <div class="project-category-section mb-5" data-category="{{ category }}">
    <a id="{{ category }}" href=".#{{ category }}">
      <h2 class="category mb-3" style="font-weight: 700; border-bottom: 1px solid var(--global-divider-color); padding-bottom: 0.4rem;">
        {{ category }}
      </h2>
    </a>
    {% assign categorized_projects = site.projects | where: "category", category %}
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
  .project-filter-pill,
  button, a {
    font-family: 'Montserrat', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif !important;
  }

  .project-filter-pill {
    padding: 6px 14px;
    font-size: 0.85rem;
    font-weight: 500;
    border-radius: 9999px;
    border: 1px solid var(--global-divider-color);
    background: var(--global-code-bg-color);
    color: var(--global-text-color);
    cursor: pointer;
    transition: all 0.2s cubic-bezier(0.16, 1, 0.3, 1);
    outline: none;
  }
  .project-filter-pill:hover {
    border-color: var(--global-theme-color);
    color: var(--global-theme-color);
    transform: translateY(-1px);
  }
  .project-filter-pill.active {
    background: var(--global-theme-color);
    color: #ffffff !important;
    border-color: var(--global-theme-color);
    box-shadow: 0 4px 12px rgba(181, 9, 172, 0.2);
  }
  .card.hoverable {
    transition: transform 0.25s cubic-bezier(0.16, 1, 0.3, 1), box-shadow 0.25s cubic-bezier(0.16, 1, 0.3, 1), border-color 0.2s ease;
    border: 1px solid var(--global-divider-color);
  }
  .card.hoverable:hover {
    transform: translateY(-4px);
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08);
    border-color: var(--global-theme-color);
  }
  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(6px); }
    to { opacity: 1; transform: translateY(0); }
  }
</style>

<script>
  (function() {
    function initFilters() {
      const pills = document.querySelectorAll('.project-filter-pill');
      if (!pills.length) return;
      pills.forEach(pill => {
        pill.addEventListener('click', function() {
          const filter = this.getAttribute('data-filter');
          pills.forEach(p => p.classList.remove('active'));
          this.classList.add('active');

          const sections = document.querySelectorAll('.project-category-section');
          sections.forEach(sec => {
            const cat = sec.getAttribute('data-category');
            if (filter === 'all' || cat === filter) {
              sec.style.display = 'block';
              sec.style.animation = 'fadeIn 0.3s ease forwards';
            } else {
              sec.style.display = 'none';
            }
          });
        });
      });
    }
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', initFilters);
    } else {
      initFilters();
    }
  })();
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,400;1,600&display=swap');

  body,
  h1, h2, h3, h4, h5, h6,
  .category,
  .card-title, .card-text,
  .project-filter-pill,
  button, a {
    font-family: 'Montserrat', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif !important;
  }

  .project-filter-pill {
    padding: 6px 14px;
    font-size: 0.85rem;
    font-weight: 500;
    border-radius: 9999px;
    border: 1px solid var(--global-divider-color);
    background: var(--global-code-bg-color);
    color: var(--global-text-color);
    cursor: pointer;
    transition: all 0.2s cubic-bezier(0.16, 1, 0.3, 1);
    outline: none;
  }
  .project-filter-pill:hover {
    border-color: var(--global-theme-color);
    color: var(--global-theme-color);
    transform: translateY(-1px);
  }
  .project-filter-pill.active {
    background: var(--global-theme-color);
    color: #ffffff !important;
    border-color: var(--global-theme-color);
    box-shadow: 0 4px 12px rgba(181, 9, 172, 0.2);
  }
  .card.hoverable {
    transition: transform 0.25s cubic-bezier(0.16, 1, 0.3, 1), box-shadow 0.25s cubic-bezier(0.16, 1, 0.3, 1), border-color 0.2s ease;
    border: 1px solid var(--global-divider-color);
  }
  .card.hoverable:hover {
    transform: translateY(-4px);
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08);
    border-color: var(--global-theme-color);
  }
  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(6px); }
    to { opacity: 1; transform: translateY(0); }
  }
</style>

<script>
  (function() {
    function initFilters() {
      const pills = document.querySelectorAll('.project-filter-pill');
      if (!pills.length) return;
      pills.forEach(pill => {
        pill.addEventListener('click', function() {
          const filter = this.getAttribute('data-filter');
          pills.forEach(p => p.classList.remove('active'));
          this.classList.add('active');

          const sections = document.querySelectorAll('.project-category-section');
          sections.forEach(sec => {
            const cat = sec.getAttribute('data-category');
            if (filter === 'all' || cat === filter) {
              sec.style.display = 'block';
              sec.style.animation = 'fadeIn 0.3s ease forwards';
            } else {
              sec.style.display = 'none';
            }
          });
        });
      });
    }
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', initFilters);
    } else {
      initFilters();
    }
  })();
</script>

