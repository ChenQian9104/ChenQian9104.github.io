---
title: "transformer"
layout: single-portfolio
image: '/images/research/transformer_physical_simulation.jpg'
collection: research
order_number: 2
header: 
  og_image: "research/transformer_physical_simulation.jpg"
abstract: "<b>Physical simulation with transformers</b>"
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
