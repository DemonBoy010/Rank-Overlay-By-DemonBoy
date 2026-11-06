<div align="center">

# VALORANT RANK OVERLAY

### A live rank-tracking overlay for OBS Studio

**Created by IMX DemonBoy**

[![YouTube](https://img.shields.io/badge/YouTube-IMX%20DemonBoy-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@imxdemonboy010)
[![Instagram](https://img.shields.io/badge/Instagram-%40imxdemonboy__official-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/imxdemonboy_official/)
[![Kick](https://img.shields.io/badge/Kick-demonboy010-53FC18?style=for-the-badge&logo=kick&logoColor=black)](https://kick.com/demonboy010)

![Version](https://img.shields.io/badge/version-1.0.0-ff4655?style=flat-square)
![Platform](https://img.shields.io/badge/platform-OBS%20Studio-6441A5?style=flat-square&logo=obsstudio&logoColor=white)
![Built with](https://img.shields.io/badge/built%20with-HTML%20%7C%20CSS%20%7C%20JavaScript-orange?style=flat-square)

---

**Choose a design. Customize your stats. Take your rank on stream.**

</div>

## Overview

A single-file setup page that generates a customizable **live VALORANT rank overlay** for OBS. Choose a style, enter your account details, customize the display and effects, preview the result, and download a ready-to-use `overlay.html`.

## Features

| Feature | Description |
|---|---|
| **14 overlay styles** | Classic Card, Slim Bar, Glass, Neon Terminal, Tactical HUD, Ring Badge, Wide Banner, Minimal Text, Red Slash, Retro Arcade, Aurora Glass, Frosted Glass, Holo Glass and Crystal |
| **Rank and RR tracking** | Display your current rank, RR number and RR progress |
| **Match information** | Show the last match result, RR change and last five match results |
| **Session statistics** | Display session RR, match record and win/loss streak |
| **Peak rank rotation** | Switch between current rank and a full peak-rank view |
| **Full customization** | Adjust colours, text, panel, transparency, font, corners and size |
| **Visual effects** | Glow, shimmer, sparks, scanlines, floating rank icon, RR animation, rank-up banner and more |
| **Demo mode** | Simulate wins, losses and rank changes to test the overlay |
| **Automatic refresh** | Configure data refresh from 5 to 15 seconds |
| **OBS support** | Add the generated file as a local Browser Source |

## Requirements

- OBS Studio (or streaming software with a Browser Source)
- A free HenrikDev API key
- Your VALORANT Riot ID (name and tag)

## Getting started

1. Download the setup HTML file from this repository: **`Rank_Overlay by DemonBoy.html`**.
2. Open the file in a browser directly from your PC. Do not use an online or chat preview; the page needs to run locally to contact the API.
3. Choose one of the 14 overlay styles.
4. Enter your HenrikDev API key, Riot name, tag, region and platform.
5. Customize the information, colours, transparency and effects.
6. Check the preview and select **Download my overlay.html**.

### Add the overlay to OBS

1. Open OBS Studio.
2. Add a **Browser** source to your scene.
3. Enable **Local file** and select your downloaded `overlay.html`.
4. Set the width and height shown on the setup page.
5. Save your source. The overlay refreshes automatically.

If you change your design or settings, generate and download a new `overlay.html` file.

## Supported regions

| Region code | Area |
|:---:|---|
| `ap` | Asia Pacific (India, Japan, Southeast Asia and Oceania) |
| `eu` | Europe |
| `na` | North America, Brazil and LATAM |
| `kr` | Korea |

## Keep your API key private

> [!CAUTION]
> The generated `overlay.html` contains your HenrikDev API key. **Do not publish, share, commit or display that generated file on stream.**

The setup page in this repository does not contain your personal API key and is safe to share.

Keep this entry in your `.gitignore`:

```gitignore
overlay.html
```

## Data source

Rank and match information is provided by the [HenrikDev VALORANT API](https://docs.henrikdev.xyz/).

## Connect with IMX DemonBoy

Follow the project creator for streams, updates and more gaming content.

| Platform | Official page |
|---|---|
| YouTube | [@imxdemonboy010](https://www.youtube.com/@imxdemonboy010) |
| Instagram | [@imxdemonboy_official](https://www.instagram.com/imxdemonboy_official/) |
| Kick | [demonboy010](https://kick.com/demonboy010) |

## Credits and disclaimer

**Created by IMX DemonBoy.**

This is an independent community project. It is not affiliated with, endorsed by, or sponsored by Riot Games. VALORANT and all related names and assets are trademarks of Riot Games, Inc.

---

<div align="center">

**BUILT FOR GAMERS. DESIGNED FOR STREAMERS.**

*IMX DemonBoy*

</div>
