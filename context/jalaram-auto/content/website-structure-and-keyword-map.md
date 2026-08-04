# Jalaram Auto Website Structure And Keyword Map

Status: Website structure working plan. Confirm services, pricing, assets, and compliance wording before publication.

Last updated: 4 August 2026.

## Strategic Summary

Jalaram Auto needs a local SEO website that makes five things obvious:

1. The workshop is a real local Glen Eden mechanic at 287C West Coast Road.
2. It handles everyday WOF, servicing, repairs, tyres, electrical, and air conditioning work.
3. Hybrid battery repair and reconditioning are the standout differentiators.
4. Trust is built through MTA approval, genuine reviews, Chirag's story, and photo-supported repair explanations.
5. The conversion path is simple: call, request a quote, or book a WOF/service.

The current structure should avoid a flat "all services" list. It should group pages around the way drivers search: urgent local mechanic needs, WOF, car service, hybrid battery issues, tyre punctures, and specific mechanical faults.

## Recommended Primary Navigation

- Services
- Hybrid Batteries
- WOF
- Tyres
- About
- Reviews
- Contact

Recommended header CTA:

- Call now
- Book a service

Optional top bar:

- 287C West Coast Road, Glen Eden
- 022 122 1822
- MTA approved

## Page Hierarchy

```text
Homepage (/)
├── Services (/services)
│   ├── WOF (/services/wof)
│   ├── Car Service (/services/car-service)
│   ├── Mechanical Repairs (/services/mechanical-repairs)
│   │   ├── Brake Repairs (/services/brake-repairs)
│   │   ├── Suspension Repairs (/services/suspension-repairs)
│   │   ├── Clutch And Transmission (/services/clutch-and-transmission)
│   │   └── Cam Belt Replacement (/services/cam-belt-replacement)
│   ├── Auto Electrical (/services/auto-electrical)
│   └── Air Conditioning (/services/air-conditioning)
├── Hybrid Batteries (/services/hybrid-battery-repair)
│   ├── Hybrid Battery Reconditioning (/services/hybrid-battery-reconditioning)
│   └── Hybrid Car Service (/services/hybrid-car-service)
├── Tyres (/services/tyres)
│   └── Puncture Repair (/services/puncture-repair)
├── Locations (/locations)
│   ├── Mechanic Glen Eden (/mechanic-glen-eden)
│   └── Mechanic West Auckland (/mechanic-west-auckland)
├── Pricing (/pricing)
├── About (/about)
├── Reviews (/reviews)
├── Gallery (/gallery)
├── FAQs (/faqs)
└── Contact (/contact)
```

## Visual Sitemap

```mermaid
graph TD
    HOME["Homepage /"] --> SERVICES["Services /services"]
    HOME --> HYBRID["Hybrid Batteries /services/hybrid-battery-repair"]
    HOME --> TYRES["Tyres /services/tyres"]
    HOME --> LOCATIONS["Locations /locations"]
    HOME --> ABOUT["About /about"]
    HOME --> REVIEWS["Reviews /reviews"]
    HOME --> CONTACT["Contact /contact"]

    SERVICES --> WOF["WOF /services/wof"]
    SERVICES --> CARSERVICE["Car Service /services/car-service"]
    SERVICES --> MECH["Mechanical Repairs /services/mechanical-repairs"]
    SERVICES --> ELECTRICAL["Auto Electrical /services/auto-electrical"]
    SERVICES --> AC["Air Conditioning /services/air-conditioning"]

    MECH --> BRAKES["Brake Repairs"]
    MECH --> SUSPENSION["Suspension Repairs"]
    MECH --> CLUTCH["Clutch And Transmission"]
    MECH --> CAMBELT["Cam Belt Replacement"]

    HYBRID --> RECON["Hybrid Battery Reconditioning"]
    HYBRID --> HYBRIDSERVICE["Hybrid Car Service"]

    TYRES --> PUNCTURE["Puncture Repair"]

    LOCATIONS --> GLENEDEN["Mechanic Glen Eden"]
    LOCATIONS --> WESTAKL["Mechanic West Auckland"]
```

## URL Map

