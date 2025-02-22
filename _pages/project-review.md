---
title: "Project Review"
layout: page
category: "Essay"
date: 2025-02-23
permalink: /project-review/ # The URL for this page
showcase: false # Set to false to hide from portfolio page
description: >
  Project review for HIST 4261/5261: Working With Data
---

## Project Overview

[“The Lines That Shape Our Cities”](https://storymaps.arcgis.com/stories/0f58d49c566b486482b3e64e9e5f7ac9) is a StoryMaps project that connects current environmental disparities within cities to historic neighborhood designations that often segregated these cities. Combining historic neighborhood evaluations by the HOLC (Home Owners Loan Corporation) in the 1930s with GIS data, the Digital Scholarship Lab at the University of Richmond, the Science Museum of Virginia, and Esri (a GIS software company) collaborated in 2020 to use maps to argue that 1930s neighborhood designations left a legacy of environmental difficulties today. This is significant because such environmental conditions, like less tree coverage, have adverse effects on people’s health and well-being. The project specifically narrowed their story to four cities, highlighting one environmental condition for each to emphasize the inequity.

## Data and Evidence

[The University of Richmond’s “Mapping Inequality” project](https://dsl.richmond.edu/panorama/redlining/introduction) compiled the data from the HOLC’s neighborhood designations in the 1930s, providing maps with the grade (A-D) of the neighborhoods. 
<div align="center">
  <p><img src="/assets/img/designation_example.png" style="width: 60%;" /></p>
</div>
These maps were overlaid with data collected through GIS imagery, including a heat map, tree, map, and map showing impervious surfaces (or artificial construction) throughout cities. For instance, in the image below one can compare the heat distribution on July 19, 2020 in St. Louis to a neighborhood’s designated grade from the HOLC.

<div align="center">
  <p><img src="/assets/img/heat_map_overlay.png" style="width: 50%;" /></p>
</div>
The boundaries of the HOLC’s neighborhood designations were also combined with demographic data to create a snapshot of economic inequalities between grades of neighborhoods.

<div align="center">
  <p><img src="/assets/img/demographic_example.png" style="width: 60%;" /></p>
</div>

It is important to note that this project focused on data that would highlight the differences between neighborhood designations, showing that people in “D” graded neighborhoods live worse lives than those in “A” graded neighborhoods even 80 years after the original designation. This data was not only deliberately chosen among many options but also reduces these people’s lives to statistical averages without highlighting people’s experiences and humanity across these neighborhoods. While the project enhances environmental statistics with descriptions of their impact, these impacts - like “characteristically higher levels of pollution,…higher energy bills,…chronic respiratory symptoms, and even pre-term birth” - are also conclusions from statistics, creating a story of averages. Ironically, using data in this way can serve to perpetuate the HOLC’s negative neighborhood classifications, despite the fact that the authors push back on the often racially motivated and unfair methods initially implemented.

## Design and Communication

Using StoryMaps, the Esri team created a way to easily navigate their data and story, despite the fact that the story included many sections. Since this project is associated with teacher resources on the “Mapping Inequality” site, such easy navigation is essential to be able to reach a student audience. Additionally, the inclusion of a video to vary the media forms is important for a student audience, hoping to reach a variety of learning styles.

StoryMaps enables readers to receive information in bite-sized pieces, giving them time to digest arguments and focus on important parts of the data. For example, in analyzing the impervious area map in Fort Wayne, the authors zoomed into a specific part of the map with an accompanying description to help the reader understand the inequality. Such design choices are especially important when working with GIS imagery, when the immediate analysis may be more difficult to interpret. 
<div align="center">
  <p><img src="/assets/img/zoom_example.png" style="width: 75%;" /></p>
</div>
That said, the design also enables the reader to explore the maps at their leisure. For instance, while the project highlighted portions of the heat map in St. Louis to accompany their argument, the reader could zoom in and out and determine for themselves the heat distribution throughout neighborhoods.

This choice helps provide agency to users, but it also lets readers find inconsistencies within the data and argument. For instance, when looking at the heat map of St. Louis, one can find many “D” neighborhoods with cooler temperatures and many “A” neighborhoods with warmer temperatures. While data is never neat, the fact that the authors do not address these examples makes their argument weaker because one wonders the extent to which they cherry picked their information to support their point. While the breakdown of impervious area by percentage was helpful in addressing the outliers in Fort Wayne, the argument would have been stronger with such explanations for all cities.
<div align="center">
  <p><img src="/assets/img/percent_example.png" style="width: 75%;" /></p>
</div>

## Correlation or Causation?

Overall, this project attempted to show that unequal and often racist designations of neighborhoods in the past left a legacy today where those neighborhoods are still experiencing worse conditions, particularly environmentally. The visual data in the project drew a connection between the historic neighborhood ratings and their current environmental conditions, enhanced through the explanations of problems associated with certain environmental conditions. However, the underlying cause of the correlation between “D” rated neighborhoods and worse environmental conditions was not immediately clear through the project’s argument. While the “brief history” section addressed the impact of the neighborhood designations on racial segregation and bank loans, there was no explanation about why such actions would have created the unequal environmental conditions that we see today. While visually and experientially appealing, this project missed a unique opportunity to show the consequences of creating data itself. However, instead of highlighting this throughline, it left the reader to assume a story through simple correlations. 

This project review was published on {{ page.date }} and falls under the category of: {{ page.category }}.
