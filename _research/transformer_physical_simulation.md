---
title: "Using transformer for physical simulation: an application to the transient thermal simulation on multiple layer deposition process"
layout: single-portfolio
image: '/images/research/transformer_physical_simulation.jpg'
collection: research
order_number: 0
header: 
  og_image: "research/transformer_physical_simulation.jpg"
abstract: "<b>Using transformer for physical simulation: an application to the transient thermal simulation on multiple layer deposition process</b>"
authors: '<b>Qian Chen</b>, Albert To'
github: 'https://github.com/ChenQian9104/AM_sim_transformer'
tail: "<br/>  <br/> <br/> <br/> <br/> "
---

{{ page.abstract }}

## Related Papers

{% for post in site.publications reversed %}
  {% if post.topic.adaptive_sampling %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
