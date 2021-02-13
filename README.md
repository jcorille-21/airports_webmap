# US Airports Webmap
**Made by: Jerome Orille**
**Date: February 12th, 2021**

## Introduction
This project maps out airports in the United States.
This is a choropleth map that measures the number of airports per state.
The labels also indicate whether or not the airport has a cell tower.

## Code Functionality
- Uses Leaflet to make a map, add in a basemap, a scale and a legend
- Uses a custom CSS spreadsheet to style the legend
- Uses Google API fonts to set a custom legend font
- Creates airplane markers and state polygons using ajax by loading in GeoJSON files
- Customizes airplane markers with Font-Awesome
- Uses color ramps from Chroma
- Appends colors to airplane markers using Jquery
- Sets maximum bounds to focus only on the United States [(credit here)](https://stackoverflow.com/questions/28117281/show-only-united-states-when-using-leaflet-js-and-osm)

## Libraries
- Leaflet (css, js and ajax libraries)
- Font-Awesome
- Google API fonts
- Jquery
- Chroma

## Data Sources
Airport data is from USGS, US state data is from [Mike Bostock](http://bost.ocks.org/mike) of [D3](http://d3js.org/).