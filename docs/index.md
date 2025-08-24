---
layout: default
title: Template
---

<!-- This page renders the contents of Course_MLDDesignDoc/template.md -->

{% include lang_switcher.html %}

## Authors

{% assign authors = site.data.authors %}
{% if authors and authors.size > 0 %}
<ul>
  {% for person in authors %}
  <li>
    <strong>{{ person.name }}</strong>
    {% if person.role %} — {{ person.role }}{% endif %}
    {% if person.links and person.links.github %}
      · <a href="{{ person.links.github }}">GitHub</a>
    {% endif %}
  </li>
  {% endfor %}
  </ul>
{% else %}
<p>No authors listed yet.</p>
{% endif %}


