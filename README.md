# Griffins Strategy

Scouting and match strategy for the Griffins, FRC team 1884, built for the 2026 FIRST Robotics Competition season: the São Paulo regional in Brazil and the Newton division at the World Championship. Scout the other teams, then plan each match, autonomous routine included, before the robots hit the field.

Built by [Jordi Albanell](https://jordialbanell.com/projects), the team's mentor, on the flight to Brazil.

## What it does

Switch between events at the top. Each event has:

- **Overview** and **Schedule**: the team's matches, with alliance partners, opponents and starting stations.
- **Strategy**: a plan per match, on the field map.
- **Free Strat**: a blank field to sketch paths and autonomous routines.
- **Scoring** and **RP Calc**: how points and ranking points add up.
- **Pit Map**, **Teams** and **Rules**: find a team's pit, scout every team, and keep the rules that matter close.

## Run it

No install and no build step. It's one HTML page plus one React file.

1. Download or clone this repo.
2. Serve the folder with any static server, for example `npx serve .`, and open the address it prints. (Opening `index.html` straight from disk won't load the `.jsx` file in most browsers.)
3. To use it for your own event, edit the event data in `griffins-strategy.jsx` (the `EVENTS` object holds each event's matches, teams and rules).

To put it online, drop the folder on [Vercel](https://vercel.com/new), Netlify or GitHub Pages.

## Licence and credit

MIT licence, copyright (c) 2026 Jordi Albanell. See [LICENSE](LICENSE).

In plain words: you can use this code, change it, share it and build on it, including for paid work. The one legal condition is that **every copy keeps the copyright line and the LICENSE file**, so the code always says where it came from. Removing them breaks the licence.

If you put something live that's built on it, a "Based on Griffins Strategy by [Jordi Albanell](https://jordialbanell.com)" link is appreciated.
