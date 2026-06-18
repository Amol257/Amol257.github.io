# amol257.github.io — Portfolio

[![Portfolio Live](https://img.shields.io/badge/Live-amol257.github.io-00FF41?style=for-the-badge&logo=github&logoColor=black&labelColor=0D1117)](https://amol257.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117)](https://www.linkedin.com/in/amol-singhal257/)
[![Email](https://img.shields.io/badge/Email-amol.singhal25@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117)](mailto:amol.singhal25@gmail.com)

Personal portfolio of **Amol Singhal** — Data Analyst and final-year B.Tech CSE (Data Science) student at ABESIT, Ghaziabad, graduating August 2026.

---

## Overview

A single-file, production-grade portfolio site built without any frontend framework. Every visual, interaction, and animation is handcrafted in vanilla HTML, CSS, and JavaScript. The design prioritises recruiter readability with editorial typography and a minimal dark-mode-first aesthetic.

### Design System

| Token | Value |
|---|---|
| Background | `#000000` |
| Ink | `#f0ece4` |
| Accent | `#c8ff00` (lime) |
| Display font | Bebas Neue |
| Mono font | DM Mono |
| Serif font | Fraunces |

Light mode (`[data-theme="light"]`) switches to a warm parchment palette (`#f5f0e8` / amber `#8a5a00`).

---

## Features

- **Cinematic loader** — name types out letter-by-letter with a blinking cursor and expanding progress line
- **Canvas effects** — three simultaneous WebGL-style canvas animations: floating particle mesh, perspective grid, and a neural-network node system that colour-shifts per section
- **Sticky project dashboard** — a live-preview pane shows bespoke SVG data visualisations (fund leaderboard, risk heatmap, AQI bar chart, pipeline diagram) as you hover each project row
- **Expandable project rows** — click to reveal a BEFORE / PROBLEM / FIX / RESULT story card with full stack tags
- **Expandable experience rows** — same pattern for work history with bullet points and tech tags
- **Skills orbital** — rotating orbital paths around a central avatar; each skill tag orbits at a different radius and speed
- **Marquee divider** — animated scrolling ticker between sections
- **Theme toggle** — seamlessly swaps between dark and light with all canvas colours, SVG fills, and glow effects adapting
- **Copy-email CTA** — one-click copies email to clipboard with visual feedback
- **Film grain + scanlines** — fixed overlays for a cinematic texture
- **Custom cursor** — 10px dot that expands to 56px on hover with mix-blend-mode difference
- **Scroll-reveal** — all sections fade and translate in via IntersectionObserver
- **Scroll progress bar** — 2px accent-coloured line at the top of the viewport

---

## Sections

| # | Section | Key Content |
|---|---|---|
| 01 | HERO | Name, role tagline, availability status, three canvas backgrounds |
| 02 | ABOUT | Bio paragraph, fact list (education, stack, internships), KPI cards |
| 03 | PROJECTS | FundScope · India AQI Dashboard · UPI Fraud Risk Analyser · PM-eBus KPI |
| 04 | EXPERIENCE | NCRTC · Internship Studio · Zidio — expandable role detail |
| 05 | SKILLS | Power BI · SQL · Python · React · DAX · Excel — orbital display |
| 06 | BUILDING | In-progress projects with status indicators |
| 07 | CONTACT | Email copy, GitHub, LinkedIn, CV download |

---

## Projects Showcased

### FundScope — Indian Mutual Fund Analyser
Composite scoring engine for 28 Indian mutual funds across 5 categories. Calculates CAGR, Sharpe, Alpha, Volatility, and a weighted composite score. Full-stack: Python backend + Next.js 15 UI.
→ [github.com/Amol257/fundscope](https://github.com/Amol257/fundscope)

### India AQI Dashboard
Real-time national air quality tracker aggregating data from 511 CPCB monitoring stations across 28 states. Gemini AI integration for contextual health-risk insights.
→ [amol257.github.io/india-aqi-dashboard](https://amol257.github.io/india-aqi-dashboard/)

### UPI Fraud Risk Analyser
Multi-page analytics site analysing UPI payment fraud patterns across 120 bank-channel pairs over 60 months (Jan 2020–Dec 2024). Z-score velocity anomaly detection + MinMaxScaler risk scoring (0–100).

### PM-eBus Sewa KPI Dashboard
Power BI dashboards built during NCRTC internship to track live fleet operations for 6,000+ buses under India's PM-eBus Sewa programme.

---

## Tech Stack

```
HTML5 · CSS3 · Vanilla JavaScript
Canvas API (three simultaneous animation loops)
Google Fonts (Bebas Neue · DM Mono · Fraunces)
IntersectionObserver API
Clipboard API
```

Zero npm dependencies. Zero build step. Single `index.html` file.

---

## File Structure

```
Amol257.github.io/
├── index.html                     # Entire site — HTML + CSS + JS in one file
├── AMOL_SINGHAL_Data_Analyst.pdf  # Downloadable CV
└── README.md
```

---

## Running Locally

No build step required. Clone and open:

```bash
git clone https://github.com/Amol257/Amol257.github.io.git
cd Amol257.github.io
open index.html   # or use Live Server in VS Code
```

---

## Performance Notes

- All fonts loaded via Google Fonts with `display=swap`
- Canvas animations use `requestAnimationFrame` with lazy init after the loader completes
- Film grain sourced from `grainy-gradients.vercel.app` (single external request)
- No JavaScript frameworks, no bundlers, no runtime dependencies

---

## Contact

Open to **Data Analyst**, **BI Analyst**, and **Business Analyst** roles in Delhi NCR — August 2026.

| Channel | Link |
|---|---|
| Portfolio | [amol257.github.io](https://amol257.github.io) |
| LinkedIn | [linkedin.com/in/amol-singhal257](https://www.linkedin.com/in/amol-singhal257/) |
| Email | amol.singhal25@gmail.com |
| GitHub | [github.com/Amol257](https://github.com/Amol257/) |
