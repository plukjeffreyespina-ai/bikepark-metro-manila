# BikePark Metro Manila — Free-only build

This version does not use Google Maps Platform APIs, a Google API key, or a billing account.

## Free components
- Leaflet map interface
- OpenStreetMap map tiles (with visible attribution)
- OpenStreetMap Nominatim + Photon address lookup fallbacks
- BRouter + OpenStreetMap-based Valhalla bicycle routing fallbacks
- OpenStreetMap-based routing service for walking/driving
- Browser/device GPS for current location and follow-me mode
- Full-screen route map and in-app route line
- Live traffic button opens Google Maps traffic in a separate tab/app; traffic is not embedded in BikePark

## Deploy to GitHub Pages
1. Extract this ZIP.
2. Open your GitHub repository `bikepark-metro-manila`.
3. Upload `index.html` and `README.md` to the repository root (replace existing files).
4. Commit the changes to the `main` branch.
5. Wait for GitHub Pages to publish, then refresh the website.

## Important limitations
- The app uses public community routing/geocoding services. They are free to access but are best-effort, can be rate-limited, and are not guaranteed to be continuously available.
- If a bicycle route provider is temporarily unavailable, retry later or use the external Google Maps directions link. No Google Maps API integration is used inside the app.
- Google Maps live traffic opens externally. There is no free public Google traffic API for embedding the live traffic layer in this app.
- GPS requires HTTPS and permission from the device/browser.
- OpenStreetMap standard tiles have a usage policy. Do not bulk-download tiles or use the public tile server for offline maps; show the required © OpenStreetMap contributors attribution and respect caching rules.
- Parking availability reports are local to the device in this prototype and are not shared between users.
