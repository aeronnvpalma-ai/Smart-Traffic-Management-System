# Smart-Traffic-Management-System

A browser-based smart traffic operations dashboard for a city mobility control center.

## Included features

- Operations dashboard in `index.html`
- Interactive live traffic map in `live-map.html`
- Role-based traffic portal in `traffic-portal.html`
- Best-route planner based on current simulated traffic conditions

## Demo roles

Open `traffic-portal.html` in a browser and sign in with one of the demo users below.

- Username: `admin` | Password: `1234`
  - Administrator
  - Manage users, roads, signals, and reports
- Username: `officer` | Password: `1234`
  - Traffic Officer
  - Monitor traffic, report incidents, and update incident status
- Username: `viewer` | Password: `1234`
  - Viewer
  - Access dashboard, traffic monitoring, and reports

## Route / best-route feature

The portal includes a route recommendation section that compares sample routes and chooses the route with the least traffic congestion and the shortest estimated travel time.

## Live traffic map

The live map page shows corridor lines on a map, with green, amber, and red conditions for free flow, moderate flow, and congestion. It includes a traffic filter and refresh button.

## Run locally

Open any of these files directly in a browser:

- `index.html`
- `live-map.html`
- `traffic-portal.html`

> These are static front-end demos. Production use would require a real backend authentication layer and traffic data source.
