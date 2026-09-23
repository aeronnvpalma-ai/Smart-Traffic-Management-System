# Smart-Traffic-Management-System

A browser-based smart traffic operations dashboard.

## Features

- Dashboard for traffic operations, roads, signals, incidents, and reports.
- **Live Traffic Map** at [`live-map.html`](live-map.html), powered by Leaflet and OpenStreetMap tiles.
- Color-coded road corridors for free-flowing, moderate, and congested traffic.
- Road popups with area, speed, and condition details.
- Condition filtering, simulated live refresh, average speed metrics, incident counts, and browser geolocation.

## Run locally

Open `index.html` for the existing dashboard or open `live-map.html` directly. Because the map uses external Leaflet and OpenStreetMap resources, an internet connection is required for map tiles and the map library.

> The traffic values in this static HTML demo are simulated. Connect the refresh logic to a traffic provider or backend API for production real-time data.
