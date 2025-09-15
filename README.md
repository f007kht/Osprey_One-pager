# Osprey One‑Pager (TalonStrike Profile)

A single‑page, **IC‑ready** company profile for **Osprey Intel LLC — TalonStrike**, optimized for private‑capital workflows (VC/PE/FO). It ships as a static HTML/CSS/JS artifact and is built to demo **agentic vertical AI** outputs (dual‑cited, decision‑grade) in a familiar one‑pager format.

> TL;DR: open `index.html` in a browser for the current one‑pager. For the latest content aligned to this thread’s updates (Market Sizing + Competitive/WTP cards), use **`index.v2.html`** (included).

---

## Contents

- [Live Preview](#live-preview)
- [Repo Structure](#repo-structure)
- [Quick Start](#quick-start)
- [What’s in the Page](#whats-in-the-page)
- [Editing the Two Updated Cards](#editing-the-two-updated-cards)
- [Market Sizing Calculators](#market-sizing-calculators)
- [Competitive Landscape & WTP](#competitive-landscape--wtp)
- [Theming & Assets](#theming--assets)
- [Governance & Data Usage](#governance--data-usage)
- [Deploying (GitHub Pages / Static Host)](#deploying-github-pages--static-host)
- [Changelog](#changelog)
- [License](#license)

---

## Live Preview

- **Open locally:** double‑click `index.html` (or `index.v2.html`).  
- **Python server (recommended):**
  ```bash
  cd Osprey_One-pager-main
  python3 -m http.server 8000
  # then visit http://localhost:8000 in your browser
  ```
- **Node (alternative):**
  ```bash
  npm i -g http-server
  http-server -p 8000
  ```

> **Note:** `index.v2.html` includes the latest content updates you requested in this thread (Consolidated Market Sizing + Competitive/WTP). Keep `index.html` as your baseline; promote `index.v2.html` to `index.html` when ready.

---

## Repo Structure

```
Osprey_One-pager-main/
  case study_broadview ventures.html
  case study_fall line capital.html
  case study_superlumincal rx.html
  index.html
  index.v2.html
  osprey_products.horizontal.html
  README.md
  LICENSE
  artifacts/
    1_autus_dashboard_preview main.html
    2_Current Standard of Care.html
    3a_Pediatric Pulmonary Valve Market_Bottom Up.html
    3b_Pediatric Pulmonary Valve Market_A Top-Down Analysis.html
    3c_U.S. Pediatric Pulmonary Valve Market_Executive Brief.html
    4_Autus Valve Clinical Trial Dashboard.html
    5_Competitive Landscape Autus Valve vs. Medtronic TPVs.html
    Consolidated_Deep_Dive_Dashboard_client_friendly.html
    GPCR Licensing One‑Pager.html
    index.html
    investor-brief.html
    Osprey Intel Deep Dive_Valve & Conduit Replacement_Pediatric CHD.html
    references.html
    regulatory.html
    vc-toolkit.html
    Craig D'cruz LinkedIn Profile.pdf
    GLP-1 and GPCR Deep Dive.pdf
    Jose Caraveo LinkedIn Profile.pdf
    Osprey Intel LLC - Sector Deep Dive Strategy & Data Infrastructure.pdf
    Osprey Intel LLC - Sector Deep Dive Strategy & Data Infrastructure_DG.pdf
    Pediatric Congenital Heart Disease (CHD)_Osprey Deep Dive.pdf
    Project Talon_GPCR Deals Starter Database_Cortellis Update.pdf
    Project Talon_GPCR Deals Starter Database_Interim Update.pdf
    Project Talon_GPCR Deals Starter Database_Report_DRAFT .pdf
    Project Talon_Water Sector Deep Dive.pdf
    images/
      autus-logo.png
      autus_valve_render.png
      boston_childrens.png
      Brigham and Women's Hospital.png
      del_nido.jpg
      edelman.jpg
      Edwards logo.png
      graziadio_logo_2024_linear_color_Logo.png
      Harvard Medical School.png
      heyninck-jantz.jpg
      hofferberth.jpg
      Logo_of_the_University_of_Melbourne.svg.png
      medtronic-2048.png
      MIT.png
      NIDO.png
      patent_expansion.png
      patent_invivo.png
      University of Wisconsin-Madison.png
      university-of-southern-california-usc-logo.png
  brand/
    osprey-in-flight.png
    osprey-spirit.png
    products-splash.png
    profile-landscape.png
    speed-accuracy.png
  images/
    broadview-logo-1.png
    craig-credentials-aws-cloud-practitioner.png
    craig-education-case-western-reserve-university.png
    craig-headshot.jpg
    craig-work-experience-accenture-logo.png
    craig-work-experience-github-emblem.png
    craig-work-experience-morsum.png
    craig-work-experience-vanguard-emblem.png
    fall-line-capital.png
    jose-credentials-cfp-board-oip.webp
    jose-credentials-finra.png
    jose-education-asu-wp-carey-horiz-cmyk-print-maroongold-logo.jpg
    jose-headshot-jose.jpg
    jose-work-experience-lek-logo.png
    jose-work-experience-morgan-stanley-logotipo-2001-2006.png
    jose-work-experience-northern-trust.png
    jose-work-experience-usaa-emblem.png
    supreluminal-rx-logo-color-horisontal.png
    tuck-logo.png
    rename-map.txt
```

Key entry points:
- **`index.html`** – main one‑pager (baseline).
- **`index.v2.html`** – updated one‑pager reflecting 2025‑09‑15 card updates (see below).
- **`case study_*.html`** – linked case studies for Broadview Ventures, Fall Line Capital, Superluminal Medicines.
- **`artifacts/`** – deep‑dive module artifacts and supplementary pages (market models, SoC, etc.).
- **`brand/`, `images/`** – assets used across cards.
- **`LICENSE`** – MIT license file.

---

## What’s in the Page

Sections are reachable via the left‑hand nav and scrollspy:
1. **Company Profile** — Osprey Intel positioning, hero, founders modal, company facts.  
2. **Private vs. Public Markets** — tabs for sourcing, screening, diligence, artifacts.  
3. **Overview & Timeline** — Spring ’25 → formation → summer ’25 stealth projects → Aug 18, 2025 delivery.  
4. **Market Sizing** — **Consolidated TAM/SAM/SOM**: top‑down (deal‑attached Deep Dives), bottom‑up license (TalonStrike), adjacencies (PE add‑ons, Secondaries).  
5. **Competitive & WTP** — positioning vs CI suites / report providers / DIY; WTP anchors; KPI chips; packaging.  
6. **Delivery & Governance** — process, SLAs, licensed‑data only, dual‑citation.  
7. **Case Studies** — 3 clickable cards with linked pages.  
8. **Technology & Methodology** — agentic orchestration, licensed ingestion, RAG graph, dual‑citation QA.

The page is pure static HTML/CSS/JS (no build step).

---

## Editing the Two Updated Cards

> The following edits are **already applied** in `index.v2.html`.

### A) Consolidated Market Sizing (TAM/SAM/SOM)
- **Executive Brief** (client view):  
  - Project TAM (services): Beachhead Deep Dives **~$19.4M run‑rate**; PE add‑ons **~$8.3M (base)** → **Combined ≈ $27.7M** (range **$13.0M–$54.9M**).  
  - License SAM/SOM (NA): **SAM $47.6M**; **SOM $3.8M–$7.1M** (8–15% adoption). **ICP‑narrow SAM $19.1M–$28.6M**; **SOM $1.5M–$4.3M**.
- **Top‑Down — Beachhead Verticals (deal‑attached projects)**  
  - Healthtech VC deals: **2024: 849**; **H1’25: 414**.  
  - Pharma biotools VC deals: **2024: 282**; **H1’25: 232**.  
  - Attach: **20–40%**; Price: **$40k–$60k**.  
  - 2024 actuals: **$9.0M–$27.1M** (base **$17.0M**). 2025 run‑rate (H1×2): **$10.3M–$31.0M** (base **$19.4M**).
- **Bottom‑Up — License (TalonStrike)**  
  - Active teams proxy: **1,379** TTM funds (global) × **57.6% NA** ⇒ **~794 NA teams**.  
  - Price: **$60k ARR/team**; Adoption in 24–36 mo: **8–15%** ⇒ **SOM $3.8M–$7.1M**.  
  - ICP filter (40–60% of teams): **SAM $19.1M–$28.6M; SOM $1.5M–$4.3M**.
- **Adjacencies**  
  - **PE Buyout Add‑ons (Big Seven TTM $83.10B; +65.3% YoY):** Base TAM **$8.3M** (Cons **$2.7M**; Agg **$23.9M**).  
  - **US VC Direct Secondaries & SPVs:** Midpoint **$61.10B**; known platforms/providers **$24.70B** with **$19.30B** tenders (~85 @ $130M) → **Combined TAM $2.6M–$35.5M** (base **$8.2M**).
- **IC takeaway**: Treat **$3.8–$7.1M SOM** as the license wedge; services TAM (**$27.7M base**) + adjacencies create a credible path to materially larger obtainable revenue as modules are productized and attach sustained.

### B) Competitive Landscape & WTP Anchors
- **Positioning (category vs. gap we exploit)**  
  - CI suites (AlphaSense, Tegus): **breadth/transcripts** → **gap:** no decision artifacts; limited frontier scaffolds.  
  - Life‑sci data/report providers: **datasets/reports** → **gap:** static PDFs; slow to thesis‑fit.  
  - DIY BI & docs: **flexible/cheap** → **gap:** time sink; no dual‑citation governance.
- **WTP anchors (validated/provisional)**  
  - Projects: VC Deep Dive **$40–$60k**; PE add‑on **$40–$60k**; Secondaries — blocks **$15–$30k**, tenders **$40–$60k**.  
  - Annual License (Team): **$60k** (Core) / **$90k** (Pro) / **$150k+** (Enterprise).  
  - Annual License (Firm): **$90–$150k** baseline; scalable by seats & credits.  
  - KPI chips: **GM 70–75%**, **CAC payback <6 mo**, **NRR >120%**.  
  - **GTM & packaging:** Credit‑bundled licenses to keep attach high; PE add‑on packs (e.g., **5‑pack $225k**, **10‑pack $430k**).  
  - **Demand signals:** Secondaries platform/small‑block flow **$5.40B** (non‑tender), **85** tenders @ **$130M** avg; attach/price sensitivity as shown.

> **Where to edit by hand:** open `index.html` (or `index.v2.html`) and scroll to the sections with `id="sizing"` and `id="competitive"`. Cards are standard HTML blocks with bullets/tables and light‑weight KPI “chips”.

---

## Market Sizing Calculators

The page embeds small calculators to keep **Top‑Down**, **PE add‑ons**, and **Secondaries** in sync:
- Sliders/inputs are wired in the footer script; IDs include `htAttach`, `htPrice`, `btAttach`, `btPrice`, `peShare`, `peEquity`, `peAttach`, `pePrice`, plus Secondaries helpers (`avgBlock`, `attach`, `price`).
- Display elements for readouts use `...Val` IDs (e.g., `htTamVal`, `beachTamVal`, `peTamVal`, `combinedVal`).  
- All math is visible and adjustable; results feed the **Executive Brief** and KPI chips to preserve “client view” narrative.

**Guardrail:** keep both **Healthtech** and **Biotools** verticals in Top‑Down; that preserves the reconciled 2024/2025 base math.

---

## Competitive Landscape & WTP

The **Positioning** table and **WTP Anchors** bullets are plain HTML. Edits do not require any build step; just change the text, ranges, or add/remove rows. KPI chips are semantic spans with classes (`kpi`, `kpi good`, `kpi info`, `kpi warn`).

Packaging guidance is spelled out and ready to port into pricing pages or sales collateral (credits, seat tiers, attach packs).

---

## Theming & Assets

- Colors and spacing use CSS custom properties in the `<style>` block (`--bg`, `--panel`, `--accent`, etc.).  
- Background “scrim” overlays improve text contrast on image‑backed cards.  
- Brand assets live in `brand/` and `images/`. Swap logos or hero artwork without touching layout.  
- Founders modal and case‑study logos are responsive (hover/contrast tuned).

---

## Governance & Data Usage

- **Licensed data only**; public web kept sandboxed.  
- **Dual‑citation**: every claim ties to (1) primary source, and (2) analyst note/snippet.  
- QA gate checks citation presence, link health, and scope conformity.  
- Share‑safe exports (client watermarking, redaction, view‑only links).

---

## Deploying (GitHub Pages / Static Host)

This repo is pure static content. Any static host works.

- **GitHub Pages**: push to `main` and enable Pages → Source: `main` → `/ (root)`. Entry file is `index.html`.  
- **S3/Cloudflare/Netlify/Vercel**: upload the folder and set entry to `index.html`.  
- **Security**: No PII/MNPI handled unless explicitly contracted; keep environment fully static.

---

## Changelog

- **2025-09-15** — Added `index.v2.html` with updated **Market Sizing** and **Competitive/WTP** cards; README overhauled.  
- **2025‑08‑18** — Broadview Ventures CHD static deck + PPV TalonStrike micro‑app suite delivered; case study page added.  
- **2025‑Summer** — Initial one‑pager, founders modal, navigation, and module sections created.

---

## License

MIT © 2025 José. See [`LICENSE`](./LICENSE).

---

### Insight Tags
`#MarketSizing` `#WTP` `#GTM` `#InvestorTrends` `#RegWatch`

