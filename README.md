# Sentinel of the Dawn-Lit Mountains (Vol. XIV, Issue 10)
### *Securing the Northeast: Indian Army’s Role in Stability, Peace & National Security*

![Format](https://img.shields.io/badge/Format-ISO_A4_Print--Ready_(50_Pages)-1f3324?style=for-the-badge)
![Edition](https://img.shields.io/badge/Edition-Sep--Oct_2026_Dossier-c59b27?style=for-the-badge)
![Tech](https://img.shields.io/badge/Stack-HTML5_%7C_CSS3_Print_%7C_Vanilla_JS-142117?style=for-the-badge)
![Citations](https://img.shields.io/badge/Verified_Dispatches-28_Articles_%7C_19_Sources-8b1e1e?style=for-the-badge)

> **Live Interactive Preview:** [Insert Your GitHub Pages Link Here]  
> **Editorial Window:** 01 September 2026 – 03 October 2026 (30-Day Verified Intelligence & Press Dossier)

---

## Overview

**Sentinel of the Dawn-Lit Mountains** is a **50-page, publication-grade digital e-magazine** documenting the multi-domain operations, frontier engineering, sporting triumphs, and civic-action outreach of the **Indian Army**, **Assam Rifles**, and **Border Roads Organisation (BRO)** across the eight states of Northeast India.

Engineered as a **zero-dependency, single-file web application**, this project combines dual-mode editorial reading on screen with pixel-accurate **ISO A4 portrait (`210mm × 297mm`) PDF export** via native browser print media queries.

---

## Key Highlights & Editorial Scope

* **Strict 30-Day Recency Mandate:** All **28 featured articles** were published on or after **01 September 2026**, complete with direct source citations and clickable verification URLs.
* **Five Core Strategic Pillars:**
  1. **Security & Strategic Affairs (Pages 06–15):** Induction of 45 BonV Aero heavy-payload logistics UAVs under Eastern Command, Indian Oil's `-33°C` Xtreme Weather Grade diesel rollout to Sikkim & Arunachal, Trishakti Corps high-altitude exercises, Indo-Myanmar border fencing defense in Changlang, calibrated AFSPA review, ₹1.10 Lakh Cr DAC clearance, and 199th Gunners' Day.
  2. **Regional News & Internal Stability (Pages 16–25):** Joint Police-Assam Rifles weapons and mortar recoveries in Chandel, Molcham, and Sajirok (Manipur); ₹35.89 Crore anti-smuggling and narcotics interdictions in Champhai (Mizoram); USRA cadre apprehensions; and NIA counter-terror accountability.
  3. **Development, Infrastructure & Sustainability (Pages 26–32):** BRO's ₹215.58 Crore twin border road EPC packages in Mizoram, Indian Army's Piped Natural Gas (PNG) clean-energy transition, Swachhata Hi Seva drives at Agartala Military Station, and ISRO's EOS-05 satellite for 24/7 border & glacial lake (GLOF) surveillance.
  4. **Sports, Adventure & Achievements (Pages 33–39):** Spear Corps' historic ascent of 22,601-ft Mt Khangchengyao in North Sikkim, Naib Subedar Neeru Dhanda's Asian Games 2026 Women's Trap Gold, grassroots youth sports gear drives in Manipur & Nagaland, and national school triathlon laurels at ARPS Mantripukhri.
  5. **Society, Youth & Empowerment (Pages 40–47):** Over 1,200 youth participating in the Churachandpur Agniveer Recruitment Rally, Royal Global University's 100% tuition waiver MoU (*Royal Shaurya*) for martyrs' wards in Shillong, Nagaland *Seema Darshan* student tour, Tripura women's literacy outreach, Tirap's motorcycle tribute to Ashok Chakra awardee Havildar Hangpan Dada, and 354 new Assam Rifles technical vacancies.
* **Built-In Audit Appendices (Pages 48–50):**
  * **Appendix I (Page 48):** Complete bibliographic registry of all **19 official portals and news organizations** with exact article counts per source.
  * **Appendix II (Pages 49–50):** Comprehensive **Editorial Selection Rationale Matrix** explaining the strategic and analytical reasoning behind every chosen dispatch.

---

## Technical Architecture & Design System

| Layer | Implementation Details |
| :--- | :--- |
| **Print Geometry** | Native CSS `@page { size: A4 portrait; margin: 0; }` with strict `210mm × 297mm` containers and `break-after: page` pagination locks. |
| **Editorial Typography** | **Cinzel** (Mastheads), **Playfair Display** (Headlines & Pull Quotes), **Source Serif 4** (2-Column Justified Body Copy with Drop-Caps), **Inter** (Tactical Tables), and **JetBrains Mono** (Running Folios & Metrics). |
| **Color Palette** | Command Olive (`#1f3324`), Deep Pine (`#142117`), Regimental Gold (`#c59b27`), Archival Parchment (`#fbfaf6`), and Tactical Crimson (`#8b1e1e`). |
| **Client-Side Pagination Engine** | Structured JavaScript dataset (`ARTICLES` & `APPENDIX_SOURCES`) that dynamically compiles all 50 A4 sheets into the DOM and populates an interactive Page Jumper (`Pages 01–50`). |
| **Screen vs. Print Isolation** | Floating navigation bar with page jump and 1-click PDF export on screen, automatically stripped during PDF generation via `@media print`. |

---

## Quick Start & Usage

### 1. View Locally in Browser
Clone the repository and open the HTML file directly in any modern browser (no build step or local server required):

```bash
git clone [https://github.com/](https://github.com/)<your-username>/sentinel-northeast-a4-emagazine.git
cd sentinel-northeast-a4-emagazine
# Open index.html (or securing-the-northeast-a4-magazine.html) in Chrome, Edge, or Brave
```

### 2. Export to a 50-Page ISO A4 PDF
1. Open the file in **Google Chrome**, **Microsoft Edge**, or **Brave**.
2. Click the gold **"Export / Print 50-Page A4 PDF"** button in the top-right toolbar (or press `Ctrl + P` / `Cmd + P`).
3. Apply the following print settings:
   * **Destination:** `Save as PDF`
   * **Paper Size:** `A4`
   * **Margins:** `None` (or `Default`)
   * **Options:** Enable **`Background graphics`** (Required to render the Olive & Gold cover, section dividers, and metric plates).

---

## 50-Page Folio Map

```text
├── Pages 01–05 : Front Cover, Editor's Note, Theater Order of Battle, Master TOC & 30-Day Timeline
├── Pages 06–15 : Section I   — Security & Strategic Affairs (Articles 01–07 + Technical Dossiers)
├── Pages 16–25 : Section II  — Regional News & Internal Stability (Articles 08–14 + Synthesis Spreads)
├── Pages 26–32 : Section III — Development, Infrastructure & Sustainability (Articles 15–18 + BRO/EOS Dossiers)
├── Pages 33–39 : Section IV  — Sports, Adventure & Achievements (Articles 19–22 + Expedition Logs)
├── Pages 40–47 : Section V   — Society, Youth & Empowerment (Articles 23–28 + Recruitment Matrix)
├── Page 48     : Appendix I  — Verified Source Registry & Article Count Matrix (19 Sources / 28 Articles)
└── Pages 49–50 : Appendix II — Article-by-Article Editorial Selection Reasoning Matrix & Colophon
```

---

## License & Attribution

All news dispatches, operational figures, and official press releases remain the intellectual property of their respective publishing organizations (PIB, The Indian Express, India Today NE, The Sentinel Assam, The Shillong Times, The Morung Express, DD India, etc.) as cited inline and audited in **Appendix I**. The HTML5/CSS3 A4 magazine layout engine and editorial synthesis are open-sourced under the MIT License.
