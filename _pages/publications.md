---
layout: page
permalink: /papers/
title: PAPERS
description: <a href = 'https://scholar.google.com/citations?user=Bex7Ma4AAAAJ&hl=en'>Google Scholar</a><br>  (αβ)indicates alphabetical author order. * indicates equal contribution.
nav: true
nav_order: 2

---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<div class='h2'>Conference</div>

<div class="publications">


{% bibliography --query @*[howpublished=conference]* %}

</div>

<br>

<div class='h2'>Preprint</div>

<div class="publications">


{% bibliography --query @*[howpublished=preprint]* %}

</div>
