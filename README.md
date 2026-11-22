# BikePark Metro Manila — Free-only with Voice Assistance

This build adds browser-based spoken route instructions using the device's built-in SpeechSynthesis API. No paid voice API or Google Maps API key is required.

## Voice features
- "Hear directions" button reads the route instructions aloud.
- "Start" begins GPS tracking and starts spoken directions.
- Press the voice button again to stop speech; press it again to replay.
- Exiting full-screen navigation stops speech.

## Existing free features
- Leaflet + OpenStreetMap map
- Device GPS and follow-me
- OpenStreetMap-based bicycle, walking and driving route providers
- Google Maps traffic opens externally (traffic is not embedded in the app)

## Important voice limitation
Voice currently reads the route's instruction list in sequence when started; it is not yet turn-triggered by GPS proximity, and it does not automatically reroute. Keep the map visible and follow road signs. Browser/device speech voices vary by phone and language settings. GPS requires HTTPS and permission.

## Deploy
Upload `index.html` and this `README.md` to the root of the `bikepark-metro-manila` GitHub repository, replacing the previous versions, then commit to `main`.
