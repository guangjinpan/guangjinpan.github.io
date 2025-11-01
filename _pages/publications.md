---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Semantic Communication for Multimedia Applications</h2>
{% bibliography --group_by none --query @*[category="Semantic Communication for Multimedia Applications"]* %}

<h2>Semantic Communication for ISAC systems</h2>
{% bibliography --group_by none --query @*[category="Semantic Communication for ISAC systems"]* %}

<h2>Semantic Communication for Closed-loop Communication–Sensing–Control Systems</h2>
{% bibliography --group_by none --query @*[category="Semantic Communication for Closed-loop Communication–Sensing–Control Systems"]* %}

</div>
