# AAA Wreckers: Full GSC Performance Audit & Competitor Strategy

This document combines a data-driven Google Search Console (GSC) audit with a deep-dive competitor analysis for AAA Wreckers, following the **Search Behaviour Operating System** framework.

---

## 1. Momentum & Trajectory Engine (Search Console Clarity)

We have analyzed the current queries and pages to uncover the velocity of the site. Here is what is gaining traction, flatlining, or decaying.

### 📊 Query Trajectory Table
| Trajectory | Query | Metrics (Imp/Pos/Clicks) | Diagnosis & Recommended Action |
| :--- | :--- | :--- | :--- |
| 🟢 **Growing** | car wreckers auckland | 1599 / 9.88 / 13 | **Gaining Traction:** High-impression growth, improving positions (bottom of page 1). *Action: Add internal links, expand content depth.* |
| 🟢 **Growing** | aa wreckers | 485 / 4.59 / 6 | **Gaining Traction:** Brand variation showing strong position. *Action: Ensure brand SERP dominance.* |
| 🟢 **Growing** | aaa wreckers | 198 / 9.14 / 28 | **Gaining Traction:** Primary brand term, but ranking is unexpectedly low for a brand name. *Action: Homepage title and brand entity optimization.* |
| 🟡 **Stable** | aaa | 1265 / 6.8 / 1 | **Stable:** Consistent volume, but likely mixed intent (e.g., American Automobile Association or AA NZ). *Action: Disambiguate brand entity.* |
| 🔴 **Decaying** | car wreckers | 864 / 12.41 / 8 | **Slowing/Decaying:** Dropping impressions, losing rank positions (page 2). *Action: Intervene with title updates and semantic depth.* |
| 🔴 **Decaying** | auto wreckers auckland | 599 / 12.62 / 1 | **Slowing/Decaying:** Dropping impressions, losing rank positions. *Action: Intervene with title updates and semantic depth.* |
| 🔴 **Decaying** | car wreckers west auckland | 454 / 10.26 / 2 | **Slowing/Decaying:** Dropping impressions, losing rank positions. *Action: Create a dedicated "West Auckland" location page.* |
| 🔴 **Decaying** | auckland car wreckers | 207 / 11.01 / 3 | **Slowing/Decaying:** Dropping impressions, losing rank positions. *Action: Intervene with title updates and semantic depth.* |
| 🔴 **Decaying** | best car wreckers auckland | 205 / 10.57 / 1 | **Slowing/Decaying:** High commercial intent but low rank. *Action: Add trust signals, reviews, and a "Why Choose Us" section.* |


### 📄 Page Trajectory Table
| Trajectory | Page URL | Metrics (Clicks/Imp/Pos) | Diagnosis & Recommended Action |
| :--- | :--- | :--- | :--- |
| 🟢 **Growing** | `/` (Homepage) | 153 / 23493 / 16.01 | **Gaining Traction:** Pulling almost all traffic and keyword footprint. *Action: Double down, push to Page 1 for core terms via internal linking and content depth.* |
| 🟡 **Stable** | `/contact-us/` | 9 / 909 / 11.13 | **Stable:** Steady conversions. *Action: Maintain dominance.* |
| 🔴 **Decaying** | `/services/car-removal/` | 2 / 844 / 26.51 | **Slowing/Decaying:** Bleeding traffic, loss of semantic relevance (deep page 3). *Action: Refresh content, add pricing/process steps.* |
| 🔴 **Decaying** | `/services/truck-wreckers/` | 1 / 498 / 16.54 | **Slowing/Decaying:** Bleeding traffic, loss of semantic relevance. *Action: Refresh content, check for technical issues.* |

---

## 2. The 5 Master Decision Systems

Based on the trajectory data and business value modeling, here is the exact execution intelligence required to drive commercial growth.

### A. Traffic Growth System
**Objective:** Push high-value Page 2 queries to Page 1.
* **Quick Wins:** The query `"car wreckers auckland"` sits at position 9.88 with 1,599 impressions. Moving this to top 3 will yield immediate lead growth.
* **Hidden Demand:** Queries like `"car wreckers west auckland"` (Pos 10.26) and `"auto dismantlers auckland"` (Pos 11.97) represent highly commercial localized intent that is currently under-served. 
* **Execution:**
  1. Inject exact match heading: `<h2>Car Wreckers Auckland - Top Cash Paid</h2>` onto the homepage.
  2. Create a dedicated "West Auckland" location page if they service that area heavily.

### B. CTR / SERP Win System
**Objective:** Fix leaking clicks on branded and primary terms.
* **Brand Confusion:** The brand query `"aaa wreckers"` ranks at 9.14. This is highly unusual and suggests Google is confusing the brand with "AA Auto Parts" or the motoring association "AA". 
* **Overall CTR:** The homepage CTR is a poor 0.65% because it ranks on page 2 for high-volume terms.
* **Execution:**
  1. **Title Rewrite for Homepage:** Update title to explicitly separate the brand and target the core location: `AAA Wreckers | #1 Car Wreckers Auckland | Cash for Cars`.
  2. Implement an `Organization` LocalBusiness Schema markup on the homepage to solidify the brand entity with Google.

### C. Google Trust System
**Objective:** Leverage what Google already trusts.
* **Trust Profile:** Google trusts the site for "wreckers" variations but is keeping it restricted to the 10-15 position range.
* **Execution:** To break through this ceiling, the site needs deeper semantic breadth. Expand the homepage content to cover the *entire* dismantling lifecycle: Quote → Free Towing → Auto Dismantling → Parts Recycling.

