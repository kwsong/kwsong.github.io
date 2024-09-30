---
layout: page
permalink: /publications/
title: publications
description: publications and patents
years: [2024, 2023, 2022, 2021, 2020, 2018, 2016, 2015, 2013, 2012, 2011, 2010, 2009]
nav_order: 2
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
