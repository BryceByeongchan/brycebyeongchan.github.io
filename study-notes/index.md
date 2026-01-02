---
layout: default
title: Study Notes
---

## Study Notes

Under Construction

### Many-body Perturbation Theory
<ul>
  {% for post in site.categories.mbpt %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>

