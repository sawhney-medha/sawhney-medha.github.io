---
layout: page
permalink: /publications/
title: Publications
description: #Publications are listed according to their type and in reverse chronological order. For an updated list please chek on [Google Scholar]<https://scholar.google.com/citations?user=o9Gj0dMAAAAJ&hl=en>(test)
nav: true
nav_order: 1
---
<!-- To add from a separate file just use:  bibliography --file preprint  -->
<!-- _pages/publications.md -->

<div class="publications">
  <p>
    Publications are listed according to their type and in reverse chronological order.
    For an updated list please check on
    <a href="https://scholar.google.com/citations?user=o9Gj0dMAAAAJ&hl=en">Google Scholar</a>.
    * denotes equal contribution
  </p>  

 
  <h4><b>Journal Papers</b></h4>
  {% bibliography -f papers -q @*[category=Journal Papers]  %}
  
  <h4><b>Workshop Papers</b></h4>
  {% bibliography -f papers -q @*[category=Workshop Papers]  %}
  
  <h4><b>Preprints</b></h4>
  {% bibliography -f papers -q @*[category=Preprints]  %}



<!--
<h3><b>Conference Proceedings</b></h3>
   bibliography -f papers -q @*[category=Conference Proceedings]  

<h2>Journal Publications</h2>
   bibliography -f papers -q @*[category=Journal Publications]  

  <h2>Book Chapters</h2>
   bibliography -f papers -q @*[category=Book Chapters]  
-->
