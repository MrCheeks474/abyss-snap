# Abyss Snap

A bioluminescent deep-sea tunnel dodger, built as a single self-contained HTML5 canvas game.

Play as a glowing drifter gliding through a living sea cave. Switch gravity to rise or fall, dodge the shifting walls, and watch for the rare tight squeezes.

## Controls

Pick a mode on the start screen:
- **Tap** — tap/click to instantly flip gravity
- **Hold** — hold down to rise, release to fall

Each mode tracks its own best distance, saved locally in your browser.

## Running it

Just open `index.html` in a browser, or serve the folder as a static site (it's a installable PWA — manifest + service worker included for offline play and "Add to Home Screen").

## Files

- `index.html` — the game
- `manifest.json` — PWA app metadata
- `sw.js` — offline service worker
- `icons/` — app icons
