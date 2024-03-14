# Creating Map Animation with Mapbox

[Demo Link](https://codewjoy.github.io/mapbox_animation/)

![map_animation](img/dynamic_map.gif)

## HTML Structure
- `<head>`: Contains metadata for the page, importing the Mapbox GL JS library, and other styles.
- `<body>`: Contains the main content, including the map and console elements.
- `<div id="map">`: Area to accommodate the Mapbox map.
- `<div id="console"`>: Area to display collision data and control elements.

## Concept
- Initializing the Mapbox map: Creating a Mapbox map instance using the provided Mapbox key.
- Loading data layers: Creating a data layer using GeoJSON data to display motor vehicle collision events.
- **Animation effects**: Implementing time-based animation controlled through a slider. The animation speed is adjustable. Use [setInterval() Web API](https://developer.mozilla.org/zh-TW/docs/Web/API/setInterval)
- Filters and interaction: Allowing users to filter data using the slider and selectors to display collision events for specific times and dates.
- Event listeners: Triggering events on slider drag and change, as well as date range selection.

## Reference
[Show changes over time with Mapbox GL JS](https://docs.mapbox.com/help/tutorials/show-changes-over-time/)

