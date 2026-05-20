# Carbon Audit — Custom Event Calculator

> *"If your conference is about saving the planet, its carbon bill should reflect that."*

A custom-variable carbon footprint calculator for conferences and events in **Pakistan and South Asia** — built as a fully static, single-file tool with no backend, no framework, and no build step. Open it. Dial in your numbers. See the truth.

**🌐 Live:** [carbon-accountability-conference-ve.vercel.app](https://carbon-accountability-conference-ve.vercel.app/)

---

## Why this exists

Climate conferences talk a lot about emissions. Most of them produce a lot of them too.

This tool was built out of frustration with that gap — and a genuine curiosity about what it would look like if event organisers actually had to face their own numbers before printing the programme. It's not an accusation. It's a mirror.

The calculator was developed iteratively through a research-backed methodology specific to Pakistan's grid, travel patterns, and climate context. It is v4 in a series — earlier versions used fixed presets; this one lets you input your own event's real variables.

---

## What it calculates

Six emission clusters, fully adjustable via sliders:

| Cluster | What's counted |
|---|---|
| ✈️ Transport | International flights, domestic flights, road travel, local commutes |
| 🏛️ Venue & Energy | Pakistan grid consumption, generator diesel, cooling load |
| 🍽️ Catering | Food type (vegan → meat-heavy), meals served, waste |
| 🏨 Accommodation | Hotel nights, star rating, HCMI benchmarks |
| 📦 Materials | Printed materials, merchandise, plastic, signage |
| 💻 Digital & AV | Streaming, screens, data transfer, broadcast |

---

## Output panels

- **Total tCO₂e** with per-capita breakdown and severity rating
- **Donut chart** — emission share by cluster
- **Ranked bar chart** — biggest offenders first
- **The Distance Score** — a single metric measuring the gap between what a conference advocates for and what it actually emits
- **Real-world consequences** — 6 Pakistan-specific frames (trees, glaciers, households, etc.)
- **GET Standards Compliance** — UNEP/GORD framework, 10 dimensions, live-scored green / amber / red
- **What-If Panel** — 5 intervention scenarios (virtual option, vegan catering, local-only, renewable energy, offset purchase)
- **Counterfactual Clock** — 7 frames showing what the same carbon budget could have funded instead (solar panels, school meals, reforestation, etc.)

---

## Language

Full **English ↔ اردو** toggle. All output narrative — consequence statements, GET commentary, clock frames, Distance score — switches to Noto Nastaliq Urdu on demand. Structural inputs stay in English.

---

## Presets

Three built-in configurations to get started quickly:

- **BREATHE Pakistan 2026** — 250 attendees, 1 day, 5-star venue in Islamabad *(the original use case)*
- **Small Conference** — 80 attendees, 1 day, local-heavy travel pattern
- **Large International Summit** — 1,500 attendees, 3 days, high international travel mix

---

## Methodology & emission factors

| Source | Used for |
|---|---|
| Yousuf et al. 2014 | Pakistan grid: **0.566 tCO₂/MWh** |
| ICAO Carbon Calculator | International & domestic flights |
| Poore & Nemecek 2018 | Food system emissions by diet type |
| HCMI Hotel Benchmarks | Accommodation by star rating |
| GHG Protocol / ISO 20121 | Compliance framing |

> These are **estimates**, not certified GHG audits. For formal reporting, engage a GHG Protocol or ISO 20121 certified auditor.

---

## Tech

- Vanilla HTML + CSS + JS — **single file, zero dependencies**
- No React. No npm. No build step. No server.
- Google Fonts only (DM Sans · DM Mono · Cormorant Garamond · Noto Nastaliq Urdu)
- Deploys as static HTML on Vercel — no `vercel.json` needed

---

## Credits

Designed and built with curiosity by **Haris Ahmad Khan**.  
Developed using a research-backed carbon methodology for Pakistan and South Asia climate events.

---

*This tool does not store any data. All calculations happen locally in your browser.*
