---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Emerging manufacturing technologies such as additive manufacturing and micro/nano fabrication have enabled much richer design freedom, but this also brings challenges associated with exploring a much larger design space and quantifying design uncertainty. The goal of my research is to overcome these challenges by **rethinking what should be a good representation of a design space and how to efficiently explore this space**. My current research treats the design space as a design element, and uses **artificial intelligence (AI)** and **machine learning (ML)** to automatically learn and explore this space. 

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html %}
{% endfor %}
