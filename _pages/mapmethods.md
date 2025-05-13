---
layout: page
title: Map Methodology
permalink: mapmethods
show-title: true
---

# The Tools

## ARCGIS

![Home Page of the ArcGIS website](/img/GISHomepage.png)

ArcGIS Online is a cloud-based platform that allows users to utilize the ARCGIS toolset exclusively in a browser. The main feature I focused on was the ability to create an interactive web map using the data that I had gathered. The tool allows users to plot points and then connect them using lines all through a sketch layer. While the tool does allow for pattern recognition, trend modeling, and advanced calculations, they were not needed to help complete the project.

## Map Warper

![Home Page of the Map Warper website](/img/MapWarperHome.png)

Map Warper is a free, open-source tool designed for georectifying and georeferencing historical maps and images. A lot of the maps I gathered were made for the purpose of readability and clarity rather than being to scale geographically. Map Warper allows users to upload their own maps and create rectified versions which are aligned with real world coordinates. Doing so would then allow me to import the maps into ArcGIS to use as layers to help create my sketch layers in the end product.

![A map that has been rectified by map warper](/img/91017.png)

---

# The Method

The first step was to gather a large amount of maps. This involved using both online archives as well as the Burns Library directly. I tried to prioritize maps found by the burns as they could easily provide high quality scans as well as already having physical copies as maps I already found online. Initially, I thought I would only need one map to base my sketch layer off of. I quickly learned that a lot of maps, especially during the early years, didn't necessarily agree with each other. It was then important to collect a large collection of maps so that I could see what they all agreed and disagree on. Based on that, I could use the multiple maps to populate my layer with all of the stations.

| ![Stephen De Riel's map of 1850s US Railroads](/img/1850TrainsUS.png) | ![Map of MBTA Public Data from 2024](/img/MBTA2025Data.png) |
| Stephen De Riel's map of 1850s US Railroads | Map of MBTA Public Data from 2024 |

Another thing that was useful was finding two major sources of data that would help bookend the era I was studying. The first was a map created by another BC student, Stephen De Riel, of the US railroad maps in the 1850s. The West End Street Rail was founded in 1887 so not too far off so as to be unusable. The second was finding publicly available GIS friendly data from the MBTA that allowed me to create a layer that was the most up to date MBTA lines and stations at the time.

![MBTA map that has been rectified by map warper](/img/60402.png)

As mentioned in the map warper section, a lot of maps made for public transporation networks aren't built to proper geographic scale. While it does make them more readable to the passengers, it makes them unusable in their current state for the project. To fix this, I would import each map to map warper, match points on that map to a real GPS map, then the website would stretch and warp the map image to fit directly on top of said GPS map. The website then allows you to either export the map as an image or as a file with coordinate data which could be imported directly as an image layer into ArcGIS.

![Three images showing how map warper can turn a map into one that can be placed on top of a GPS map](/img/MapWarperProcess.png)

After all of my maps were imported, I would then layer them on top of the map one by one and build a sketch layer on top. This included plotting stations as points and tracks as lines. Once I had all of the differently sketched out map laters, I would compare all of the points with the real GPS map to see where defunct stations used to be or where the modern MBTA station now rested. Having the two bookend layers of the US 1850 railroads and the modern MBTA station data also helped refine the placement of points.

With all of the points placed, the map is complete for now!