### D. Content Investment System
**Objective:** Tell the business WHAT content to create next.
* **The Gap:** Currently, the site only has basic `/services/car-removal/` and `/services/truck-wreckers/` pages that rank poorly (Pos 16-26). They lack the content formatting Google rewards.
* **Execution (Build Next):**
  1. **Pricing / Payout Guide:** "How much cash for your car in Auckland?" with a pricing table (e.g., Sedans: $200-$1000, SUVs: $500-$2000). Winning pages in this niche use pricing tables.
  2. **Step-by-Step Flow:** Add a "How It Works" 3-step sequence (1. Get Quote, 2. Free Towing, 3. Get Paid) on the car removal page.

### E. Authority Flow System
**Objective:** Redistribute ranking power strategically.
* **The Issue:** The homepage is an authority black hole (getting all impressions and clicks) while service pages are starved.
* **Execution:** The homepage must become an active **Authority Hub**.
  1. Add a dedicated "Our Services" grid on the homepage.
  2. Link to `/services/car-removal/` with the exact anchor text: `"Auckland Car Removal"`.
  3. Link to `/services/truck-wreckers/` with the exact anchor text: `"Truck Wreckers Auckland"`.

---

## 3. Site Quality & Index Hygiene
* **Zombie Pages:** `/services/` (0 clicks, 39 imp) and `/team-member/` (0 clicks, 14 imp). 
  * *Action:* If `/services/` is just an empty archive page, `noindex` or redirect it to the homepage. Delete or merge `/team-member/` if it serves no commercial purpose.
* **Cannibalization Risk:** The homepage and `/services/car-removal/` are likely competing for the same intent. Ensure the homepage focuses on the broad brand/directory intent ("Car Wreckers Auckland"), while the service page targets the action intent ("Cash for car removal", "Free auto towing").

---

## 4. Competitor Research & Query Qualification

### Target Queries:
1. `car wreckers auckland`
2. `cash for cars auckland`

### 1. Query Qualification & Commercial Value
Both queries are the lifeblood of the auto-dismantling industry.
* **`car wreckers auckland`**: Highly commercial intent. Users are actively looking to dispose of a vehicle. AAA Wreckers already has momentum here (Position 9.88, 1,599 impressions), making this a primary target to push into the top 3.
* **`cash for cars auckland`**: Supreme commercial value. The intent here is purely financial—the user wants the highest payout and fastest removal. AAA Wreckers currently lacks a dedicated page targeting this exact semantic intent.

### 2. SERP Comparison (Against Top Winners)
Based on current SERP data for the Auckland market, the dominant competitors (e.g., *NZ Wreckers*, *Mega Car Collection*, *Cash For Car*) exhibit the following winning patterns:

| Element | Top Competitors (Winners) | AAA Wreckers (Current State) |
| :--- | :--- | :--- |
| **Page Structure** | Dedicated URL for each intent (e.g., `/cash-for-cars-auckland/`, `/car-removal-auckland/`) | Relies heavily on the homepage and poorly ranking `/services/car-removal/` |
| **Trust Signals** | Instant online quote forms, "up to $12,000" badges, eco-friendly recycling badges. | Weak on immediate trust signals and specific payout limits. |
| **Content Formatting** | 3-step "How it works" flows (Quote → Towing → Cash). Detailed lists of accepted brands. | Basic text paragraphs lacking structured semantic layouts. |
| **Title Tags** | Direct intent matching (e.g., `Cash for Cars Auckland | Up to $12,000 | Free Removal`) | Generic targeting or brand confusion in titles. |

### 3. Actionable On-Page Suggestions
Based on competitor gaps and semantic intent, here are the exact on-page changes required for AAA Wreckers:

#### For `car wreckers auckland` (Optimising the Homepage):
* **H1 Update:** `Auckland's #1 Car Wreckers – Top Cash & Free Removal`
* **Semantic Injection:** Add a section specifically listing the condition of cars accepted (e.g., *Scrap, Damaged, De-registered, MOT Failures, Wrecked, Rusted*).
* **Location Expansion:** Mention specific sub-regions on the homepage (West Auckland, South Auckland, North Shore) to capture long-tail variations like `"car wreckers west auckland"`.

#### For `cash for cars auckland` (New Page Required):
* **Create a Dedicated URL:** `https://www.aaawreckers.co.nz/cash-for-cars-auckland/`
* **Formatting Upgrade:** Implement a **Pricing/Payout Table** (e.g., Sedans: $200-$1,000 | SUVs & 4x4s: $500-$5,000). Winning pages use exact numbers.
* **Conversion Element:** Place a sticky or highly visible "Get Instant Cash Quote" form at the top of the page.
* **Internal Linking:** Point an exact match anchor `Cash for Cars Auckland` from the homepage to this new URL to instantly transfer authority.

### 4. Broader Discovery (Competitor Sitemap & Content Gap Engine)
We triggered the sitemap extraction engine against a top competitor (*nzwreckers.com*) to reveal their broader traffic strategy. 

**Competitor Sitemap Findings:**
* `https://www.nzwreckers.com/car-removal-auckland/`
* `https://www.nzwreckers.com/cash-for-cars-auckland/`
* `https://www.nzwreckers.com/used-car-parts-auckland/`
* `https://www.nzwreckers.com/service-locations/`

**The Content Gap:**
The competitor separates "Car Removal" (service intent), "Cash for Cars" (financial intent), and "Used Car Parts" (parts buyer intent) into distinct, highly optimized silos. They also have a dedicated `/service-locations/` cluster, likely spinning off pages for West Auckland, South Auckland, etc.

**Strategic Action for AAA Wreckers:**
Do not bundle all services onto a single page or rely just on the homepage. Build out the "Big Three" silo:
1. `.../cash-for-cars/` (Targeting sellers)
2. `.../car-removal/` (Targeting convenience/disposal)
3. `.../used-car-parts/` (Targeting buyers) 
*If parts sales are part of the business model, this is a massive missed opportunity.*
