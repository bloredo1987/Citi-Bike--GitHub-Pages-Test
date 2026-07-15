# Citi Bike - Github Pages Test
This code fetches live Citi Bike station data, turns each station into a map marker with details, and displays everything on an interactive Leaflet map so users can visually explore station locations and capacity — which is important for understanding bike availability and planning trips.

# What the code does
It downloads real-time station information from the Citi Bike API using d3.json.

It loops through each station and creates a Leaflet marker showing its location, name, and capacity using Leaflet markers.

It groups all markers into a single layer using layerGroup.

It builds an interactive map centered on NYC with OpenStreetMap tiles using Leaflet map.

It adds a layer control so users can toggle the bike station layer on and off.

# How it shows the data
Each station appears as a clickable marker on the map.

Clicking a marker opens a popup with the station name and capacity.

The map is fully interactive — users can zoom, pan, and toggle layers.

# Why it’s important
- It transforms raw API data into a visual, easy-to-understand map.

- Users can quickly see where stations are located and how many bikes they can hold.

- It supports real-world use cases like trip planning, capacity monitoring, and urban mobility analysis.