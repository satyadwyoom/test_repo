---
layout: page
permalink: /publications/
title: PUBLICATIONS
description: Publications by categories in reversed chronological order.
# years: [2022, 2023]
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

<!-- {%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %} -->

{% bibliography -f {{ site.scholar.bibliography }} %}


</div>