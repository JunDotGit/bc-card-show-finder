# BC Card Show Finder

A single static page listing upcoming Pokémon TCG / trading card shows across British Columbia, sorted by distance from the visitor (browser geolocation or a manual city pick), with a list and calendar view.

Live site: https://JunDotGit.github.io/bc-card-show-finder/

## Data

Show data lives inline in `index.html` as the `SHOWS` array — no build step, no backend. Each entry has a name, city, optional venue address + coordinates, dates, and a source link.

## Suggesting a show

Open an issue with the **Suggest a show** template. Suggestions are checked against a public source before being merged into `index.html`.

## Updating the data

Edit the `SHOWS` array in `index.html` and push to `main` — GitHub Pages redeploys automatically.
