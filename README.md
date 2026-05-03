# Grocery sales — revenue by product category

An animated motion chart showing monthly grocery sales revenue across seven product categories for 2022. Built as part of the *Advanced Data Visualization with Tableau* course on Coursera.
(https://anhvotn.github.io/grocery-sales-motion-chart/)

## What it shows

Total monthly revenue across Bakery, Beverages, Dairy, Dry Goods, Fresh Produce, Meat/Seafood, and Snacks. Use play/pause or the slider to scrub through Jan–Dec 2022.

A few things that jump out:
- Dry Goods and Meat/Seafood are the dominant categories all year.
- Meat/Seafood spikes to $1,500 in November — the biggest single-month jump.
- Dairy stays the smallest category throughout the year.

## Built with

- [Chart.js](https://www.chartjs.org/) for the bar chart and animations
- Vanilla HTML/CSS/JS — no build step
- A companion Tableau Public version is also available *(add your link here)*

## Run locally

It's a single file. Either open `index.html` directly, or:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Data

Sample grocery sales dataset provided by the Coursera course *Advanced Data Visualization with Tableau* (Tableau Learning Partner).
