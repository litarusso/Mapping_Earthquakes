# Mapping_Earthquakes
## Overview of the Analysis
In this projects aims to do interactive maps about earthquakes in the world for last seven days. To do so, I used Leaflet.js library, Javascript, and HTML to retrieve earthquake information from a GeoJSON file.

### My working steps are below:
- The tectonic plate data is added as a second layer group
- The tectonic plate data is added to the overlay object
- The d3.json() callback is working and does the following
 - The tectonic plate data is passed to the geoJSON() layer
 - The geoJSON() layer adds color and width to the tectonic plate lines
 - The tectonic layer group variable is added to the map
- The major earthquake data is added as a third layer group 
- The major earthquake data is added to the overlay object
- The d3.json() callback is working and does the following:
    - Sets the color and diameter of each earthquake.
    - The major earthquake data is passed to the geoJSON() layer.
    - The geoJSON() layer creates a circle for each major earthquake, and adds a popup for each circle to display the magnitude and location of the     earthquake
- The major earthquake layer group variable is added to the map
- All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off

## Summary
In the Maps below, you can see the interactive projects with three base maps and three options.

![Screen Shot 2022-11-30 at 11 40 52 AM](https://user-images.githubusercontent.com/111788394/204863825-827da64e-d630-4869-8acc-17ae316224e8.png)
![Screen Shot 2022-11-30 at 11 41 19 AM](https://user-images.githubusercontent.com/111788394/204864018-4c9c2b4e-73e7-42a5-b8d9-aeb99de46e11.png)
![Screen Shot 2022-11-30 at 12 15 51 PM](https://user-images.githubusercontent.com/111788394/204864536-fb16588d-f70c-4ede-a390-40dacf0b35cc.png)

