---
layout: page
permalink: /publications/
title: publications
description: My publications in reversed chronological order.
years: [2017, 2016, 2015, 2014]
---

<h3 class="year">Theses</h3>
{% bibliography -f theses %}

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
