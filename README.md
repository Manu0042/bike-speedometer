# Bike Speedometer

A lightweight GPS bike computer that runs in your phone's browser and installs as a PWA.

## Features
- Live speed, average speed (moving time only) and max speed
- Distance, moving time and total trip duration
- Start / pause / resume and one-tap reset for each new ride
- Carbon-fiber dark theme with yellow-orange display, inspired by Ferrari dashboards
- Works offline once installed; data saved locally, no account and no server

## Project structure
```
index.html              app (HTML, CSS, JS)
manifest.webmanifest    PWA manifest
sw.js                   service worker (offline cache)
icons/                  app icons (192, 512, maskable, Apple touch, favicon)
```

## Usage
1. Open the app over **HTTPS** (e.g. GitHub Pages).
2. Allow location access when the browser asks.
3. Install it: Firefox/Chrome menu › *Install* (or *Add to Home screen*).
4. Tap **Start** and keep the screen on during the ride. Tap **Reset** twice for a new trip.

## Notes
- Geolocation only works on secure (HTTPS) pages.
- Browser GPS tracking pauses when the screen locks.
- Stops below 2 km/h are ignored to avoid GPS drift.
- After editing files, bump `CACHE` in `sw.js` so installed copies update.

## License
MIT
