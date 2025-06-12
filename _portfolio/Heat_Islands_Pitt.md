---
title: "Man, It's Cool in the Park"
order: 1
excerpt: "A remote sensing image analysis project, focusing on the urban heat islands, and cooling effect of vegetation and green spaces in Pittsburgh."
layout: single

header:
  overlay_image: /assets/images/project_collection/UrbanHeatIslandPitt/UHI_header.jpg
  overlay_filter: rgba(0, 20, 0, .6)
  teaser: /assets/images/project_collection/UrbanHeatIslandPitt/OneDayTemperature_Pitt_trimmed.jpg
sidebar:
  - title: "Category"
    text: "Personal project"
gallery1:
  - url: /assets/images/project_collection/UrbanHeatIslandPitt/GoundSurfaceTemp.jpg
    image_path: /assets/images/project_collection/UrbanHeatIslandPitt/GoundSurfaceTemp.jpg
    alt: "Ground surface temperature"
  - url: /assets/images/project_collection/UrbanHeatIslandPitt/NDVI.jpg
    image_path: /assets/images/project_collection/UrbanHeatIslandPitt/NDVI.jpg
    alt: "NDVI"
  - url: /assets/images/project_collection/UrbanHeatIslandPitt/UHIwithLegnd.jpg
    image_path: /assets/images/project_collection/UrbanHeatIslandPitt/UHIwithLegnd.jpg
    alt: "UHI"
  - url: /assets/images/project_collection/UrbanHeatIslandPitt/NDVIvsUHI.jpg
    image_path: /assets/images/project_collection/UrbanHeatIslandPitt/NDVIvsUHI.jpg
    alt: "NDVI vs UHI"
gallery2: # UHI vs Pop
  - url: /assets/images/project_collection/UrbanHeatIslandPitt/PopDensity.jpg
    image_path: /assets/images/project_collection/UrbanHeatIslandPitt/PopDensity.jpg
    alt: "Pop density"
  - url: /assets/images/project_collection/UrbanHeatIslandPitt/AverageHeatIslad_Pitt2.jpg
    image_path: /assets/images/project_collection/UrbanHeatIslandPitt/AverageHeatIslad_Pitt2.jpg
    alt: "Average UHI index"
  - url: /assets/images/project_collection/UrbanHeatIslandPitt/Major Heat Island_2.jpg
    image_path: /assets/images/project_collection/UrbanHeatIslandPitt/Major Heat Island_2.jpg
    alt: "Average UHI index vs Pop density"    
CoolingEffect:
  - url: /assets/images/project_collection/UrbanHeatIslandPitt/CoolingEffect.jpg
    image_path: /assets/images/project_collection/UrbanHeatIslandPitt/CoolingEffect.jpg
    alt: "Cooling effect of sampled parks"
---
<p style="color:grey;"><em>Key words: Remote sensing,  Urban heat island, NDVI, Data visualization</em></p>

The heatwaves in urban areas can be quite disturbing, especially during the summer. It influences our lives from aspects like mental state, physical health, and urban pest control. In this project, I collected a series of satellite remote sensing images of Pittsburgh city area to analyze the urban heat island phenomenon and the cooling effect of green spaces.<br><br>

### Urban heat island effect and vegetation

The <a href="https://en.wikipedia.org/wiki/Urban_heat_island" target="_blank">urban heat island</a> effect is a phenomenon that refers to the urban area's temperature is higher than which of the suburban areas. By processing the remote sensing images that cover every season, I extracted and calculated the ground surface temperature, normalized difference vegetation index (an index that evaluates the growing status of vegetation), and urban heat island index. 

{% include gallery id="gallery1" caption="Figure 1. Ground surface temperature extracted<br>Figure 2. Normalized Difference Vegetation Index (NDVI) <br> Figure 3. Urban Heat Island (UHI) index<br>Figure 4. Correlation coefficient between NDVI and UHI"%}

Results show that the urban heat island effet is more obvious during summer and winter. During summer, the strong negative correlation between the vegetation's growing condition and urban heat island effect suggests that plants can cool down and patially cancel the heat.

### Heat islands and cool zones
{% include gallery id = "gallery2" caption = "Figure 5. Population density of Pittsburgh (by neighborhood)<br>Figure 6. Average UHI index in PIttsburgh<br> Figure 7. Major heat island areas in Pittsburgh"%}
Construction materials such as cement, concrete, and asphalt make high population density areas such as commercial and residential areas into heat islands.<br><br>
Meanwhile, the park is usually 1.5 to 6 <span>&#8451;</span> (2.7 to 10.8 <span>&#8457;</span>) cooler than its surroundings due to the existence of a large amount of vegetation; they can also reduce the temperature within 150 to 200 meters (492 to 656 feet)of the surrounding area.
{% include gallery id = "CoolingEffect" caption = "Cooling effect of sampled parks in Pittsburgh"%}