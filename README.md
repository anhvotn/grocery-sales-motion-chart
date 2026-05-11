# Tableau Coursera — data visualisation portfolio

Interactive web versions of the assignments from the *Advanced Data Visualization with Tableau* course on Coursera. Built with vanilla HTML/JS so they can run anywhere; the originals live in Tableau Public.

## Visualisations

### [Grocery sales motion chart →](./index.html)
An animated bar chart of monthly grocery revenue across seven product categories for 2022. Play/pause and a scrubber let you step through Jan–Dec. The Meat/Seafood spike in November is the standout moment.

### [Earthquakes around Japan, 2007–2014 →](./japan-earthquakes.html)
M6+ earthquakes in the Japan region, shown two ways: an animated map by year, and an eight-panel small-multiples grid for direct comparison. 2011 is the dominant story — 84 quakes clustered around the M9.0 Tōhoku event and its aftershocks, with clear decay visible through 2014.

![Screenshot](screenshot.png)

## Built with

- [Chart.js](https://www.chartjs.org/) — the grocery motion chart
- [D3.js](https://d3js.org/) + [TopoJSON](https://github.com/topojson/topojson) + [world-atlas](https://github.com/topojson/world-atlas) — the earthquake maps
- Vanilla HTML/CSS — no build step

## Run locally

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Data

Sample datasets provided by the Coursera course *Advanced Data Visualization with Tableau*. The earthquake catalogue is in USGS format (time, lat, lon, depth, magnitude); the grocery data is monthly aggregated revenue, units sold, and profit by product category.
