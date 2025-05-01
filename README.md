# Massachusetts Hazardous Waste and Oil Sites Map

## Project Overview
This web application provides an interactive map visualization of MassDEP (Massachusetts Department of Environmental Protection) Oil and/or Hazardous Material Sites with Activity and Use Limitations. The map allows users to explore and identify locations across Massachusetts where there are environmental concerns or restrictions.

## Features
- Interactive Mapbox GL JS map centered on Massachusetts
- Clickable points representing hazardous waste and oil sites
- Popup information displaying:
  - Site name
  - Site address 
  - Town location
- Custom map styling using Mapbox Studio
- Responsive design with clean user interface

## Technical Details
- Built using Mapbox GL JS v3.3.0
- HTML5/CSS3 for structure and styling
- Pure JavaScript for interactivity
- Uses Mapbox's custom styling and tiling system
- Responsive layout that works across different screen sizes

## Map Features
- Initial view centered at coordinates: [-71.70, 42.393748]
- Default zoom level: 8
- Custom map style using Mapbox Studio style URL
- Interactive layer: 'massdep-oil-and-or-hazardous-bgt474'

## Usage
To view the map:
1. Open the HTML file in a web browser
2. Click on any point on the map to view site details
3. Information will appear in a popup showing the site name, address, and town

## Dependencies
- Mapbox GL JS (v3.3.0)
- Mapbox GL CSS (v3.3.0)
- Valid Mapbox access token (required)

## Note
This project requires a valid Mapbox access token to function. The token should be kept secure and not shared publicly. 