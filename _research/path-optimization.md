---
title: "path optimization"
layout: single-portfolio
image: '/images/research/Path_optimization.jpeg'
collection: research
order_number: 1
header: 
  og_image: "research/Path_optimization.jpeg"
abstract: "<b>Island scanning pattern optimization for residual deformation mitigation in laser powerder bed fusion via sequential inherent strain method and sensitivity analysis</b>"
journal: '<em>Additive Manufacturing 46, 102116</em>'
authors: '<b>Qian Chen</b>, Hunter Taylor, Akihiro Takezawa, Xuan Liang, Xavier Jimemez, Ryan Wicker, Albert To'
paperurl: '/files/pdf/publications/Island_scan_opt.pdf.pdf'
link: 'https://www.sciencedirect.com/science/article/abs/pii/S2214860421002815'
github: 'https://github.com/ChenQian9104/island_scan_opt'
tail: "<br/> <br/> <br/> <br/> <br/>"
---

{{ page.abstract }}

## Related Papers

{% for post in site.publications reversed %}
  {% if post.topic.adaptive_sampling %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
