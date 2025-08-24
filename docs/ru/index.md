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
- [Чеклист дизайн-документа]({{ '/ru/checklist' | relative_url }})

## Дизайн‑документ проекта

### Резюме
- **Название проекта**: [Название]
- **Постановка задачи**: [Краткое описание проблемы]
- **Бизнес‑эффект**: [Ожидаемый эффект и KPI]
- **Таймлайн**: [Высокоуровневый план]

### I. Определение проблемы
- Истоки: [заполнить]
- Важность и причины: [заполнить]
- Предыдущие попытки: [заполнить]
- Прочие вопросы и риски: [заполнить]


