# Smart-Traffic-Management-System

A browser-based smart traffic operations dashboard.

## Features

- Existing operations dashboard in `index.html`.
- Live traffic map in `live-map.html`, powered by Leaflet and OpenStreetMap tiles.
- Role-based demo portal in `traffic-portal.html` with Administrator, Traffic Officer, and Viewer roles.
- Best Route planner that compares possible routes using current simulated traffic levels.

## Demo roles

Open `traffic-portal.html` and use password `1234`:

| Username | Role | Permissions |
| --- | --- | --- |
| `admin` | Administrator | Manage users, roads, signals, and view reports |
| `officer` | Traffic Officer | Monitor traffic, report incidents, and update incident status |
| `viewer` | Viewer | Access dashboard, traffic monitoring, and reports |

## Run locally

Open `index.html`, `live-map.html`, or `traffic-portal.html` in a browser. The live map requires an internet connection for Leaflet and OpenStreetMap resources.

> The role accounts, route values, and traffic values are front-end demo data. A production deployment should authenticate against a backend and obtain route/traffic data from a real provider.
