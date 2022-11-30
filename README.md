# Mapping_Earthquakes

In this project I created interactive maps. To do so, I used Leaflet.js library, Javascript, and HTML to retrieve earthquake information from a GeoJSON file.

To do it an interactive Map, I did ....:
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
- All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or of


Overview
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. We wrote a script to pull the GeoJSON earthquake data from the USGS website to retrieve the geographical coordinates and magnitudes of earthquakes for the last seven days. The data is then added to a map. Since the information is linked to a real-time source, the map will update whenever the user accesses it. Scripts are built using JavaScript and D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. We then used Leaflet library to plot the data on a Mapbox style map through an API request and made it interactive by adding visualization for different map styles, creating layers to display Tectonic plates, Earthquake magnitude and location information.

