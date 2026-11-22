# BikePark Metro Manila — Free GPS-triggered voice guidance

## New behavior
- Voice navigation starts only after the user taps START.
- The browser continuously watches device GPS while navigation is active.
- Turn prompts are tied to maneuver coordinates returned by the routing service.
- The app speaks when the rider is within approximately 220 metres of the next maneuver, including an estimated distance.
- Arrival is announced within approximately 35 metres of the destination.
- Prompts are advanced once, so the same turn is not repeatedly announced.
- Voice uses the browser's built-in SpeechSynthesis API; no paid voice provider or API key is needed.

## Deploy
Replace the existing root `index.html` and `README.md` in the GitHub repository and commit to `main`.

## Limitations
- Prompt accuracy depends on phone GPS accuracy and the quality of route maneuver coordinates.
- Public routing services can be rate-limited or temporarily unavailable.
- Browser/device voice availability and language voices vary.
- Keep the browser tab open and screen awake during navigation. Test voice prompts safely before riding.
