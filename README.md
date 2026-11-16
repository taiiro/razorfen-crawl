# Razorfen Crawl

A first-person quilboar dungeon crawler that runs in the browser. You're the monster this time: mine blood stones in the tunnels of the Kraul, fight off the Horde and Alliance adventurers farming your home, and get the stones back to the Warren to grow your boar and your tribe.

A free, non-commercial fan project. World of Warcraft and its races and places belong to Blizzard Entertainment; this project isn't affiliated with or endorsed by Blizzard.

**Play:** https://taiiro.github.io/razorfen-crawl/

## Install it like an app

- **iPhone / iPad:** open the link in Safari → Share → **Add to Home Screen**.
- **Android:** open it in Chrome → menu → **Install app** (or Add to Home screen).
- **Desktop Chrome / Edge:** click the install icon in the address bar.

After the first load it works offline.

## Saves

Progress saves on the device. To move progress between devices (or from the Claude version), open **Menu → Back up my save** on one, then **Menu → Load a save code** on the other. Save codes start with `RFC1:`.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole game (one file) |
| `manifest.webmanifest` | App name, icons and colours for installing |
| `sw.js` | Offline cache. Bump `VERSION` when the game changes |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | App icons |