| Page | URL | Parent | Nav Location | Priority |
| --- | --- | --- | --- | --- |
| Homepage | `/` | None | Header logo | High |
| Services Hub | `/services` | Homepage | Header | High |
| WOF | `/services/wof` | Services | Header / Services dropdown | High |
| Car Service | `/services/car-service` | Services | Header / Services dropdown | High |
| Hybrid Battery Repair | `/services/hybrid-battery-repair` | Homepage | Header | High |
| Hybrid Battery Reconditioning | `/services/hybrid-battery-reconditioning` | Hybrid Battery Repair | Hybrid page links | High |
| Hybrid Car Service | `/services/hybrid-car-service` | Hybrid Battery Repair | Hybrid page links | Medium |
| Mechanical Repairs | `/services/mechanical-repairs` | Services | Services dropdown | High |
| Brake Repairs | `/services/brake-repairs` | Mechanical Repairs | Mechanical page links | Medium |
| Suspension Repairs | `/services/suspension-repairs` | Mechanical Repairs | Mechanical page links | Medium |
| Clutch And Transmission | `/services/clutch-and-transmission` | Mechanical Repairs | Mechanical page links | Medium |
| Cam Belt Replacement | `/services/cam-belt-replacement` | Mechanical Repairs | Mechanical page links | Medium |
| Auto Electrical | `/services/auto-electrical` | Services | Services dropdown | Medium |
| Air Conditioning | `/services/air-conditioning` | Services | Services dropdown | Medium |
| Tyres | `/services/tyres` | Homepage | Header | High |
| Puncture Repair | `/services/puncture-repair` | Tyres | Tyres page links | High |
| Locations | `/locations` | Homepage | Footer | Medium |
| Mechanic Glen Eden | `/mechanic-glen-eden` | Locations | Header/footer/contextual | High |
| Mechanic West Auckland | `/mechanic-west-auckland` | Locations | Footer/contextual | High |
| Pricing | `/pricing` | Homepage | Header/footer | Medium |
| About | `/about` | Homepage | Header | High |
| Reviews | `/reviews` | Homepage | Header/footer | High |
| Gallery | `/gallery` | Homepage | Footer | Medium |
| FAQs | `/faqs` | Homepage | Footer | Medium |
| Contact | `/contact` | Homepage | Header CTA/footer | High |

## Page Briefs

### Homepage

Recommended H1:

- Mechanic in Glen Eden for WOF, Servicing and Hybrid Battery Repairs

Primary keywords:

- mechanic Glen Eden
- Jalaram Auto
- WOF Glen Eden
- car service Glen Eden

Sections:

- Hero with Glen Eden location, MTA trust, phone CTA, and booking CTA.
- Service cards: WOF, car service, hybrid battery repair, mechanical repairs, tyres, auto electrical, air conditioning.
- Hybrid battery proof section explaining repair, reconditioning, rebuild, and replacement options in plain language.
- Why choose Jalaram Auto: genuine reviews, MTA approval, before/after photos, owner-led service, quality oil/parts.
- Starting-price teaser linking to `/pricing`.
- Glen Eden and West Auckland service-area section.
- Owner story preview with link to About.
- Reviews/testimonials.
- FAQ.

CTA:

- Call Jalaram Auto
- Book a WOF or service
- Ask about hybrid battery repair

### Services Hub

Target page: `/services`

Primary keyword:

- car repairs Glen Eden

Sections:

- Service overview grouped by customer need.
- WOF and servicing.
- Hybrid repairs.
- Mechanical repairs.
- Tyres and puncture repair.
- Auto electrical and air conditioning.
- "Not sure what your car needs?" quote CTA.

### WOF

Target page: `/services/wof`

Primary keyword:

- WOF Glen Eden

Sections:

- What a WOF inspection covers.
- What happens if the car passes.
- What happens if the car fails.
- WOF repairs and recheck pathway.
- MTA/authorisation trust wording after confirmation.
- Glen Eden location and booking CTA.

### Car Service

Target page: `/services/car-service`

Primary keyword:

- car service Glen Eden

Sections:

- Basic service.
- Full service.
- Hybrid car servicing.
- Sedan/hatchback starting price after approval.
- SUV starting price after approval.
- Quality oil and parts.
- Service records and reminders.
- CTA to request a quote by make/model.

### Hybrid Battery Repair

Target page: `/services/hybrid-battery-repair`

Primary keyword:

- hybrid battery repair Auckland

Secondary keywords:

- hybrid battery repair West Auckland
- hybrid battery repair near me
- hybrid battery replacement Auckland
- hybrid battery service near me

Sections:

- Symptoms of hybrid battery problems.
- Diagnosis process.
- Repair versus reconditioning versus replacement.
- Common hybrid vehicles, if confirmed.
- Why Jalaram Auto for hybrid battery work.
- Quote CTA.
- Link to `/services/hybrid-battery-reconditioning` and `/services/hybrid-car-service`.

### Hybrid Battery Reconditioning

Target page: `/services/hybrid-battery-reconditioning`

Primary keyword:

- hybrid battery reconditioning

Sections:

- What reconditioning means in simple terms.
- When it can be suitable.
- When replacement may be better.
- Safety and testing.
- Cost range or starting-price guidance after approval.
- CTA for diagnosis.

### Mechanical Repairs

Target page: `/services/mechanical-repairs`

Primary keyword:

- mechanical repairs Glen Eden

Sections:

- Brakes and rotors.
- Suspension.
- Clutch.
- Transmission.
- Cam belt.
- Engine-related work.
- Photo-supported diagnosis.
- Quote-before-repair trust message.

