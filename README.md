# Pieter Wigboldus Games

An overview of the public games by Pieter Wigboldus, with a link to play each game and a link to its code. One static page for GitHub Pages: plain HTML and CSS, no build.

| Game | Play | Code |
|---|---|---|
| TripScouts | https://tripscouts.online/ | [w3nl/tripscouts](https://github.com/w3nl/tripscouts) |
| Villa Villekulla: Locked In with Mr Nilsson | https://kakelbont.online/ | [w3nl/pippi](https://github.com/w3nl/pippi) |
| Sinterklaas: Het Grote Pakjesavontuur | https://5december.online/ | [w3nl/sinterklaas](https://github.com/w3nl/sinterklaas) |
| Hello, IT: The Basement Lockdown | https://w3nl.github.io/it/ | [w3nl/it](https://github.com/w3nl/it) |
| Het Geheim van de Albertsmaheert | https://albertsmaheert.nl/escaperoom/ | [w3nl/albertsmaheert](https://github.com/w3nl/albertsmaheert) |
| TunnelVue | https://tunnelvue.nl/ | [w3nl/tunnelvue](https://github.com/w3nl/tunnelvue) |

All six are web apps (installable, playable offline). TripScouts is also an Android app, now in testing on Google Play: join the test [on the web](https://play.google.com/apps/testing/nl.w3nl.cabinweek) or [on Android](https://play.google.com/store/apps/details?id=nl.w3nl.cabinweek).

Private games are not listed here.

## Files

- `index.html`: the page, with a card per game.
- `style.css`: the styles, with a dark and a light theme (it follows the device).
- `icons/`: the app icon of each game, copied from its repository.
- `.nojekyll`: GitHub Pages serves the files as they are.

## Adding a game

1. Copy its app icon into `icons/` (an SVG if the game has one, otherwise its 192 px PNG).
2. Copy an `<article class="game">` in `index.html` and fill in the name, the kind of game, a few sentences, the languages, the play link and the code link. Leave out the code link if the code is not public. `--accent` is the colour of the line on top of the card.
3. Add the game to the table above.

## Publishing

Settings → Pages → Build and deployment: **Deploy from a branch**, branch `main`, folder `/ (root)`. The page is then at https://w3nl.github.io/games/.
