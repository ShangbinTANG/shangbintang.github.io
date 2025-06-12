---
title: "Mapping the Migration of Academic Talent"
order: 6
excerpt: "An exploration of 268 million research papers to uncover international and interregional patterns in academic collaboration and researcher migration."
layout: single
# classes: wide
header:
  overlay_image: /assets/images/project_collection/Mag_talent_migration/global_v_0_1_cropped.jpg
  overlay_filter: rgba(0, 0, 0, .8)
  teaser: /assets/images/project_collection/Mag_talent_migration/global_v_0_1_cropped.jpg
sidebar:
  - text: <br>
  - title: "Tools"
    text: "Python<br>pandas<br>ArcGIS Pro"
gallery1: # Hot words in new titles.
  - url: /assets/images/project_collection/Mag_talent_migration/final.jpg
    image_path: /assets/images/project_collection/Mag_talent_migration/final.jpg
    alt: "Dark theme"

---

<!-- {% include gallery caption="This is a sample gallery to go along with this case study." %}
![image-center]({{ site.url }}{{ site.baseurl }}/assets/images/image-alignment-580x300.jpg){: .align-center} -->
<p style="color:grey"><em>Key words: MAG, GIS, Mapping, Python</em></p>

<!-- <p style="margin-top:75px; color:grey">This is a small personal project, where I aquaired and converted publicly available tabular data into spatial data, and mapped the earthquake events in a 100% pure coding method.</p> -->


{% include gallery id = "gallery1" caption="" %}
<a href="https://academic.oup.com/healthaffairsscholar/article/1/1/qxad003/7203711" target="_blank"> Microsoft Academic Graph</a>(MAG) was a massive bibliographic database containing hundreds of millions of publication records, along with detailed information on authors, citations, and journals. Unfortunately, it was retired at the end of 2021.

<br>
I downloaded **268 million** publication records and **729 million** paper-author-affiliation entries. After preprocessing and cleaning the data, I filtered the records to include only those from 2010 onward and from authors with more than one publication. For each author, I constructed a "research trajectory" by collecting and chronologically ordering their affiliation history. 