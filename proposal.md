# Kites 'r' Us

Kites are is a real time wind simululation app built and designed to be used by the kite boarding community.  With wind being one of the more dynamically changing weather patterns, it is imperative for kite boarders to have access to real-time information on the current and projected wind patterns.  Kites r us will be a custom map of the continental United States, built by leveraging the U.S. Census Bureau's cartographic boundaries for data and the Geospatial Data Abstraction Library to physically build the borders.  In addition, it will utilize the D3.js library to build a map overlay of current and historical wind conditions.

## MVP

1. Custom built map of the United States.
2. Weather overlay showing real-time changes in weather pattern.
3. Ability to zoom/pan on map
4. Menu bar allowing users to change between weather types, realtime, and historical data views.


## Wireframes

Kites r Us will be an interactive weather app.  At the top of the page will be a button bar, allowing users to toggle between current wind conditions and a historical wind condition view.  A weather/visual overlay will be designed to go on top of the map providing a visual representation of current weather conditions.  For wind, a visual marker will be displayed at the correct lat/long coordinates for weather tracking facilities across the US.  These markers will provide a visual representation of wind speed, direction, and "gustiness".

In addition, a map navigational bar will be to the right of the screen allowing users to zoom in/out and pan around.

![Map Overlay](https://i.imgur.com/RjLDMaG.png)


## Architecture and technologies

1.  Geospatial Data Abstraction Library will be used to draw custom map.
* Lat/long data from the US Census bureau will be used to create/design a map specifically build for kites r us.
2. D3 will be used to build an interactive visual overlay that will dynamically change based upong changing weather patterns
3. Underground weather API will be used to pull realtime and historical weather data, which will then be converted into a visual representation for the user.


## Timeline


Day one:

- [ ] Build custom map of the US

Day two:

- [ ] Build realtime overlay of wind patterns in the US

Day three:

- [ ] Build button bar allowing for user panning/zooming of map


Day four:

- [ ] Build options allowing users to change weather view for current/historical timeline
