# Griffins Strategy

Scouting and match strategy for the Griffins, FRC team 1884, built for the 2026 FIRST Robotics Competition regional in São Paulo, Brazil: scout the other teams, then plan each match, autonomous routine included, before the robots hit the field.

Built by [Jordi Albanell](https://jordialbanell.com/projects), the team's mentor, on the flight to the competition.

## What it does

- The team's match schedule, with alliance partners, opponents and starting stations.
- A profile for every team at the event, for scouting notes.
- A drawing board for each match: sketch paths and the autonomous routine on the field.
- Quick notes on the game rules that matter on the day.

## Run it

No install and no build step. It's one HTML page plus one React file.

1. Download or clone this repo.
2. Serve the folder with any static server, for example `npx serve .`, and open the address it prints. (Opening `index.html` straight from disk won't load the `.jsx` file in most browsers.)
3. To use it for your own event, edit the `MATCHES` and `TEAMS` lists at the top of `griffins-strategy.jsx`.

To put it online, drop the folder on [Vercel](https://vercel.com/new), Netlify or GitHub Pages.

## Licence and credit

MIT licence, copyright (c) 2026 Jordi Albanell. See [LICENSE](LICENSE).

In plain words: you can use this code, change it, share it and build on it, including for paid work. The one legal condition is that **every copy keeps the copyright line and the LICENSE file**, so the code always says where it came from. Removing them breaks the licence.

If you put something live that's built on it, a "Based on Griffins Strategy by [Jordi Albanell](https://jordialbanell.com)" link is appreciated.
