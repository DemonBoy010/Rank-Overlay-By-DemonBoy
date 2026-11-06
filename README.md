# Valorant Rank Overlay Setup

A single-file setup page that generates your own **live Valorant rank overlay** for OBS. Pick a style, enter your details, tweak colours and effects, preview it, then download a ready-to-use `overlay.html`.

Created by [IMX DemonBoy](https://www.youtube.com/@imxdemonboy010)

---

## Features

- **14 overlay styles** with live demo previews: Classic Card, Slim Bar, Glass, Neon Terminal, Tactical HUD, Ring Badge, Wide Banner, Minimal Text, Red Slash, Retro Arcade, Aurora Glass, Frosted Glass, Holo Glass and Crystal
- **Choose what to show:** player name, #tag, RR number, RR progress bar (or ring), last match result, RR change, session RR, last 5 matches as dots, session record and win/loss streak, small peak rank tag
- **Peak rank rotation:** loop back and forth to a full peak rank view with adjustable timings
- **Result wording:** WIN / LOSS, VICTORY / DEFEAT, or icon only
- **Colours:** automatic per-rank accent, or one custom colour; custom text, panel, win and loss colours
- **Transparency:** fully transparent background, no border, glass (glassmorphism) mode, overall opacity
- **Effects:** glow, shimmer, floating sparks, scanlines, floating rank icon, RR pop, win/loss flash, rank up / derank banner, icon rotation, pulsing glow
- **Size control** from 0.5x to 2x
- **Near real-time updates** with a data refresh of 5 to 15 seconds
- **Simulate buttons** (win, loss, rank up) to test the animations in demo mode

---

## Requirements

- A free **HenrikDev API key** (get it from the HenrikDev Discord)
- Your **Riot ID** (name and tag)
- **OBS Studio** (or any streaming software with a browser source)

---

## How to use

1. Download or clone this repo.
2. Open `Rank_Overlay_setup.html` in your browser **from a saved file on your PC** (not inside a chat or online preview, or it can't reach the API).
3. **Choose a style** from the gallery.
4. Fill in your **API key, Riot name, tag, region and platform**.
5. Pick what to show, set colours, transparency and effects.
6. Check the live preview, then click **Download my overlay.html**.

### Add it to OBS

1. Add a **Browser** source.
2. Tick **Local file** and select your downloaded `overlay.html`.
3. Set the width and height shown on the setup page (they change with the style and size you chose).
4. Done. It refreshes by itself. If you change any settings, download a new file.

---

## Regions

| Code | Area |
|------|------|
| `ap` | Asia Pacific (India, Japan, SEA, Oceania) |
| `eu` | Europe |
| `na` | North America, Brazil, LATAM |
| `kr` | Korea |

---

## Important: keep your API key private

The downloaded `overlay.html` **contains your API key**. Don't share that file, commit it to Git, or show it on stream.

The setup page (`Rank_Overlay_setup.html`) has no key in it, so it is safe to share and safe to upload.

Tip: add this to your `.gitignore` so you never commit a generated overlay by accident:

```
overlay.html
```

---

## Data source

Rank and match data comes from the [HenrikDev Valorant API](https://docs.henrikdev.xyz/).

---

## Disclaimer

This project is not affiliated with or endorsed by Riot Games. Valorant and all related names and assets are trademarks of Riot Games, Inc.

---

## Credits

Created by [IMX DemonBoy](https://www.youtube.com/@imxdemonboy010)
