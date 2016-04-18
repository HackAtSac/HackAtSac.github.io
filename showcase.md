---
layout: page
title: Showcase
subtitle: Our Strongest Projects... So Far!
permalink: /showcase/

projects:
  - name: March Madness Predictor
    description: Visualization tool to rank teams by their offensive and defensive ability.
    url: http://datascience-sacstate.github.io/March-Madness
    img: /img/showcase/marchmadness.gif
    
  - name: Clean Sac
    description: 311 Data collection visualization tool. Can view incident heatmaps by type filters and by cluster location.
    url: http://datascience-sacstate.github.io/clean-sac/src/
    img: /img/showcase/cleansac.gif 
    
---

Here's what we've built so far, we're always creating new things so check back for more.

{% for project in page.projects %}
---
{%capture floatside%}{%cycle 'left', 'right'%}{%endcapture%}
{%include entry-render.html entry=project float=floatside isfirst=forloop.first%}
{% endfor %}
---



