---
title: ""
layout: single-portfolio
image: '/images/research/Path_optimization.jpeg'
collection: research
order_number: 1
header: 
  og_image: "research/Path_optimization.jpeg"
abstract: "<b>Island scanning pattern optimization for residual deformation mitigation in laser powerder bed fusion via sequential inherent strain method and sensitivity analysis<b>"
journal: 'Additive Manufacturing 46, 102116'
authors: '<b>Qian Chen</b>, Hunter Taylor, Akihiro Takezawa, Xuan Liang, Xavier Jimemez, Ryan Wicker, Albert To'
paperurl: '/files/pdf/publications/Luo2015_Article_SimulationOfAluminumAlloyFlowi.pdf'
link: 'https://link.springer.com/article/10.1007%2Fs00170-015-7228-6'
github: 'https://github.com/wchen459/GAN-DUF'
---

{{ page.abstract }}

## Related Papers

{% for post in site.publications reversed %}
  {% if post.topic.adaptive_sampling %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
