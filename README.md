# Carbon Audit — Custom Event Calculator

A custom-variable carbon footprint calculator for conferences and events in Pakistan and South Asia. Built as a fully static, single-file tool — no backend, no framework, no build step.

**Live:** [carbon-accountability-conference-version.vercel.app](https://carbon-accountability-conference-version.vercel.app)

---

## What it does

Lets event organisers dial in their own event's actual numbers — attendees, flight patterns, venue size, catering choices, accommodation, materials, digital footprint — and get a live carbon estimate across six emission clusters.

Output panels include:
- Total tCO₂e with per-capita breakdown
- Donut chart by cluster
- Ranked cluster bar chart
- The Distance score — gap between advocacy and action
- Real-world consequences (6 frames, Pakistan-specific)
- GET Standards Compliance (UNEP/GORD, 10 dimensions, live-scored)
- What-if panel (5 intervention scenarios)
- Counterfactual Clock (7 frames — what the carbon cost could have funded instead)

Includes a full **English ↔ اردو** toggle — all output narrative switches to Noto Nastaliq Urdu on demand. Structural inputs stay in English.

---

## Methodology

- Emission factors: Pakistan grid (0.566 tCO₂/MWh — Yousuf et al. 2014), ICAO flight factors, Poore & Nemecek 2018 (food), HCMI hotel benchmarks
- These are estimates, not certified GHG audits
- For certification: GHG Protocol or ISO 20121

---

## Presets

Three built-in presets load representative configurations:
- **BREATHE Pakistan 2026** — 250 attendees, 1 day, 5-star Islamabad venue
- **Small Conference** — 80 attendees, local-heavy
- **Large International Summit** — 1,500 attendees, 3 days, high international travel

---

## Credits

Designed and built with curiosity by Haris Ahmad Khan.
