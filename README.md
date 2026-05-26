# 🪓 Trail Blazed

> *"The trail was hard enough before the lawnmower showed up."*

**Trail Blazed** is a single-player 2D side-scrolling platformer built for an AI Master's course assignment on the theme of *American Weekend Vacation*.

---

## 🎮 Game Concept

The Blaze family is hosting Grandma's birthday BBQ when Dad's backyard time machine goes haywire — pulling the entire party into 1848 Oregon Trail country. The machine landed in their wagon in pieces. The only way home: travel the trail, collect gold, and repair the time machine one component at a time.

The catch? The malfunction dragged half the BBQ with them. A toy drone. A riding lawnmower. A bandit who somehow got hold of the archery set. The trail just got weird.

---

## 👨‍👩‍👧‍👦 The Blaze Family

| Key | Character | Ability |
|-----|-----------|---------|
| `1` | **Clark** (Dad) — cooky inventor | Repair Boost: doubles gold value temporarily |
| `2` | **Ellen** (Mom) — secretly loves the chaos | Reveal: highlights nearby hidden gold |
| `3` | **Rusty** — the athlete | Sprint burst + double jump |
| `4` | **Audrey** — the artist | Stun: music blast freezes nearby enemies |
| `5` | **Marty** — the historian/scientist | Detect: arrow points to nearest gold |

Switch characters on the fly with keys **1–5**. Each obstacle has an optimal character.

---

## 🕹️ Controls

| Input | Action |
|-------|--------|
| `Arrow Keys` / `Space` | Move & Jump |
| `Z` | Character Special Ability |
| `1–5` | Switch Family Member |
| `Enter` | Confirm / Continue |

---

## 📋 Screens

- **Title Screen** — Animated night sky, wagon train silhouettes, campfires
- **Narrative Panels** — Oregon Trail-style story intro (4 panels)
- **Gameplay** — Side-scrolling platformer, Level 1: The Open Prairie
- **Game Over / Win** — Score summary
- **High Scores** — 3-character initials entry, persisted via `localStorage`
- **How to Play** — Controls and ability reference

---

## 🏆 Objective

Collect **12 gold nuggets** (or reach Fort Laramie) to repair the time machine component and complete the level. Food pickups restore health. Stomp enemies from above.

---

## 🛠️ Tech Stack

- Vanilla HTML5 Canvas + JavaScript
- Zero dependencies, zero frameworks
- Single file: `index.html`
- High scores stored in `localStorage` (no server required)
- SNES-inspired pixel art drawn programmatically via Canvas 2D API

---

## 🚀 Running the Game

Open `index.html` in any modern browser. No build step, no install, no server required.

```bash
# Clone the repo
git clone https://github.com/FlightsandGigabytes/trail-blazed.git

# Open in browser
open index.html
```

---

## 🗺️ Roadmap

- [ ] Level 2: Fork in the River
- [ ] Level 3: The Mountain Pass & Gold Mine
- [ ] Sound effects and background music
- [ ] Mobile touch controls
- [ ] Animated cutscenes between levels
- [ ] Boss fight: Bandit King on the lawnmower

---

*Built as part of the Applied Artificial Intelligence Master's Program coursework.*  
*Inspired by Oregon Trail (1971), Super Mario Bros (1985), and an unreasonable amount of family BBQs.*
