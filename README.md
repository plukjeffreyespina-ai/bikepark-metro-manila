# BikePark Metro Manila — Professional UI + Routing Fix

Updated static website package for GitHub Pages.

## Included
- `index.html` — complete app
- Professional responsive interface and Metro Manila directory
- Map search, filters, location details, copy address, and community availability reports
- In-app route display
- Bicycle routing: BRouter primary service with Valhalla fallback
- Walking and driving routing using the existing OpenStreetMap routing service

## Update your GitHub Pages site
1. Extract this ZIP.
2. Open your `bikepark-metro-manila` repository.
3. Select **Add file → Upload files**.
4. Upload the new `index.html`, replacing the existing file.
5. Commit the changes to the `main` branch.
6. GitHub Pages will automatically rebuild the site.

Keep `index.html` at the repository root (`/(root)`), not inside a subfolder.

## Routing notes
Routing uses third-party public services and requires internet connectivity. Public services may be rate-limited or temporarily unavailable, and OpenStreetMap coverage may be incomplete. Always verify routes and follow local traffic rules.

User-added places and parking reports in this prototype are stored in the current browser's local storage; they are not synchronized between devices.
