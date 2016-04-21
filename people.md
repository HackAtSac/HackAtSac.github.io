---
layout: page
title: People
subtitle: The people behind Hack@Sac
permalink: /people/

people:
  - name: Varun Ved
    description: 3rd year CS student
    url: http://varunmved.github.io
    img: /img/people/varunved.jpg
  - name: Matthew Merrill
    description: 1st year CS student
    url: http://matthewmerrill.me
    img: /img/people/matthewmerrill.jpg

---

{% for person in page.people %}
---
{%capture floatside%}{%cycle 'left', 'right'%}{%endcapture%}
{%include entry-render.html entry=person float=floatside isfirst=forloop.first%}
{% endfor %}
---

