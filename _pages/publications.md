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

<h2>AI for Communication</h2>
{% bibliography --group_by none --query @*[category=SC-XR]* %}

<h2>AI for sensing</h2>
{% bibliography --group_by none --query @*[category=SC-ISAC]* %}

<h2>AI for Closed-loop Communication–Sensing–Control Systems</h2>
{% bibliography --group_by none --query @*[category=SC-ISCCC]* %}

</div>
