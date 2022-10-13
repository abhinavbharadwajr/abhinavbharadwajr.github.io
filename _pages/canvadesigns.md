---
layout: page
permalink: /canvadesigns/
title: canva designs
description: canva designs for various activities and public usage.
nav: false
nav_order: 5
---
<!-- _pages/canvadesgn0.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
