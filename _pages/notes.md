---
layout: page
title: Notes
nav_title: notes
description: Divulgative notes about some mathematical facts. 
permalink: /notes/
nav: true
nav_order: 4
math: true
---

$$
\newcommand{\R}{\mathbb{R}}
$$

{% for doc in site.data.notes %}
  {% include note.liquid doc=doc %}
{% endfor %}

<style>
  .document-entry {
    margin-bottom: 2rem;
  }

  .document-abstract {
    margin-top: 0.75rem;
  }

  .document-abstract summary {
    cursor: pointer;
    color: var(--global-theme-color);
    font-weight: 500;
  }
</style>