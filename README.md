# SIGNAL — The Human Story of Connection
### Frontend Odyssey: Interactive Web Experience Challenge

> *From the first mark pressed into cave stone to the infinite threads of the digital age — an immersive journey through how humanity has always reached across distance to touch each other.*

---

## Live Demo

🔗 **[View Live Site](https://imaginative-faun-1d7af2.netlify.app/)** ← *(replace with your Netlify / Vercel / GitHub Pages URL)*

---

## Project Description

**SIGNAL** is an immersive, scroll-driven storytelling website that traces the complete arc of human communication — from prehistoric cave paintings to artificial intelligence. The central thesis is simple and timeless: every technology ever invented has been an elaboration of a single primal urge — to reach across distance and touch another conscious mind.

The experience unfolds across five narrative sections. The **Hero** opens with a living particle constellation, setting a tone of cosmic scale. **Origin** reveals the cave painting era through hand-drawn SVG animations that recreate the act of mark-making in real time. **Evolution** uses a horizontal scroll mechanism to carry visitors through five transformative eras — Writing, Print, Telegraph, Internet, and AI — each rendered as an interactive card with mouse-reactive lighting. **Convergence** presents the staggering scale of today's connected world through animated counters and a clickable historical timeline. Finally, **Beyond** invites reflection with a floating atmospheric canvas and a magnetic call-to-action button.

The design language draws on editorial restraint — a deep void palette punctuated by aged gold and ice blue, paired with Cormorant Garamond (for timeless weight) and JetBrains Mono (for technical precision). Every detail — the lagging cursor ring, the film grain overlay, the SVG path draws — reinforces the theme: signal is fragile, deliberate, and beautiful.

---

## Technical Highlights

| Requirement | Implementation |
|---|---|
| **5+ Story Sections** | Hero · Origin · Evolution · Convergence · Beyond |
| **Scroll Effect 1** | Hero parallax — title and canvas shift on scroll depth |
| **Scroll Effect 2** | Horizontal card carousel driven entirely by vertical scroll position |
| **Scroll Effect 3** | Sticky progress bar tracking Evolution section depth |
| **Interaction 1** | Custom two-layer cursor (dot + lagging ring) with hover state |
| **Interaction 2** | Evolution cards with radial mouse-position glow via CSS custom properties |
| **Interaction 3** | Magnetic "Begin Again" button — physically follows cursor, snaps back |
| **Interaction 4** | Clickable timeline dots that animate a progress fill bar |
| **Animation 1** | Counting loader (0 → 100%) with fade-out transition |
| **Animation 2** | Hero particle constellation — animated nodes with connecting lines |
| **Animation 3** | Cave art SVG path draw-on (stroke-dashoffset animation) |
| **Animation 4** | Scroll-triggered animated counters (5B users, 333B emails, 500M posts) |
| **Animation 5** | Floating atmospheric orb canvas in the conclusion section |
| **Responsive** | Mobile-first grid collapse, hidden nav links on small screens |

---

## Tech Stack

- **HTML5 / CSS3 / Vanilla JavaScript** — zero dependencies, zero build step
- **Canvas API** — hero constellation + conclusion orbs
- **SVG Animation** — cave art path drawing + SVG `<animate>` star blinks
- **IntersectionObserver API** — scroll-triggered reveals and counter start
- **Google Fonts** — Cormorant Garamond + JetBrains Mono
- **CSS Custom Properties** — full design token system

---

## Getting Started

No build step required. Just open `index.html` in any modern browser.

```bash
git clone https://github.com/YOUR_USERNAME/signal-story.git
cd signal-story
open index.html
```

---

## Deployment

### Option A — GitHub Pages (Free, Instant)
```bash
# In your repo on GitHub:
# Settings → Pages → Source: Deploy from branch → main → / (root) → Save
# Your site will be live at: https://YOUR_USERNAME.github.io/signal-story
```

### Option B — Netlify (Recommended)
```bash
# 1. Go to netlify.com → "Add new site" → "Import an existing project"
# 2. Connect your GitHub repo
# 3. Build command: (leave blank)
# 4. Publish directory: . (root)
# 5. Click Deploy — live in ~30 seconds
```

### Option C — Vercel
```bash
npm i -g vercel
vercel
# Follow prompts — select the project folder, no framework preset needed
```

---

## File Structure

```
signal-story/
└── index.html       # Complete self-contained experience
└── README.md        # This file
```

---

## Design Decisions

- **Color** — Deep void (`#050508`) anchors the void of prehistoric darkness; aged gold (`#c9a84c`) represents preserved, enduring signal; ice blue (`#7dd3fc`) marks the cold precision of digital transmission.
- **Typography** — Cormorant Garamond for editorial gravitas and historical weight; JetBrains Mono for the technical, modern layer.
- **Film grain overlay** — A subtle SVG-noise texture at 2.8% opacity adds analog warmth and prevents the design from feeling purely digital.
- **Cursor** — A two-layer lagging cursor (sharp dot + slow ring) creates physical weight; it becomes the user's primary tactile relationship with the page.

---

*Built for the Frontend Odyssey Interactive Web Experience Challenge.*
