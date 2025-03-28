# HealthFacilities

# Created by Edgar Castillo-Ramos

## Map of Veteran's Affairs Health Offices

#### Background
Having family members who have served in the armed forces I created this map as a way to provide information for those out of deployment/in the reserves. 

### Languages

- HTML
- JavaScript
- CSS

### Plugins

- Leaflet
- Ajax
- JQuery

## Instructions
This map is a choropleth map meaning that each color shade corresponds to a group of numbers. The lighter and greener the color corresponds to a lower amount of healthcare facilities in the state, and vice versa for darker blue colors. 
Clicking on a state displays the locations of each facility within that state. Hovering over the point displays a box containing information about the facility that includes:
- Address
- Address2 (if applicable)
- City
- County
- Zip
- Directions (if applicable)
- Phone
- NAISC Description (if applicable
## Data 
U.S Department of Homeland Security. (2020). Veterans Health Administration Medical Facilities. https://hifld-geoplatform.opendata.arcgis.com/datasets/veterans-health-administration-medical-facilities
*alt data link* https://hifld-geoplatform.hub.arcgis.com/datasets/f11d7d153bfb408f85bd029b2dac9298_0/explore
Leaflet
Cheng J, Schloerke B, Karambelkar B, Xie Y (2025). leaflet: Create Interactive Web Maps with the JavaScript 'Leaflet' Library. R package version 2.2.2.9000, https://github.com/rstudio/leaflet, https://rstudio.github.io/leaflet/. 

Copyright (c) 2024, MapTiler.com & OpenMapTiles contributors.
Copyright (c) 2015, CartoDB Inc.
All rights reserved.

Derived from "CartoDB Basemaps" (https://github.com/CartoDB/CartoDB-basemaps) designed by Stamen and Paul Norman for CartoDB Inc., licensed under CC-BY 3.0.

##### Known Issues
The most prevalent issue regarding the map had to do with displaying the points. Clicking on a state displays points both in and certain points in surrounding states. As it does not affect map usage, however, it does not need to be rectified. 
