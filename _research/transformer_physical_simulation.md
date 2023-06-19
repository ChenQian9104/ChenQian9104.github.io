---
title: "Physical simulation with transformers"
layout: single-portfolio
image: '/images/research/transformer_physical_simulation.jpg'
collection: research
order_number: 0
header: 
  og_image: "research/transformer_physical_simulation.jpg"
abstract: "Inspired by the recent trend of **large language model (LLM)**, trasient physical problems such as heat transfer could be solved in a step by step, or sequence to sequence way. We build a model based on transformer models to solve the long-term dependancy problem existing in physical simulation <br/> Authors: <b> Qian Chen </b> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/> <br/>"
authors: '<b>Qian Chen</b>'
github: 'https://github.com/ChenQian9104/AM_sim_transformer'
---

{{ page.abstract }}

## Related Papers

{% for post in site.publications reversed %}
  {% if post.topic.adaptive_sampling %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
