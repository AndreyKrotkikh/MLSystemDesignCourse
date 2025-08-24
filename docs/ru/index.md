---
layout: plain
title: Курс по ML System Design
lang: ru
---

{% include lang_switcher.html %}

# Курс по ML System Design

## Авторы

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
<p>Список авторов пока пуст.</p>
{% endif %}

## Документы

- [Шаблон дизайн-документа]({{ '/ru/template' | relative_url }})


