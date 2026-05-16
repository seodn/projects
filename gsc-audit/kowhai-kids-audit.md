# Kowhai Kids Club - GSC Performance Audit & Strategy

This audit follows the Search Behaviour Operating System blueprint, prioritizing commercial intent, traffic velocity, and index hygiene.

---

## 📊 Query Trajectory Table
*What is growing, stable, or decaying?*

| Trajectory | Query | Metrics (Imp / Pos / CTR) | Diagnosis & Recommended Action |
| :--- | :--- | :--- | :--- |
| 🟢 **Growing** | kowhai kids club | 227 / 1.0 / 79.7% | **Gaining Traction:** Brand dominance. Ensure the homepage has clear conversion pathways and CRO elements. |
| 🟡 **Stable** | after school care | 238 / 8.2 / 3.8% | **Page 1 Opportunity:** Sitting at the bottom of Page 1. Needs a strong CTR push (Title/Meta rewrite) and semantic depth expansion to move to top 3. |
| 🟡 **Stable** | carpe diem kids | 23 / 5.1 / 17.4% | **Page 1 Opportunity:** High CTR but low impressions. Monitor competitor brand cannibalization. |
| 🟡 **Stable** | oscar subsidy calculator | 19 / 8.3 / 5.3% | **High Commercial Intent:** Excellent opportunity to build a custom calculator or detailed guide to capture early-stage funnel traffic. |
| 🔴 **Decaying** | before and after school care | 79 / 11.9 / 6.3% | **Page 2+ Drop:** Dropping impressions, losing rank positions. Action: Intervene with title updates and add explicit "before and after" sections to service pages. |
| 🔴 **Decaying** | after school care auckland | 169 / 11.1 / 2.4% | **Page 2+ Drop:** High impression potential but stuck on Page 2. Requires localized semantic expansion (e.g., adding specific Auckland suburbs). |

---

## 📄 Page Trajectory Table
*Which pages are performing and which are bleeding?*

| Trajectory | Page URL | Metrics (Clicks / Imp / CTR / Pos) | Diagnosis & Recommended Action |
| :--- | :--- | :--- | :--- |
| 🟡 **Stable** | `/after-school-care/` | 107 / 6634 / 1.6% / 8.2 | **Stable / Leaking Clicks:** Massive impression pool but terrible CTR (1.6%). **Action:** Immediate Title/Meta rewrite. Add trust signals (e.g., "WINZ Approved"). |
| 🟡 **Stable** | `/holiday-programme/` | 80 / 1782 / 4.5% / 13.7 | **Stable / Page 2:** Good CTR for Page 2. **Action:** Needs internal link authority flow from the homepage and a semantic depth refresh to push to Page 1. |
| 🟢 **Growing** | `/locations/` | 8 / 565 / 1.4% / 5.0 | **Gaining Traction:** High visibility. **Action:** Double down. Create dedicated location sub-pages if not already present. |
| 🟡 **Stable** | `/oscar-subsidies/` | 5 / 2971 / 0.2% / 8.9 | **Stable / Leaking Clicks:** Massive impression pool (2.9k) but negligible CTR (0.2%). **Action:** Re-align search intent. Add a calculator format (see query above). |
| 🔴 **Decaying** | `/Flanshaw-Holiday-Programme.pdf` | 6 / 92 / 6.5% / 5.3 | **Index Hygiene Issue:** Bleeding traffic to a PDF asset. **Action:** Convert to an HTML page or apply `noindex` and redirect. |

---

## 🕵️‍♂️ Competitor Sitemap & Content Gap Engine (Target: Kelly Club)

Kelly Club is executing a aggressive "programmatic local SEO" strategy that Kowhai Kids can mirror.

*   **Programmatic Local SEO Hubs:** Kelly Club has built dedicated landing pages for every school and suburb they service (e.g., `/avondale`, `/bayswater`).
*   **Content Gap:** Kowhai Kids aggregates locations into a single page, losing traffic for "after school care [suburb]" queries.
*   **Authority Flow:** They use a dedicated `/oscar-childcare-subsidy` page linked from all local pages to funnel authority and drive informational intent.

---

## 🚀 Strategic Execution Plan

### 1. CTR / SERP Win System (Immediate)
*   **Target:** `/after-school-care/` and `/oscar-subsidies/`.
*   **Action:** Rewrite Meta Titles to include trust signals like "WINZ Approved" and "OSCAR Subsidies Available". Target 3% CTR benchmark.

### 2. Programmatic Location Expansion
*   **Target:** Current sites (Flanshaw, Jireh, Chaucer, Riverhills, Elim, St Mary’s, Waikowhai).
*   **Action:** Build 7 standalone landing pages to capture suburb-specific search intent.

### 3. Index Quality Engine (Index Hygiene)
*   **Target:** PDF Brochures.
*   **Action:** Implement `X-Robots-Tag: noindex` for PDFs and replace them with conversion-optimized HTML landing pages.

### 4. Semantic Intent Bridge
*   **Target:** "OSCAR Subsidy Calculator".
*   **Action:** Build an interactive calculator or table on `/oscar-subsidies/` to capture and convert early-funnel informational traffic.
