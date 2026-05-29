# Global Crime Mapper 🗺️

**Author:** Sam Shaikh · [github.com/samshai5](https://github.com/samshai5)  
**Stack:** HTML5 · CSS3 · JavaScript · Leaflet.js  
**Status:** ✅ Live — runs entirely in the browser  

---

## Overview

An interactive **global crime hotspot visualization map** built with HTML5, CSS3, JavaScript, and the Leaflet.js mapping library. Displays crime data across major cities worldwide with color-coded markers, danger level indicators, a live heatmap toggle, city search, and night mode — all running client-side with zero backend required.

This project demonstrates real-world frontend development skills including dynamic DOM manipulation, event-driven programming, geospatial data visualization, CSS animations, and responsive UI design.

---

## Live Demo

Open `index.html` in any browser — no installation, no server, no dependencies to install.

---

## Features

| Feature | Description |
|---|---|
| 🗺️ **Interactive Map** | Powered by Leaflet.js with smooth pan, zoom, and fly-to animations |
| 📍 **Crime Markers** | Color-coded by crime type with pulsing animations and danger level sizing |
| 🔥 **Heatmap Toggle** | Switch between marker view and heatmap overlay with one click |
| 🔍 **City Search** | Real-time search — type a city name to fly directly to that location |
| 🌙 **Night Mode** | Toggle between light and dark map tiles |
| 📊 **Crime Detail Panel** | Click any marker to see crime type, danger level, trends, and police presence |
| 🖱️ **Click to Explore** | Click anywhere on the map to find the 3 nearest crime hotspots |
| ⌨️ **Keyboard Shortcuts** | R = Reset view · H = Heatmap · N = Night mode · F = Focus search |
| 📱 **Responsive Design** | Works on desktop and mobile browsers |

---

## Crime Categories

| Color | Type |
|---|---|
| 🔴 Red | Violent Crime |
| 🟠 Orange | Property Crime |
| 🔵 Blue | Drug-Related Crime |
| 🟣 Purple | Gang Activity |
| 🟢 Green | Cybercrime / Fraud |

---

## Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic page structure, map container, UI panels |
| **CSS3** | Glassmorphism UI, pulse animations, responsive layout, keyframe animations |
| **JavaScript (Vanilla)** | Event handling, DOM manipulation, geospatial logic, search, clustering |
| **Leaflet.js** | Interactive map rendering, marker placement, tile layers, fly-to animations |

---

## How to Run

No installation needed.

**Option 1 — Just open it:**
1. Download or clone this repo
2. Open `index.html` in any browser
3. That's it

**Option 2 — Clone via Git:**
```bash
git clone https://github.com/samshai5/global-crime-mapper.git
cd global-crime-mapper
open index.html
```

---

## Project Structure

```
global-crime-mapper/
│
├── index.html          # Full application — HTML, CSS, and JS in one file
└── README.md           # This file
```

---

## Key Technical Highlights

- **Geospatial proximity algorithm** — custom distance calculation to find the N nearest crime hotspots to any clicked map coordinate
- **Dynamic icon generation** — marker size and glow color scale with danger level (1–10) using programmatic CSS injection
- **CSS keyframe animations** — pulsing markers draw attention to high-danger zones without cluttering the UI
- **Glassmorphism UI** — frosted glass panels using `backdrop-filter: blur()` for a modern, professional look
- **Event-driven architecture** — all interactions (click, hover, zoom, keydown, input) handled with clean vanilla JS event listeners
- **No framework dependency** — built entirely in vanilla HTML/CSS/JS, demonstrating core frontend fundamentals

---

## Keyboard Shortcuts

| Key | Action |
|---|---|
| `R` | Reset map to global view |
| `H` | Toggle heatmap overlay |
| `N` | Toggle night mode |
| `F` | Focus search bar |

---

## Roadmap

- [ ] Connect to a real crime data API (e.g. FBI Crime Data API, UK Police API)
- [ ] Add date range filter to explore crime trends over time
- [ ] Add country-level statistics panel
- [ ] Export crime report as PDF
- [ ] React rewrite with TypeScript for component-based architecture

---

## Skills Demonstrated

`HTML5` `CSS3` `JavaScript` `Leaflet.js` `Geospatial Visualization` `DOM Manipulation` `Event-Driven Programming` `CSS Animations` `Glassmorphism UI` `Responsive Design` `Data Visualization` `Proximity Algorithms` `Frontend Development` `Vanilla JS` `No-Framework Development`

---

## Related Projects

- 🔗 [dq-dashboard](https://github.com/samshai5/dq-dashboard) — Frontend data quality dashboard (HTML/CSS/JS)
- 🔗 [Trading](https://github.com/samshai5/Trading) — AI-powered trading signal engine
- 🔗 [sql-dq-engine](https://github.com/samshai5/sql-dq-engine) — SQL data quality rule engine
- 🔗 [snowflake-dq-project](https://github.com/samshai5/snowflake-dq-project) — Enterprise DQ framework in Snowflake

---

*Built by Sam Shaikh — Computer Science student at the University of Houston, passionate about frontend development, data visualization, and building interactive tools that make complex data easy to explore.*
