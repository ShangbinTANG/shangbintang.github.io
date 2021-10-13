---
title: Is It Easy for Everyone to Get COVID-19 Vaccine?
excerpt: A GIS analysis assesses the accessibility of potential COVID-19 vaccine administration facilities to the public before mass distribution of vaccines.
layout: single
#classes: wide
header:
  overlay_image: /assets/images/project_collection/Project_VaxMap/ProjectVaxMap_header_v1.jpg
  teaser: /assets/images/project_collection/Project_VaxMap/teaser - copy.jpg
  #overlay_filter: rgba(0, 0, 0, .8)
sidebar:
  - title: "Authors"
    text: "Lucas A. Berenbrok, Shangbin Tang, Kim C. Coley, Cristina Boccuti, Sean Dickson, and Inmaculada Hernandez" 
  - title: "Role"
    text: "GIS Analyst"
  - title: "Responsibilities"
    text: "Performing the GIS analysis and data analysis, designing and generating maps and plots"
gallery1: # big map
  - url: /assets/images/project_collection/Project_VaxMap/CoVax Big Map.jpg
    image_path: /assets/images/project_collection/Project_VaxMap/CoVax Big Map.jpg
    alt: "Accessibility of potential COVID-19 vaccine administration facilities"
gallery2: 
  - url: /assets/images/project_collection/Project_VaxMap/FacilityDensity_noTitle.jpg
    image_path: /assets/images/project_collection/Project_VaxMap/FacilityDensity_noTitle.jpg
    alt: "facility density (per 10,000 residents) (county-level)"
  - url: /assets/images/project_collection/Project_VaxMap/AverageDist_noTitle.jpg
    image_path: /assets/images/project_collection/Project_VaxMap/AverageDist_noTitle.jpg
    alt: "mean driving (network traveling) distance from to closest facility"
  - url: /assets/images/project_collection/Project_VaxMap/Pct Further 10 miles title 14_noTitle.jpg
    image_path: /assets/images/project_collection/Project_VaxMap/Pct Further 10 miles title 14_noTitle.jpg
    alt: "proportion of population with driving distance greater than 10 miles from closest facility"
  - url: /assets/images/project_collection/Project_VaxMap/High Risk_vs_elderly_noTitle.jpg
    image_path: /assets/images/project_collection/Project_VaxMap/High Risk_vs_elderly_noTitle.jpg
    alt: "proportion of elderly population with driving distance greater than 10 miles from closest facility"


---
<p style="color:grey"><em>Key words: GIS, COVID-19, Vaccine, Network analysis</em></p>

<p style="margin-top:75px; color:grey">This is a nationwide geospatial analysis that has been published as a white paper and has been quoted by <a href="https://www.nytimes.com/2021/02/18/world/us-coronavirus-vaccine-minorities.html?smid=tw-share" target="_blank"> NY Times</a>, <a href="https://www.npr.org/2021/02/05/962946721/across-the-south-covid-19-vaccine-sites-missing-from-black-and-hispanic-neighbor" target="_blank"> NPR</a>, CNN(<a href="https://www.npr.org/2021/02/05/962946721/across-the-south-covid-19-vaccine-sites-missing-from-black-and-hispanic-neighbor" target="_blank"> story 1: America's biggest cities face racial inequities in vaccine distribution</a>, <a href="https://edition.cnn.com/2021/03/02/health/rural-pharmacy-deserts-covid-vaccines-khn/index.html" target="_blank">story2: Rural Americans in pharmacy deserts hurting for Covid-19 vaccines</a>), <a href = "https://cnnespanol.cnn.com/video/vacunas-covid19-proceso-vacunacion-opciones-para-mejorar-rapidez-acesso-intv-xavier-serbia-cnn-dinero/" target="_blank"> CNN Español</a>, <a href = "https://www.nbcnews.com/health/health-news/inside-chaotic-first-days-effort-vaccinate-america-n1251944" target="_blank">NBC News</a>, <a href = "https://www.politico.com/news/2020/12/18/pharmacies-vaccine-push-unequal-access-448478" target="_blank">Politico</a>, and other medias. </p>


{% include gallery id = "gallery1" caption="" %}

In late 2020, we analyzed the accessibility of potential COVID-19 vaccine providers to the general public. We included community pharmacies that provided immunization services as of October 1, 2020, federally qualified health centers, hospital outpatient departments, and rural health clinics as possible vaccine providers. The population sample is a 1% random sample of UTI's synthetic population based on the 2010 census. 

I used ArcGIS to map out the locations of all potential vaccine facilities and synthetic populations, used network analysis to gain the route and network traveling distance (route length) from each sampled synthetic people to their closest facility, processed the result, and summarized it to state and county level. We also performed a subgroup analysis for people with ages equal to or greater than 65.

{% include gallery id = "gallery2" caption="fig.1 facility density (per 10,000 residents) (county-level)<br>fig.2 average driving (network traveling) distance from to closest facility<br>fig.3 proportion of population with driving distance greater than 10 miles from closest facility<br>fig.4 proportion of population with driving distance greater than 10 miles from closest facility" %}

For more information about this project, please see the <a href="https://www.westhealth.org/wp-content/uploads/2020/12/covid-vaccine-distribution-pharmacy-locations-state-county-west_health-university_pittsburgh.pdf" target="_blank"> Whitepaper</a> and <a href="https://www.westhealth.org/resource/vaxmap-potential-covid-19-vaccine-locations/" target="_blank">Website: VaxMap 2.0: West Health Policy Center and University of Pittsburgh School of Pharmacy Develop County-Level Map of Potential COVID-19 Vaccine Locations</a>