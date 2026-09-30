# Bike Speedometer

A lightweight GPS bike computer that runs in your phone's browser and can be installed as a PWA.

## Features
- Live speed, average speed (moving time only) and max speed
- Distance, moving time and total trip duration
- Start / pause / resume and one-tap reset for each new ride
- Carbon-fiber dark theme with yellow-orange display, inspired by Ferrari dashboards
- Data saved locally on your device, no account and no server

## Usage
1. Open the app over **HTTPS** (for example via GitHub Pages).
2. Allow location access when the browser asks.
3. Tap **Start** and keep the screen on during the ride.
4. Tap **Reset** twice to begin a new trip.

## Notes
- Geolocation only works on secure (HTTPS) pages.
- GPS tracking in a browser pauses when the screen locks.
- Stops below 2 km/h are ignored to avoid GPS drift.

## License
MIT
