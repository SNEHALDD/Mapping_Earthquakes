# Mapping_Earthquakes

## Purpose
Create earthquake map with two different maps and the earthquake overlay. Show earthquake data in relation to the tectonic plates’ location on the earth, and show the earthquakes with a magnitude greater than 4.5 on the map. Additionally, show the data on a third map.


## Analysis and Results:

### Deliverable 1 : Add Tectonic Plate Data
After passing the "GeoJSON/PB2002_boundaries.json" data, added style to the lines with a color and weight. The results shown below.


### Deliverable 2 : Add Major Earthquake Data
- Used data from "https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson". 
- Used functions such as "getColor()" and " getRadius()"
- In "getColor()" function, only 3 colors have been used for 3 magnitudes such as magnitude less than 5, a magnitude greater than 5, and a magnitude greater than 6.
Figure of the getcolor() :
- Changes in geoJSON 
	- Turned each feature into a circleMarker on the map
	- Styled each circle with styleInfo() function
	- Created a popup for the circle to display the magnitude and location of the earthquake
	Figure of geoJSON file:
- Map showing major earthquake layer and data is as follows:

### Deliverable 3 : Add an Additional Map
With the help of "https://docs.mapbox.com/api/maps/styles/", added one more map which is "dark mode" in map. 

