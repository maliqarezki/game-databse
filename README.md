# HTML5 Games Database by Maliq Arezki

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Format: JSON](https://img.shields.io/badge/Data%20Format-JSON-blue.svg)](https://raw.githubusercontent.com/maliqarezki/game-databse/refs/heads/main/games.json)
[![Platform: HTML5](https://img.shields.io/badge/Platform-HTML5-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![Status: Active](https://img.shields.io/badge/Status-Maintained-brightgreen.svg)](#)

A structured and lightweight JSON database containing a curated collection of HTML5 web games, ready to integrate into web arcades, Discord bots, portals, or game launchers.

---

## Direct Data Endpoint

You can fetch the latest raw JSON data directly using the following URL:
https://raw.githubusercontent.com/maliqarezki/game-databse/refs/heads/main/games.json
---

## Features

* **Categorized Collection:** Covers multiple genres including Arcade, Action, Puzzle, Adventure, Sports, and Retro.
* **Lightweight & Fast:** Single JSON file format designed for fast retrieval without backend database overhead.
* **Cross-Platform:** Pure web-based games compatible across desktop, tablet, and mobile browsers.
* **Standardized Metadata:** Uniform schema including ID, title, description, category, thumbnail, game URL, and tags.

---

## JSON Schema

Each game entry in `games.json` follows this structure:

```json
[
  {
    "nama": "Plundur.io",
    "deskripsi": "Online 3D Pirate Game. Jelajahi lautan luas, rampas harta karun, dan jadilah raja bajak laut.",
    "thumbnail": "https://cbox9234.github.io/res/scopeditems/plundur.io.png",
    "embed_url": "https://plundur.io/",
    "developer": {
      "nama": "LEGiON Studio",
      "logo_url": "https://cbox9234.github.io/_next/static/media/logo.d0302b21.png"
    }
  },
]
```

Credits
Author & Maintainer: Maliq Arezki

Data Source: maliqarezki/game-databse

License
This project is open-source and distributed under the MIT License.
