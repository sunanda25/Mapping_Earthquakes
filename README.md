# Mapping_Earthquakes
## Overview
A non-profit company has offered me a position as a data visualization specialist in the disaster reporting network. The company’s mission is to provide data-driven stories about disasters around the world. My role is to build a website to visualize interactive features on earthquakes around the world. To support the website and mobile application, the latest earthquake Geo JSON data will be used from the US Geological Survey website. By using JavaScript, D3, and Leaflet library, the past week's earthquake data will be retrieved and plotted on a Mapbox map. As part of this challenge information related to earthquakes will be shown using different styles of maps.

## Summary
The earthquake map is plotted using 2 different map styles along with an earthquake overlay. Using the two styles of maps, the tectonic plate’s location on earth and earthquakes with a magnitude greater than 4.5 need to be plotted. An additional two overlays will be created to show Tectonic plates and Major Earthquakes.

### 1.  Tectonic Plate Data
Tectonic plate data is sourced from a GitHub user who uploaded a GeoJSON file containing the boundaries of tectonic plates around the world and has been imported using d3. JSON (). After importing this data, JavaScript, Leaflet.js, and GeoJSON have been used to plot the data as a LineString. Adding tectonic plate data as an additional layer to the earthquake map allows a user to toggle between earthquake data and tectonic plate data. The data can be viewed using both Street and Satellite views. 

![image](https://user-images.githubusercontent.com/76491891/119263680-166edd00-bbae-11eb-850a-a655f3201b0b.png)

### 2.  Major Earthquake Data
Major earthquake data for the past 7 days is sourced from the US Geological Survey website and has been imported using d3. JSON (). After importing this data, JavaScript, Leaflet.js, and GeoJSON have been used to plot the data as a Circle. The color of the circle varies based on the magnitude of the earthquake. Each circle has a popup to display the location and magnitude of the earthquake. Adding major earthquake data as an additional layer to the earthquake map allows a user to toggle between major earthquake data, earthquake data, and tectonic plate data. The data can be viewed using both Street and Satellite views. 

![image](https://user-images.githubusercontent.com/76491891/119263716-2f778e00-bbae-11eb-8ec8-87db066f86ad.png)

### 3.  Additional Map Style
A light view map style is added using Mapbox as an additional style. Data related to the earthquake, Tectonic plates, and Major earthquakes data can all be seen on this new map style.

![image](https://user-images.githubusercontent.com/76491891/119263729-3bfbe680-bbae-11eb-8e4b-ea64caa55187.png)
