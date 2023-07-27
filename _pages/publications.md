---
layout: page
title: titles.publications
description: descriptions.publications
permalink: /publications/
nav: true
nav_order: 1
---
<div> <a id="top"></a>
 <ul>
  <li><a href="#papertype1"> Journal Papers </a></li>
  <li><a href="#papertype2"> International Conference Papers </a></li>
  <li><a href="#papertype3"> Other Papers </a></li>
  <li><a href="#papertype4"> Patents </a></li>
</ul> 
</div>
<!-- _pages/publications.md -->
<a id="papertype1"></a>

<div class="publications">
<h2> Journal Papers  </h2>
{% bibliography -f {{ site.scholar.bibliography1 }} %}

</div>
<a id="papertype2"> </a>

<div class="publications">
<h2> International Conference Papers</h2>
{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
<a id="papertype3"></a>

<div class="publications">
<h2>Other Papers </h2>
{% bibliography -f {{ site.scholar.bibliography2 }} %}

</div>
<a id="papertype4"></a>

<div class="publications">
<h2>Patents </h2>
{% bibliography -f {{ site.scholar.bibliography4 }} %}

</div>