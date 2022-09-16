# Mapping_Earthquakes
Creating interactive maps using the Leaflet.js Application Programming Interface (API) to populate a geographical map with GeoJSON earthquake data from a URL.

## Background
### Overview
This project consists of three technical analysis deliverables.

- Deliverable 1: Add Tectonic Plate Data

- Deliverable 2: Add Major Earthquake Data

- Deliverable 3: Add an Additional Map

### Purpose

The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.


## Methodology

- Used JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. 

- Used Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

## Resources
 
Data source:
- (1) major_eq_starter_logic.js, (2) challenge_logic.js, (3) chart.js
 
Software:
- Visual Studio Code 1.68.1, HTML, CSS, Bootstrap and JavaScript
 
<br/>

### Results

Using JavaScript, Leaflet, and D3, we re-factored the code of our index.html file to create an interactive earthquake map as shown in image (a, b and c).

<br/>


(a)![Streets_map](./Earthquake_Challenge/Resources/images/street_map.png)
 
<sub> Figure (a) Streets_Earthquakes_maps

<br/>

(b)![Satellite_map](./Earthquake_Challenge/Resources/images/satellite_map.png)
 
<sub> Figure (b) Satellite_Earthquakes_maps

<br/>

(c)![Dark_map](./Earthquake_Challenge/Resources/images/dark_map.png)
 
<sub> Figure (c) Dark_Earthquakes_maps

<br/>


## Summary

- We created our earthquake map with two different maps (Fig a, b) and the earthquake overlay. Then we added the earthquake data in relation to the tectonic plates’ location on the earth, the earthquakes with a magnitude greater than 4.5, and we added the data on a third map (Fig c).

     - [index.html](https://l-aldarondo.github.io/Mapping_Earthquakes/)

<br/>

## References

[Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
 
[Earthquake data](https://earthquake.usgs.gov/)
 
[Mapbox](https://docs.mapbox.com/api/maps/styles/)

[Leaflet](https://leafletjs.com/examples/quick-start/)
