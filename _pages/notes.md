---
layout: page
title: notes
permalink: /notes/
description: research notes (continuous progress)
nav: true
nav_order: 2
display_categories:
horizontal: false
---

<!-- pages/notes.md -->

<div class="projects">

{%- assign sorted_notes = site.notes | sort: "importance" -%}

<!-- Generate smaller text-only clickable cards for each project stacked vertically -->

<div class="container">
  {%- for notes in sorted_notes -%}
    <a href="{{ notes.url }}" class="card mb-3 text-decoration-none text-reset">
      <div class="card-body">
        <h5 class="card-title">{{ notes.title }}</h5>
        <p class="card-text">{{ notes.description }}</p>
      </div>
    </a>
  {%- endfor %}
</div>

</div>
