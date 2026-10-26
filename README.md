# Movie Radar 🎬

A personal movie-discovery app that answers one question: **what's worth seeing next, for me, near Parsippany NJ?**

Every film gets a **fit score (0–100)** built from:

| Signal | Weight | What it measures |
|---|---|---|
| Your genres | 35% | Action, comedy and romcom first; romance and epics close behind |
| Acclaim | 30% | Rotten Tomatoes Tomatometer + Oscar pedigree / awards buzz |
| Taste echo | 20% | How close it feels to Independence Day, Titanic, Gladiator and Indian award winners |
| Easy to see | 15% | Distance to the nearest likely theater and how soon it opens |

Your own **star ratings** feed back into the score.

## Features
- Tabs: In theaters · Tickets on sale · Coming soon · International · Classic returns · My ratings
- Genre filters and sorting by fit, release date or Rotten Tomatoes
- 5-star rating under every film (saved in your browser)
- "Alert me" tracking with days-to-release countdown
- Analytics lobby: genre pie, theater distances, release radar, fit leaderboard, your stars by genre
- One-tap links to Fandango (tickets & seat picker) and Rotten Tomatoes

## Run it
Static, zero-build. Open `index.html`, or serve it with GitHub Pages.

## Data
Release dates, RT scores and ticket status checked 26 Oct 2026. Update the `M` array in `index.html` to refresh the slate.

## New in v2
- **Posters** load live from Wikipedia (free, no API key) and are cached in your browser
- **Box office drawer**: tap any poster for the trailer, reviews, 3-day ticket outlook, theaters and seat map
- **Real drive times** from OpenStreetMap routing (OSRM), from Parsippany or your live location, with Google Maps directions
- **3-day ticket outlook**: today, tomorrow and the day after, based on release and on-sale dates
- **Seat preference**: middle or back rows, never rows A–D, shown on a seat map
- **Last 12 months taste memory**: 14 recent films with starter ratings based on your genres. Change any star and the fit scores re-rank
- Search, "Surprise me", sort by closest screen, card tilt
