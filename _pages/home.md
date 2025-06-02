---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/HomePageHeadPic.jpg
  overlay_filter: rgba(34, 36, 33, .7)
excerpt: > # text on the header image
  <br />Collaborative research data analyst with a focus on healthcare, geospatial, and population-level data.<br><br>Skilled in building reproducible analytics workflows and translating complex data into actionable insights that support public health research, resource planning, and evidence-based decision-making.<br><br>
  <small><i class="fas fa-fw fa-envelope"/>&nbsp;<a href="mailto:shangbin.tang@outlook.com"> shangbin.tang@outlook.com</a></small><br>
  <small>&nbsp;<i class="fas fa-file-pdf"></i>&nbsp;&nbsp;<a href="/assets/Resume_ShangbinTANG_version20250512.pdf" target="_blank"> Resume</a></small>

intro: 
  - excerpt: ''

feature_row1:
  - image_path: /assets/images/project_collection2.jpg
    alt: "Portfolio"
    title: "Portfolio"
    excerpt: "Take a look at these interesting projects, including data mining, data visualization, spatial analysis, network analysis, and remote sensing image processing & analysis. Some of them helped and are still helping with the COVID-19 vaccine allocation."
    url: "/portfolio/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
feature_row2:
  - image_path: /assets/images/publication_collection.jpg
    alt: "Publications"
    title: <div align="left">Publications</div>
    excerpt: <div align="left">My published works.</div>
    url: "/publications/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
feature_row3:
  - image_path: /assets/images/art_collection.jpg
    alt: "Arts"
    title: "Arts"
    excerpt: "Vision is the easiest and most powerful way for us to understand and communicate with the world, and it is also my favorite way to record moments."
    url: "/arts/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
---
{% include feature_row id="intro" type="center" %}
{% include feature_row id="feature_row1" type="left" %}
{% include feature_row id="feature_row2" type="right" %}
{% include feature_row id="feature_row3" type="left" %}
