<div align="center">

# Stark Industries Database

**A classified MCU archive of every Iron Man suit and AI system Tony Stark built, presented as an interactive JARVIS-style database.**

![HTML](https://img.shields.io/badge/-HTML-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-AGPLv3%20%2B%20Commercial-00D4C8.svg)

</div>

---

> *"Part of the journey is the end."*

## What it does

Stark Industries Database is a single-file, zero-dependency web app cataloguing every Iron Man suit and AI system from the MCU films, styled as a classified JARVIS-style terminal. Search and filter the archive, then click any suit card for an expanded detail view.

## Features

- **50 Iron Man suits** — every Mark from I through LXXXV, with film of first appearance and primary function
- **7 AI systems** — J.A.R.V.I.S., F.R.I.D.A.Y., E.D.I.T.H., K.A.R.E.N., DUM-E, U, and Butterfingers
- Search suits by name, function, or mark number
- Filter by film (Iron Man 1–3, Avengers, Age of Ultron, Civil War, Infinity War, Endgame, Homecoming)
- Click any suit card for an expanded detail modal
- Era-coloured arc reactor thumbnails with pulsing animations
- Fully responsive — works on mobile and desktop

## Tech Stack

| Layer | Choice |
|---|---|
| Frontend | Pure HTML, CSS, and vanilla JavaScript — zero dependencies, zero build step |
| Fonts | Google Fonts: Orbitron, Share Tech Mono, Barlow |
| Structure | Self-contained single file (`index.html`) |

## Screenshots

_Screenshots coming soon._

## Quick Start

```bash
git clone https://github.com/TheBooleanJulian/stark-db
cd stark-db
# Open in browser — no server needed
open index.html
```

Or deploy to GitHub Pages in one click:

1. Push to a repo on GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Done — live at `https://TheBooleanJulian.github.io/stark-db`

## Project Structure

```
stark-db/
|-- index.html   # The entire app — data, styles, and logic in one file
|-- README.md
`-- LICENSE
```

## Data Coverage

| Film | Suits |
|------|-------|
| Iron Man (2008) | Marks I–III |
| Iron Man 2 (2010) | Marks IV–VI |
| The Avengers (2012) | Mark VII |
| Iron Man 3 (2013) | Marks VIII–XLII (Iron Legion) |
| Age of Ultron (2015) | Marks XLIII–XLV incl. Hulkbuster |
| Civil War (2016) | Mark XLVI |
| Homecoming (2017) | Mark XLVII |
| Infinity War (2018) | Mark L (Bleeding Edge) |
| Endgame (2019) | Marks XLIX (Rescue) + LXXXV |

## Status / Roadmap

- [x] Full suit and AI system archive with search and filtering
- [x] Detail modal per suit
- [x] Responsive layout
- [ ] Timeline/chronological view across films

## Changelog

- **2026-04-08** — Initial release: full suit/AI archive, search, filtering, and detail modal

## License

This project is dual licensed.

- Community Edition — [GNU Affero General Public License v3 (AGPLv3)](LICENSE). Free to use, modify, and self-host. If you distribute a modified version or run it as a network service, you must make the corresponding source available.
- Commercial License — for organisations that want to embed, modify, or distribute this software without AGPLv3's obligations. See [COMMERCIAL-LICENSE.md](COMMERCIAL-LICENSE.md).

---

<div align="center">
<sub>Built by <a href="https://github.com/TheBooleanJulian">@TheBooleanJulian</a></sub>
</div>
