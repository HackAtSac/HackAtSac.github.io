---
layout: page
title: People
subtitle: The people behind Hack@Sac
permalink: /people/

people:
  - name: Varun Ved
    title: Python Perpetuator
    about: 3rd year CS student
  - name: Matthew Merrill
    title: Enterprise Enthusiast
    about: 1st year CS student

---

{% for person in page.people %}
### {{ person.name }}
{%if person.title%}
    {{ person.title }}{%endif%}{%if person.about%}
    {{ person.about }}{%endif%}
{% endfor %}

