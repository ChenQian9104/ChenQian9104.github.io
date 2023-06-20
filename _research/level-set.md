---
title: "level set optimization"
layout: single-portfolio
image: '/images/research/Path_generation.gif'
collection: research
order_number: 2
header: 
  og_image: "research/Path_generation.gif"
abstract: "<b>A level-set based continuous scanning path optimization method for reducing residual stress and deformation in metal additive manufacturing</b>"
journal: '<em>Computer Methods in Applied Mechanics and Engineering 360, 112719</em>'
authors: '<b>Qian Chen</b>, Jikai Liu, Xuan Liang, Albert To'
paperurl: '/files/pdf/publications/Level-set.pdf'
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
