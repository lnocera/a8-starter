# DSCI 554 Assignment 8

## Description

In this assignment you will create 4 maps:

1. Using countries from assignment 1 and UN data of your choice, build a proportional symbol map
2. Using countries from assignment 1 and UN data of your choice, build a choropleth map
3. Using data of your choice from the [County of Los Angeles Open Data website](https://data.lacounty.gov/browse?limitTo=maps&utf8=%E2%9C%93) build a D3 map.
4. Using data from [geohub.lacity.org](geohub.lacity.org) build a Mapbox map showing occupancy for all building footprints in UPC.

Use separate files (html, js, css) for each map and create links in `index.html`.

## Rubric

__15% of the grade is for artifacts generated as part of the lab.__

### Development (5 pts)

| Quality       | Points | Description |
| ------------- | ------ | ----------- |
| Sophisticated | 4-5    | Good development practices are demonstrated. Using node. Page(s) render without errors. Pages are well formatted with a proper layout. The maps are well documented, include labels, legend, and title as appropriate. |
| Competent     | 2-3    | Good development practices are not well demonstrated. Not using node. Page(s) render with errors. Pages are not well formatted with a proper layout. The maps are not well documented, include labels, legend, and title as appropriate. |
| Needs work    | 0-1    | Good development practices are not demonstrated. Not using node. Page(s) do not render or render with errors. Pages are not formatted with a proper layout. The maps are not documented, include labels, legend, and title as appropriate. |

### Proportional symbol map (5 pts)

Using countries from assignment 1 and UN data of your choice, build a Proportional symbol map.

| Quality       | Points | Description |
| ------------- | ------ | ----------- |
| Sophisticated | 4-5    | Map data is well formatted in TopoJSON, using appropriate projection. Data is well formatted and imported. D3 data join is well used. Colors, labels, title and legend are well formatted and used, scales are well used. |
| Competent     | 2-3    | Map data is not well formatted in TopoJSON, not using appropriate projection. Data is not well formatted and imported. D3 data join is not well used. Colors, labels, title and legend are not well formatted and used, scales are not well used. |
| Needs work    | 0-1    | Map data is not formatted in TopoJSON, not using appropriate projection. Data is not formatted and imported. D3 data join is not used. Colors, labels, title and legend are not formatted and used, scales are not used. |

### Choropleth map (5 pts)

Using countries from assignment 1 and UN data of your choice, build a choropleth map.

Same rubric as the Proportional Symbol Map.

### Los Angeles County map (5 pts)

Using data of your choice from the [County of Los Angeles Open Data website](https://data.lacounty.gov/browse?limitTo=maps&utf8=%E2%9C%93) build a D3 map. Map should be in __projected TopoJSON__ format. You can map the data in the TopoJSON or map it in the page.

Same rubric as the Proportional Symbol Map.

### Mapbox Building Footprints Map (5 pts)

Using Mapbox create a map showing all building footprints for USC UPC. Use data from [geohub.lacity.org](geohub.lacity.org). Generate a synthetic dataset where each building footprint encodes occupancy data (number of people a building can allow). Encode occupancy using a color scale and show it on the map. You can work within your project group to generate the footprint file and mock the occupancy data.

| Quality       | Points | Description |
| ------------- | ------ | ----------- |
| Sophisticated | 4-5    | Map data and occupancy data are well formatted. Labels, title and legend are well formatted and used, scales are well used. |
| Competent     | 2-3    | Map data and occupancy data are not well formatted. Labels, title and legend are not well formatted and used, scales are not well used. |
| Needs work    | 0-1    | Map data and occupancy data are not formatted. Labels, title and legend are not formatted and used, scales are not used. |

## Homework Guidelines

- Homework repository must be updated before the deadline
- Commits after the deadline will not be considered unless requested
- Late policy: 10% of total available points per each late day; duration less than 24 hours counts as one whole day
- Homework is expected to work in CHROME
