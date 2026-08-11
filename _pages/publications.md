---
layout: page
title: Publications
permalink: /publications/
description: "*corresponding author"
nav: true
nav_order: 2
---

<style>
body, h1, h2, h3, h4, h5, h6, nav a, .navbar-brand { font-family: 'Lora', serif !important; }
.social a i { font-size: 1.5rem !important; }
:root { --global-theme-color: #15803d !important; --global-hover-color: #0d5c2b !important; }
html[data-theme="dark"] { --global-theme-color: #81c784 !important; --global-hover-color: #a5d6a7 !important; }
.bibliography em { color: var(--global-theme-color) !important; }
.bibliography .year { color: #555 !important; }
html[data-theme="dark"] .bibliography .year { color: #aaa !important; }
</style>
<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
