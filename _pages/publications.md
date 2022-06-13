---
layout: page
permalink: /publications/
title: Publications
description: Selected publications in reverse-chronological order <br/> Full publication list on <a href=https://scholar.google.com/citations?user=vgLANV0AAAAJ>Google Scholar</a> and <a href=https://dblp.org/pid/152/1714.html>DBLP</a>
years: [2022, 2021, 2020]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>