---
layout: page
title: People
subtitle: The people behind Hack At Sac
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
#### _{{ person.title }}_
{%endif%}
{%if person.about%}
{{ person.about }}
{%endif%}
{% endfor %}


{% include icon-github.html username="MatthewMerrill" %} /
[jekyll-new](https://github.com/jglovier/jekyll-new)

You can find the source code for Jekyll at
{% include icon-github.html username="jekyll" %} /
[jekyll](https://github.com/jekyll/jekyll)

