# Clear Weather

A responsive weather app with live city search, current conditions, a 24-hour forecast, a seven-day forecast, location detection, and Celsius/Fahrenheit switching.

## Files

- index.html — page structure and metadata
- style.css — styling and responsive layouts
- app.js — weather requests, rendering, search, location, and unit controls

## Run the app

Extract this ZIP, then open index.html in Chrome, Edge, or Firefox.
An internet connection is needed for weather data and web fonts.

For local development, run this command from the extracted clear-weather folder:

    python -m http.server 8000

Then open http://localhost:8000 in your browser. This also gives location detection a supported local origin. Allow location access when prompted, or use city search.

No build step, npm packages, or API key is required.

## Customize

Edit index.html for page content, style.css for the design, and app.js for functionality. Refresh your browser to see changes.
Temperature units and the selected city are saved locally in the browser.

## Data

Weather and city search use Open-Meteo: https://open-meteo.com/
Weather data attribution is included in the app footer. Check the provider's current terms and usage limits before commercial deployment.
Google Fonts supplies DM Sans and Manrope; the app falls back to system fonts if those fonts are unavailable.
