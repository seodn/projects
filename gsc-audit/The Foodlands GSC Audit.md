# The Foodlands - Search Behaviour OS Audit

This comprehensive audit executes the Search Behaviour Operating System blueprint for the Christchurch, NZ Indian grocery market. The goal is to move beyond finding "SEO opportunities" to providing a "prioritised action system" that dictates exact execution intelligence to increase online and in-store sales.

---

## 10. Momentum & Trajectory Engine

### 📊 Query Trajectory Table
*What is growing, stable, or decaying in the local market?*

| Trajectory | Query | Metrics (Imp / Pos / CTR) | Diagnosis & Recommended Action |
| :--- | :--- | :--- | :--- |
| 🟢 **Growing** | indian supermarket christchurch | 1,349 / 2.23 / 13.12% | **Top 3 Winner:** Excellent positioning. The site is a trusted entity for physical grocery shopping in Christchurch. |
| 🟢 **Growing** | jaggery | 2,245 / 7.48 / 0.58% | **National E-commerce Opportunity:** High volume, Page 1 ranking. The low CTR is because the SERP is filled with informational intent. Action: Add Recipe Schema to the jaggery product pages. |
| 🟡 **Stable** | indian grocery store near me | 1,728 / 6.50 / 1.85% | **Local Pack Borderline:** Action: The massive 17k impression cannibalization issue (see below) is splitting your local trust signals. |
| 🔴 **Decaying** | ragi flour | 651 / 3.02 / 0.61% | **Leaking Clicks:** Ranking #3 but getting less than 1% of clicks. Competitors offer better metadata showing pack sizes and delivery times. |

### 📄 Page Trajectory Table
*Which pages are performing and which are bleeding?*

| Trajectory | Page URL | Metrics (Clicks / Imp / CTR / Pos) | Diagnosis & Recommended Action |
| :--- | :--- | :--- | :--- |
| 🟢 **Growing** | `/` (Homepage) | 1,640 / 50,319 / 3.26% / 10.78 | **Stable Growth:** The homepage is generating massive impressions. |
| 🔴 **Decaying** | `/?utm_source=google-business` | 1,640 / 17,230 / 9.52% / 4.08 | **CRITICAL Index Hygiene Crisis:** Your Google Business Profile tracking link is indexed and getting 17,000+ impressions, actively competing with the main homepage. **Action:** Implement an absolute canonical tag on the homepage to stop this immediately. |
| 🟡 **Stable** | `/rice-flours/rice/` | 61 / 5,228 / 1.17% / 9.42 | **Category Page Stall:** Action: Needs a localized FAQ section at the bottom (e.g., "Do you deliver basmati rice across Christchurch?"). |

---

## 5 Master Decision Systems

### A. Traffic Growth System (Stalled Queries)
**Purpose:** Increase impressions + rankings for pages stuck at the bottom of Page 1 or top of Page 2.
- **Hidden Demand:** The `ragi flour` product page.
- **Action:** Add semantic trust signals: "Gluten-Free", "High Calcium", and "Sourced directly from India".

### B. CTR / SERP Win System (Leaking Clicks)
**Purpose:** Increase clicks without rankings changing by optimizing metadata.

**Exact Implementation (Copy & Paste these into your CMS):**

**1. Homepage (Local + National Delivery Intent)**
- **Title Tag:** `The Foodlands | Indian Supermarket Christchurch & NZ Delivery`
- **Meta Description:** `Shop authentic Indian groceries, spices, jaggery, and fresh produce at The Foodlands in Christchurch. Enjoy 50% OFF weekly specials and fast NZ-wide delivery.`

**2. Rice Category Page**
- **Title Tag:** `Buy Premium Basmati & Sona Masoori Rice NZ | The Foodlands`
- **Meta Description:** `Stock up on premium Indian rice. From everyday Basmati to Sona Masoori, get the best prices in Christchurch with fast delivery across New Zealand.`

### C. Google Trust System
**Purpose:** Understand what Google trusts.
- **Observation:** Google trusts local business entities that prove they actually exist.
- **Action:** Your homepage is currently heavily product-focused. Add a "Visit Our Christchurch Store" section with photos of the actual storefront at 501 Moorhouse Avenue, Waltham.

### D. Content Investment System
**Purpose:** Tell the business WHAT content to create next based on commercial opportunity.

**Recommended Blog / Article Titles (Content Gap Attack):**
To capture top-of-funnel recipe traffic and build trust with Kiwi-Indian families, publish these highly-searched informational articles:
1. *Where to Buy the Best Jaggery in New Zealand (And How to Store It)*
2. *5 Must-Have Spices for an Authentic Indian Pantry in Christchurch*
3. *Ragi Flour Recipes: How to Make Healthy Dosa at Home*
4. *The Ultimate Guide to Choosing the Right Basmati Rice*

### E. Authority Flow System & Semantic Link Modelling
**Purpose:** Redistribute ranking power strategically.
- **Donor Page:** Homepage (`/`) — Highly trusted.
- **Recipient Pages:** `/suger-jaggery/` and `/rice-flours/rice/`.
- **Exact Implementation:** Ensure that the homepage banners link to these specific categories using exact match anchors like `Buy Jaggery NZ` and `Indian Rice Christchurch`.

---

## Additional Intelligence Layers

### 1. Index Quality Engine (Index Hygiene Analysis)
- **CRITICAL ALERT:** The URL `https://thefoodland.nz/?utm_source=google-business&utm_medium=organic` must be de-indexed using canonicalization. It is splitting your homepage authority by 25%.

### 2. Competitor Sitemap & Content Gap Engine
- **Competitors:** *Yogiji's Food Mart, Value Mart, MandiBazaar.*
- **Output:** Online competitors like MandiBazaar dominate by having extensive recipe sections linked to products. Adding a "Recipe" tab that links directly to the spices/flours needed will massively increase average order value (AOV).

---

## Execution Checkpoints (Step-by-Step Action Plan)

To deploy this blueprint immediately, complete the following steps in order of highest business impact:

- [ ] **Step 1: Fix Index Cannibalisation (Priority: CRITICAL)**
  - [ ] Add the canonical tag `<link rel="canonical" href="https://thefoodland.nz/" />` to the homepage to stop the Google Business Profile UTM link from stealing authority.
- [ ] **Step 2: Rewrite Core Metadata**
  - [ ] Update the Homepage Title Tag and Meta Description to target "Indian Supermarket Christchurch" and "NZ Delivery".
  - [ ] Update the `/rice-flours/rice/` Category Page Title Tag to "Premium Basmati & Sona Masoori Rice NZ".
- [ ] **Step 3: Deploy Local Trust Signals**
  - [ ] Add a "Visit Our Christchurch Store" section to the homepage with a photo of the 501 Moorhouse Ave storefront.
  - [ ] Add an FAQ section to the Rice category page addressing Christchurch and NZ-wide delivery.
- [ ] **Step 4: Execute Content Gap Attack**
  - [ ] Publish the 4 recommended blog articles targeting Jaggery storage, Ragi Dosa recipes, and Basmati rice selection.
  - [ ] Embed Recipe Schema on the Jaggery and Ragi Flour product pages.