### Tyres

Target page: `/services/tyres`

Primary keyword:

- tyres Glen Eden

Sections:

- New tyres.
- Tyre checks.
- Puncture repair.
- When a tyre cannot be repaired.
- Link to `/services/puncture-repair`.

### Puncture Repair

Target page: `/services/puncture-repair`

Primary keyword:

- puncture repair Glen Eden

Sections:

- Repairable tread-area punctures.
- Sidewall damage is not repairable.
- Safety check.
- Quote/visit CTA.
- Add clear photo or diagram of repairable tyre area.

### Mechanic Glen Eden

Target page: `/mechanic-glen-eden`

Primary keyword:

- mechanic Glen Eden

Sections:

- Local mechanic positioning.
- WOF, car service, hybrid battery repair, tyres, repairs.
- Address and nearby landmarks.
- Reviews and MTA proof.
- Links to service pages.
- Contact CTA.

### Mechanic West Auckland

Target page: `/mechanic-west-auckland`

Primary keyword:

- mechanic West Auckland

Sections:

- West Auckland service-area overview.
- Glen Eden workshop as the physical location.
- Henderson, Kelston, New Lynn, Avondale, Titirangi, Glendene, Green Bay, Sunnyvale, and nearby suburbs.
- Core services and hybrid differentiator.
- CTA.

## Navigation Spec

Header nav:

- Services
- Hybrid Batteries
- WOF
- Tyres
- About
- Reviews
- Contact

Header CTA:

- Call now

Services dropdown:

- WOF
- Car Service
- Mechanical Repairs
- Auto Electrical
- Air Conditioning
- Tyres
- Puncture Repair

Hybrid dropdown or featured nav:

- Hybrid Battery Repair
- Hybrid Battery Reconditioning
- Hybrid Car Service

Footer columns:

- Services: WOF, Car Service, Hybrid Battery Repair, Mechanical Repairs, Auto Electrical, Air Conditioning, Tyres, Puncture Repair.
- Locations: Mechanic Glen Eden, Mechanic West Auckland, Henderson, New Lynn, Kelston, Titirangi.
- Trust: About, Reviews, Gallery, MTA Approved.
- Contact: Phone, Address, Hours, Booking/Quote form.

Breadcrumbs:

- Home > Services > WOF
- Home > Services > Hybrid Battery Repair
- Home > Locations > Mechanic Glen Eden

## Internal Linking Plan

Hub pages:

- `/services` should link to every core service page.
- `/services/hybrid-battery-repair` should link to hybrid reconditioning, hybrid car service, pricing, reviews, and contact.
- `/services/mechanical-repairs` should link to brakes, suspension, clutch/transmission, cam belt, WOF, and car service.
- `/services/tyres` should link to puncture repair, WOF, and contact.
- `/mechanic-glen-eden` should link to WOF, car service, hybrid battery repair, mechanical repairs, tyres, reviews, and contact.

Cross-section links:

- WOF page links to mechanical repairs and tyres for failed inspection fixes.
- Car service page links to hybrid car service and mechanical repairs.
- Hybrid battery pages link to reviews and gallery once assets exist.
- About page links to MTA trust, reviews, and hybrid services.
- Pricing page links to WOF, car service, hybrid battery repair, puncture repair, and quote form.

No orphan pages:

- Every page in the URL map must be linked from either the header, footer, parent service page, location page, or related-service section.

## Recommended Launch Phasing

### Phase 1: Core Local SEO Site

- Homepage
- Services hub
- WOF
- Car Service
- Hybrid Battery Repair
- Mechanical Repairs
- Tyres
- Puncture Repair
- Mechanic Glen Eden
- About
- Reviews
- Contact
- FAQs

### Phase 2: Service Expansion

- Hybrid Battery Reconditioning
- Hybrid Car Service
- Auto Electrical
- Air Conditioning
- Brake Repairs
- Suspension Repairs
- Clutch And Transmission
- Cam Belt Replacement
- Mechanic West Auckland
- Pricing
- Gallery

### Phase 3: Content And Suburb Expansion

- Hybrid battery educational articles.
- WOF and servicing guides.
- Henderson, New Lynn, Kelston, and Titirangi suburb pages only if data supports them.
- Competitor comparison pages only after strategy approval.

## Schema Recommendations

- LocalBusiness / AutoRepair on homepage and location pages.
- AutomotiveBusiness where supported by implementation stack.
- FAQPage on service FAQ sections.
- BreadcrumbList on all pages below homepage.
- Review snippets only if compliant with Google review and structured-data policies.

## Do Not Include At Launch

- Wheel alignment.
- Major panel beating.
- Thin suburb doorway pages.
- Unapproved fixed prices.
- Unverified "only provider in Glen Eden" claims.
- Unapproved insurance or warranty guarantees.
