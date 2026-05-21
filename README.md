# Carbon Audit — Custom Event Calculator

> *"If your conference is about saving the planet, its carbon bill should reflect that."*

A custom-variable carbon footprint calculator for conferences and events in **Pakistan and South Asia**, built as a fully static, single-file tool with no backend, no framework, and no build step. Open it, dial in your numbers, and see the truth.

**🌐 Live:** [carbon-accountability-conference-version.vercel.app](https://carbon-accountability-conference-version.vercel.app/)

## Why this exists

Climate conferences talk a lot about emissions. Most of them produce a lot of them too.

This tool was built out of frustration with that gap and a genuine curiosity about what it would look like if event organisers actually had to face their own numbers before printing the programme. It is not an accusation. It is a mirror.

The calculator was developed iteratively through a research-backed methodology specific to Pakistan's grid, travel patterns, and climate context. It is v4 in a series where earlier versions used fixed presets, and this one lets you input your own event's real variables.

## What it calculates

The tool covers six emission clusters, all fully adjustable via sliders.

| Cluster | What's counted |
|---|---|
| ✈️ Transport | International flights, domestic flights, road travel, local commutes |
| 🏛️ Venue & Energy | Pakistan grid consumption, generator diesel, cooling load |
| 🍽️ Catering | Food type (vegan to meat-heavy), meals served, waste |
| 🏨 Accommodation | Hotel nights, star rating, HCMI benchmarks |
| 📦 Materials | Printed materials, merchandise, plastic, signage |
| 💻 Digital & AV | Streaming, screens, data transfer, broadcast |

## Output panels

The tool generates several output panels that update live as you move the sliders. These include a total tCO₂e figure with per-capita breakdown and severity rating, a donut chart showing emission share by cluster, and a ranked bar chart with the biggest offenders first. The Distance Score measures the gap between what a conference advocates for and what it actually emits. Real-world consequences translate the number into six Pakistan-specific frames covering trees, glaciers, households, and more. The GET Standards Compliance panel scores your event against the UNEP/GORD framework across 10 dimensions, live-scored green, amber, or red. The What-If Panel runs five intervention scenarios including a virtual option, vegan catering, local-only attendance, renewable energy, and offset purchase. Finally, the Counterfactual Clock shows seven frames of what the same carbon budget could have funded instead, from solar panels to school meals to reforestation.

## Language

The tool includes a full English and اردو toggle. All output narrative including consequence statements, GET commentary, clock frames, and the Distance Score switches to Noto Nastaliq Urdu on demand. Structural inputs stay in English.

## Presets

Three built-in configurations are available to get started quickly. BREATHE Pakistan 2026 loads a 250-attendee, one-day event at a five-star venue in Islamabad, which was the original use case for the tool. The Small Conference preset covers 80 attendees over one day with a local-heavy travel pattern. The Large International Summit preset models 1,500 attendees across three days with a high international travel mix.

## Methodology and emission factors

The emission factors used in this tool are drawn from the following sources.

| Source | Used for |
|---|---|
| Yousuf et al. 2014 | Pakistan grid: **0.566 tCO₂/MWh** |
| ICAO Carbon Calculator | International and domestic flights |
| Poore & Nemecek 2018 | Food system emissions by diet type |
| HCMI Hotel Benchmarks | Accommodation by star rating |
| GHG Protocol / ISO 20121 | Compliance framing |

These are estimates and not certified GHG audits. For formal reporting, engage a GHG Protocol or ISO 20121 certified auditor.

## Tech

This tool is built with vanilla HTML, CSS, and JavaScript as a single file with zero dependencies. There is no React, no npm, no build step, and no server. It uses Google Fonts only, specifically DM Sans, DM Mono, Cormorant Garamond, and Noto Nastaliq Urdu. It deploys as static HTML on Vercel with no configuration file needed.

## Credits

Designed and built with curiosity by **Haris Ahmad Khan**. Developed using a research-backed carbon methodology for Pakistan and South Asia climate events.

*This tool does not store any data. All calculations happen locally in your browser.*
