# Ultilytics

A lightweight, offline-first analytics tracker for ultimate frisbee teams — built as a single HTML file with no dependencies.

## Features

- **Team management** — add players with name and gender, mark them active/inactive
- **Game management** — create games with name and date, track score automatically
- **Game mode** — build a 7-player lineup before each point, choose offense or defense (auto-suggested based on who scored last), then track per-player stats during the point:
  - Pull, Defense, Turnover, Drop, Assist, Goal
- **Statistics** — per-game and overall stats tables with sortable columns (Points Played, Pulls, Defenses, Turnovers, Drops, Assists, Goals, Total)
- **CSV export / import** — export all data or a single game; reimport to restore a session

## Live

[leodreieck.de/ultilytics](https://leodreieck.de/ultilytics)

## Usage

Just open `index.html` in any modern browser. All data is stored in the browser's `localStorage` — nothing is sent to a server.

To share or back up data, use the **Export All Data (CSV)** button on the Team screen and **Import CSV** to restore it later.

## Development

No build step. Edit `index.html` directly.
