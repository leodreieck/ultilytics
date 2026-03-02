# Ultilytics

A lightweight, offline-first analytics tracker for ultimate frisbee teams — built as a single HTML file with no dependencies.

## Features

- **Team management** — add players (name, gender M/F), toggle active status, sort by name or status
- **Player profiles** — per-player detail screen with stats summary, weighted +/- total, and radar chart comparing to team average
- **Game management** — create games with name, date, and division (Mixed/Women's/Open); track score automatically
- **Game mode** — build a 7-player lineup before each point, choose offense or defense (auto-suggested based on who scored last), then track per-player stats during the point: Pull, Defense, Turnover, Drop, Assist, Goal
- **Statistics** — per-game and overall stats with sortable player tables (Points, D-Points, O-Points, Pulls, Defenses, Turnovers, Drops, Assists, Goals, Total), team summary with win %, and a player co-occurrence matrix with heatmap
- **CSV export / import** — export all data or a single game; reimport to restore a project

## Live

[leodreieck.de/ultilytics](https://leodreieck.de/ultilytics)

## Usage

Just open `index.html` in any modern browser. All data is stored in the browser's `localStorage` — nothing is sent to a server.

To share or back up data, use the **Export All Data (CSV)** button on the Team screen and **Import CSV** to restore it later.

## Development

No build step. Edit `index.html` directly.
