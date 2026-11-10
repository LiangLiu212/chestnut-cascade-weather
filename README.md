# Ski Weather Monitor

Live ski weather for three Midwest hills:

* Chestnut Mountain (Galena, IL)
* Cascade Mountain (Portage, WI)
* Devil's Head (Merrimac, WI)

For each one the page shows current conditions, snowmaking windows (from wet bulb temperature),
a 48 hour outlook and a 10 day outlook.

Live page: https://liangliu212.github.io/chestnut-cascade-weather/

Single static page (`index.html`), no build step. Forecast data comes from
[Open-Meteo](https://open-meteo.com/) and is fetched by the browser each time the page loads.

To add another hill, append an entry to the `RESORTS` list near the top of the script in
`index.html` and add a color token for it in the CSS.

Hosted with GitHub Pages from the `main` branch.
