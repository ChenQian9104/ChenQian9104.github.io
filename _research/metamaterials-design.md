---
title: "Metamaterials Design"
layout: single-portfolio
image: "/images/research/heterogeneous.png"
collection: research
order_number: 40
header: 
  og_image: "research/heterogeneous.png"
abstract: "Metamaterials have enabled unprecedented mechanical, thermal, optical, acoustic, and other physical properties. One can carefully engineer the geometry of metamaterials to achieve target properties and eventually reach certain global performance, but this is not easy work, especially when we face a large-scale heterogeneous problem where we want to optimize metamaterials at different locations of a large domain. Despite this challenge, metamaterials, as simple modularized geometries, are relatively easy to be processed by machine learning models and data are usually abundant. In this research, I combine machine learning and topology optimization to simplify and accelerate the design of such large-scale heterogeneous systems."
---

{{ page.abstract }}

## Related Papers

{% for post in site.publications reversed %}
  {% if post.topic.metamaterials_design %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


