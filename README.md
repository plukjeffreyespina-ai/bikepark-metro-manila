# BikePark Metro Manila — Full-screen route navigation

## New navigation features
- Route results automatically open in a full-screen map.
- Live GPS location tracking using the browser's geolocation permission.
- Follow-me control to keep the map centered on the rider.
- Exit map control (also Escape on desktop).
- Route summary and available turn instructions in a compact bottom panel.
- Live traffic button opens Google Maps' traffic layer near the current GPS location or route destination.

## Important traffic limitation
The app's Leaflet/OpenStreetMap map does not contain a live traffic feed. The Live traffic button opens Google Maps traffic separately. An embedded, in-app live traffic overlay requires a licensed traffic data provider/API key (for example Google Maps Platform, TomTom, or HERE) and the applicable billing/usage setup.

## Deploy
Replace the existing `index.html` at the root of your GitHub repository, commit to `main`, and wait for GitHub Pages to rebuild. Keep the file at repository root.
