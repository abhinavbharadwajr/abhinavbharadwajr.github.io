---
layout: blog
title: canva designs
permalink: /canvadesigns/
description: canva designs for various activities and public usage.
nav: false
nav_order: 5
---
<!-- _pages/canvadesigns.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
