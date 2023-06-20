---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Please check my **[google scholar page](https://scholar.google.com/citations?user=bbCX7LkAAAAJ&hl=en)** for all the publications <br/>

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html %}
{% endfor %}
