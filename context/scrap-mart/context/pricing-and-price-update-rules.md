# Scrap Mart Pricing And Price Update Rules

Last updated: 26 June 2026.

## Pricing Strategy

The new website should show current scrap metal rates by grade, with separate city price pages for:

1. Auckland
2. Christchurch

Use Onehunga and Hillsborough as branch proof inside the pages, not as the main URL structure.

The client wants exact current rates shown and updated weekly.

## Update Frequency

Fireflies notes say prices are affected by global commodity markets and are expected to update weekly, often around Tuesday.

Recommended website approach:

- Add a "last updated" date on every price table.
- Make pricing editable from the website backend.
- Keep prices as structured data, not hardcoded inside page copy.
- Add one central price-management area so staff can update metal grades without editing full pages.
- Show a clear disclaimer that final prices depend on grade, weight, cleanliness, and inspection.

## Client-Supplied Commodity List

Dharmesh supplied two price-list spreadsheet attachments on 24 June 2026. The parsed attachment output confirmed the accepted commodity categories and units, including:

- aluminium
- batteries and lead
- brass
- copper
- motors
- stainless steel
- steel
- wires
- zinc
- e-waste listed as POA

Use the supplied commodity list as the main source for what Scrap Mart buys. Exact public price values still need to be confirmed or manually checked before publishing.

## Draft Price Sources

The placeholder pricing in `../content/price-list-draft.md` uses:

- Endless Onehunga live pricing valid 17-23 June 2026 for Auckland placeholders.
- Metalcorp Christchurch public pricing updated 25 February 2026 for Christchurch placeholders.

These are not Scrap Mart prices. They are working placeholders only and should be superseded by the client's supplied weekly rates once confirmed.

## Publish Rules

Do not publish the draft prices until one of these happens:

1. Scrap Mart supplies their own weekly price list.
2. Scrap Mart approves the placeholder price list.
3. Sagar approves a pre-launch temporary price strategy.

Because the client has now supplied commodity files, use those files for accepted item names. Do not publish price values until the exact rates are approved for the live website.

## Customer-Facing Disclaimer

Recommended wording:

> Prices are indicative and subject to change without notice. Final payment is confirmed after inspection, weighing, and grading at the yard. Prices may vary by location, quantity, cleanliness, and market conditions.

## Backend Requirements

The website should support:

- price per kg
- price per tonne
- price per item
- location-specific price values
- grade notes
- "POA" or "Call for price"
- active/inactive status for each metal grade
- last updated date
- optional calculator later

## Suggested Price Page URLs

- `/scrap-metal-prices`
- `/scrap-metal-prices/auckland`
- `/scrap-metal-prices/christchurch`

Christchurch should be treated as a confirmed branch price page. Pricing can still be marked as tentative until the client approves the live rates.
