---
layout: plain
title: ML System Design Course
lang: en
---

{% include lang_switcher.html %}

# ML System Design Course

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

## Documents

- [Design Doc Template]({{ '/en/template' | relative_url }})


