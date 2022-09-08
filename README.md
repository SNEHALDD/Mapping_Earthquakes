# Mapping_Earthquakes

## Purpose
Create earthquake map with two different maps and the earthquake overlay. Show earthquake data in relation to the tectonic plates’ location on the earth, and show the earthquakes with a magnitude greater than 4.5 on the map. Additionally, show the data on a third map.


## Analysis and Results:

### Deliverable 1 : Add Tectonic Plate Data
After passing the "GeoJSON/PB2002_boundaries.json" data, added style to the lines with a color and weight. The results shown below.
<img width="1673" alt="Techtonic_plate" src="https://user-images.githubusercontent.com/106944351/189177254-7a524227-ba40-441e-85d5-397b9882578f.png">

### Deliverable 2 : Add Major Earthquake Data
- Used data from "https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson". 
- Used functions such as "getColor()" and " getRadius()"
- In "getColor()" function, only 3 colors have been used for 3 magnitudes such as magnitude less than 5, a magnitude greater than 5, and a magnitude greater than 6.
Figure of getcolor() :
<img width="301" alt="getColor()" src="https://user-images.githubusercontent.com/106944351/189177305-08acc96c-d527-40fe-92d7-e324a19824ad.png">

- Changes in geoJSON 
	- Turned each feature into a circleMarker on the map
	- Styled each circle with styleInfo() function
	- Created a popup for the circle to display the magnitude and location of the earthquake
	Figure of geoJSON file:
	<img width="993" alt="geoJSON_Major_earthquake" src="https://user-images.githubusercontent.com/106944351/189177581-1b73e980-4687-44dd-b75d-0ac9d8135135.png">

- Map showing major earthquake layer and data is as follows:
<img width="1675" alt="Major_Earthquake" src="https://user-images.githubusercontent.com/106944351/189177350-ce3dcf72-c20b-4c47-86da-d53289f23295.png">

### Deliverable 3 : Add an Additional Map
With the help of "https://docs.mapbox.com/api/maps/styles/", added one more map which is "dark mode" in map. 
<img width="1671" alt="Additional_map" src="https://user-images.githubusercontent.com/106944351/189177382-5270c7b6-aadf-4d5b-b48c-8312df515464.png">

