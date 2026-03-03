# Preflight

An Even HUB plugin for airline pilots. Displays key flight release data on Even Realities G2 glasses during preflight.

## What it does

Enter your flight release details in the form — flight number, departure and arrival stations, flight time, fuel figures, and cabin crew names — then tap **Send to Glasses**. The data is formatted and displayed on your G2 lenses instantly.

**Displayed on glasses:**
- Flight number (centered)
- Route (e.g. LAX → JFK)
- Release fuel and minimum takeoff fuel
- Block time
- Cabin crew names (up to 4)

## Intended use

Preflight is intended for use during non-critical phases of flight when personal electronic devices are permitted.

## Tech

- Single-file web plugin (`index.html`)
- Uses the [Even Hub SDK](https://www.npmjs.com/package/@evenrealities/even_hub_sdk) (`waitForEvenAppBridge`, `createStartUpPageContainer`)
- Two-container layout for pixel-accurate column alignment on the G2 display (576px wide, 40 chars)
- Hosted on GitHub Pages: [flyceliac.github.io/preflight-plugin](https://flyceliac.github.io/preflight-plugin/)

## Roadmap

- Automatic parsing of release data to pre-fill the form

## Author

[flyCeliac](https://github.com/flyCeliac) — developed with the assistance of [Claude](https://claude.ai) (Anthropic)
