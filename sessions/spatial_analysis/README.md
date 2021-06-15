---
title: "Mapping Session"
author: "Juliano Palacios Abrantes (*Adapted from T. Cashion*)"
date: '2019-11-06'
output:
  html_document:
    keep_md: yes
  pdf_document: default
---


# Introduction to session

This session will look at how to make maps with *R*. As allays, there are many ways to create a map in *R* and some of them are better than others. I actually started using the `rgdal` and `sp`packages. However, with the new `sf`package, life is so much easier and faster. So for this session I'll focus on the `sf`package. If you're interested in the other versions you can find a tutorial on the [IOF-DSDS site](https://github.com/timcashion/studyGroup/tree/gh-pages/lessons/Intro_Map).

# Objectives

Create a map from scratch either for showing your study site or showing data.

# Instructions

1. **Session Materials:** Push the repository for the most updated version. 

2. **Data:** Download the following data set and save it on your `Data` folder

- [FAO Regions](http://www.fao.org/figis/geoserver/area/ows?service=WFS&request=GetFeature&version=1.0.0&typeName=area:FAO_AREAS&outputFormat=SHAPE-ZIP)


3. **Necessary Packages:** Please make sure you run the first chunk of the `Making_Maps.rmd` before the session or that you have installed the following packages:

- `tidyverse` 
- `sf`, for loading shapefiles
- `tools`, for loading shapefiles
- `sp`, for loading and manipulating shapefiles
- `here`, for easy paths
- `rnaturalearth`, for accessing maps online
- `viridis`, this is a package that provides color-blind friendly pallets



# References and help!
- Test out colors and get advice for color-blind/print friendly maps: 
  http://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3
- [Marine Regions](http://www.marineregions.org/downloads.php) Website
- [FAO Shapefiles](http://www.fao.org/figis/geoserver/web/)
- [Spatial manipulation with sf: : CHEAT SHEET](https://wch.github.io/latexsheet/latexsheet.pdf)
- A more complete tutorial from Jamie Afflerbach & Jeanette Clark (NCEAS) on [spatial analysis in R](https://github.com/eco-data-science/spatial-analysis-R)

