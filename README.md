# MLB Season Tracker

A single-page web app that tracks any MLB team's full season schedule, scores, and starter pitching stats. Pulls live data from the MLB Stats API.

## Features

- **All 30 MLB teams** — dropdown selector grouped by division
- **Full season schedule** — date, W/L, running record, opponent, runs, hits
- **Starter pitching lines** — name, IP, K, ER for each game
- **Live tracking** — running record, streak, home/away splits
- **Auto-refresh** — updates every 5 minutes
- **Today's game** — highlighted and auto-scrolled into view
- **Persistent selection** — remembers your team between visits

## Data Source

All data comes from the [MLB Stats API](https://statsapi.mlb.com/api/v1) (no authentication required).

## Deployment

Hosted on GitHub Pages. Just a single `index.html` file — no build tools or dependencies.
