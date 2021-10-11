---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/HomePageHeadPic.jpg
  overlay_filter: rgba(34, 36, 33, .7)
excerpt: > # text on the header image
  <br />A passionate GIS analyst, data analyst, and artist, committed to exploring data, communicating information with plots and maps.<br /><br />
  <small><i class="fas fa-fw fa-envelope"/><a href="mailto:shangbin.tang@outlook.com"> shangbin.tang@outlook.com</a></small>

intro: 
  - excerpt: ''

feature_row1:
  - image_path: /assets/images/project_collection.jpg
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
    url: "/tags/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
---
{% include feature_row id="intro" type="center" %}
{% include feature_row id="feature_row1" type="left" %}
{% include feature_row id="feature_row2" type="right" %}
{% include feature_row id="feature_row3" type="left" %}
