# DAMB GOOD LAH — Cost Barrier Map — 2026-09-07

## Purpose

Identify the cost barriers most likely to determine whether the current $11.95-$14.95 menu architecture works, rank them by dollars-per-meal impact, and define the operating thresholds that matter more than small ingredient savings.

This document complements `docs/HALAL_PROTEIN_PRICING_2026-09-07.md`.

## Executive conclusion

**Halal protein cost is important, but it is not currently the largest economic risk.**

The dominant cost barriers are:

1. **Paid labor + kitchen-hour productivity**
2. **Delivery density / delivery cost per destination**
3. **Marketplace commissions and payment leakage**
4. **Packaging creep**
5. **Waste / remake / spoilage**
6. **Shrimp, lap cheong, eggs, frying oil and other volatile/high-cost SKUs**
7. **Permit, certification, insurance and startup compliance costs**
8. **Storage, refrigeration and hidden commissary fees**
9. **Equipment failures / weak wok capacity / rework**
10. **Customer acquisition cost and failed first-order economics**

The project should optimize in that order unless measured data show otherwise.

---

# 1. Labor + kitchen utilization — largest controllable barrier

## Current verified inputs

- San Jose minimum wage effective January 1, 2026: **$18.45/hour**.
- The Commissary 20-hour tier: **$710/month = $35.50 reserved kitchen hour** before hidden/ancillary costs.
- A two-person production crew at minimum wage therefore costs **$36.90/hour in direct wages** before payroll taxes, workers' compensation, paid sick leave, training, breaks, overtime or management time.

### Combined direct wage + Snell kitchen cost

Before payroll burden:

| Economic main-equivalents / paid kitchen hour | 2-worker direct wages / meal | Snell kitchen / meal | Combined before payroll burden |
|---:|---:|---:|---:|
| 10/hour | $3.69 | $3.55 | **$7.24** |
| 18/hour | $2.05 | $1.97 | **$4.02** |
| 24/hour | $1.54 | $1.48 | **$3.02** |
| 30/hour | $1.23 | $1.18 | **$2.41** |

**Interpretation:** moving from 10 to 24 main-equivalents/hour saves about **$4.22 per meal** before any ingredient negotiation.

This is why the canonical productivity targets remain:

- Consumer: **>=18 main-equivalents / total paid kitchen hour**
- Corporate constrained-menu: **>=24/hour**

### Additional labor costs not included above

Budget separately for:

- employer payroll taxes
- workers' compensation
- paid sick leave / statutory obligations
- onboarding and training
- overtime premiums
- manager/admin time
- cleanup after production
- receiving and inventory time
- food-safety logging

**Rule:** measure total paid person-hours, not just minutes spent actively cooking.

### Primary mitigation

- constrained office menus
- batch rice / curry / braise production
- advance-prep garnishes
- one shared chicken prep
- staggered prep/rush/cleanup labor
- mise-en-place designed around the six launch mains
- no menu expansion until the six-core system hits target throughput

---

# 2. Delivery — catastrophic for one meal, cheap for one office

Current public direct-delivery benchmarks:

- Uber Direct advertises pricing as low as **$6.99/delivery** depending on distance, region and product.
- DoorDash Drive API currently lists **$9.75 base for deliveries within 5 miles**, then distance increments.

### Delivery cost density

| Delivery fee | 1 meal | 10 meals | 20 meals | 30 meals | 50 meals |
|---:|---:|---:|---:|---:|---:|
| $6.99 | $6.99 | $0.70 | $0.35 | $0.23 | $0.14 |
| $9.75 | $9.75 | $0.98 | $0.49 | $0.33 | $0.20 |
| $12.00 | $12.00 | $1.20 | $0.60 | $0.40 | $0.24 |

**Conclusion:** direct courier delivery is structurally attractive for 20-50 meal office drops and structurally unattractive for subsidized single-meal delivery.

### Rule

- Do not promise free delivery on individual $11.95 meals.
- Corporate drop preference remains **20+ meals per destination**.
- Charge, pass through, threshold, or subsidize delivery only when contribution supports it.
- Cluster routes whenever possible.

---

# 3. Marketplace commission + payment leakage

## Marketplace

Current Uber Eats U.S. merchant terms list restaurant marketplace tiers around:

- Lite: **20%**
- Plus: **25%**
- Premium: **30%**

At a $12.75 average realized meal price:

- 20% = **$2.55/meal**
- 25% = **$3.19/meal**
- 30% = **$3.83/meal**

This alone can erase most contribution margin.

**Rule:** marketplace is discovery / overflow. It cannot be the economic foundation at the current value prices.

## Direct-card processing

Current Square Free restaurant/online benchmarks:

- in-person card: **2.6% + $0.15**
- online: **3.3% + $0.30**
- ACH via invoice: **1%**, $1 minimum

At $12.75:

- one individual online transaction ≈ **$0.72**
- one individual in-person transaction ≈ **$0.48**

For one consolidated 20-meal corporate order at $12.75/meal = $255:

- Square online card ≈ **$8.72/order = $0.44/meal**
- Square ACH ≈ **$2.55/order = $0.13/meal**

Corporate ACH therefore saves roughly **$0.31/meal** versus an online card on a 20-meal order, while consolidated payment already improves economics versus 20 individual transactions.

### Rule

- consumer direct: accept normal card processing
- recurring corporate: encourage ACH/invoice where operationally appropriate
- never accept 20-30% marketplace leakage as a default cost of sale

---

# 4. Packaging creep

Current project targets:

- consumer: **~$1.15/main**
- corporate: **~$0.65/meal**

Current public foodservice pricing shows that a basic disposable entree container can be substantially below those totals:

- 36 oz 3-compartment microwavable container + lid: about **$0.33-$0.37 each** at current listed case pricing
- 3-compartment foil tray + lid: about **$0.32-$0.36 each** at current listed case pricing
- compostable fiber bowls alone: roughly **$0.16-$0.25 each** before lid / accessories

The problem is not the base container. The problem is stacking:

- lid
- sauce cup + lid
- bag
- tamper label
- utensils
- napkin
- condiment packet
- branding sticker
- drink carrier
- outer catering carrier

A $0.50 packaging overrun costs **$500 per 1,000 meals**.

### Rule

Every package component must earn its place through:

- leak prevention
- texture protection
- heat retention
- food safety
- labeling/allergen need
- handling efficiency

Do not pay for unnecessary presentation layers during launch.

---

# 5. Waste, remakes and spoilage

Canonical stabilization target: **~5% food waste or lower**.

Waste must include:

- prep trim above expected yield
- overproduction
- expired perishables
- burnt/rejected CKT
- broken eggs
- overcooked noodles
- curry/braise left after service
- remake portions
- delivery failures that require replacement

A small food-cost percentage does not mean small economic impact if the waste also consumes labor, kitchen time and packaging.

### Rule

Track waste by SKU and cause, not only total dollars.

Use three buckets:

1. unavoidable yield loss
2. forecast / overproduction loss
3. execution / quality failure

Only #1 belongs in normal recipe yield. #2 and #3 are operational defects.

---

# 6. High-volatility / high-risk food SKUs

## A. Shrimp

A current U.S. wholesale reference for raw peeled/deveined shrimp is around **$6.20-$6.50/lb** for a 10-lb case benchmark, though Bay Area quotes must replace this reference.

At a 75 g CKT shrimp portion (~0.165 lb), $6.20/lb is roughly **$1.02 shrimp cost before yield/drain loss**.

Shrimp therefore matters, but it is still smaller than a poorly utilized kitchen hour.

**Action:** quote 21/25, 26/30 and 31/40 P&D tail-off formats and blind-test the smallest count that preserves CKT quality.

## B. Chicken lap cheong

This remains the single most strategically fragile ingredient because it combines:

- HALAL-certification requirement
- U.S. import/distribution uncertainty
- specialty pricing
- authenticity requirement
- CKT dependence

Cost target remains provisional until a U.S. quote is obtained.

**Redundancy:** Bestt Impex -> CKK Paradiso -> direct Thai/Malaysian importer/manufacturer path.

## C. Eggs

Bay Area restaurants have recently experienced extreme egg volatility; a 15-dozen case reportedly ranged from roughly **$40** recently to as high as **$120** during the shortage.

That implies approximately:

- $40/case = **$0.22/egg**
- $120/case = **$0.67/egg**

Nasi Lemak, Mee Goreng and CKT all use egg, so an extreme move can add roughly $0.45 per affected dish.

**Rule:** maintain two approved egg sources and never redesign the menu around temporary egg spikes unless they persist.

## D. Frying oil

Current foodservice benchmark: about **$51.99 for 35 lb canola oil** before local supplier negotiation.

Oil cost is less important than oil life and fryer architecture.

Avoid:

- contaminating oil with unnecessary products
- excessive fryer dependence during rush
- discarding oil prematurely
- halal-control conflicts that force wasteful oil replacement

A dedicated halal fryer requirement could materially change both capital and oil economics and must be resolved with the certifier.

---

# 7. Certification, permits and insurance

These are mostly fixed/semi-fixed barriers rather than per-meal killers, but they matter during low-volume launch.

## Santa Clara County

Current March 1, 2026 county fee schedule contains material permit/application fees for food operations. Exact DAMB GOOD LAH classification remains subject to County confirmation.

Do not spread an assumed permit cost into the model until the County confirms our code.

## HALAL certification

HFSAA quote still required.

American Halal Foundation is now a secondary certification path; it publicly states there is **no application fee for product qualification**, but certification cost depends on facility/product complexity and requires a quote.

## Insurance

Current California restaurant-business marketplace averages from Insureon are approximately:

- general liability: **$42/month** among California restaurant customers in its current California dataset
- workers' compensation: **$62/month** average in the same California dataset
- BOP: **$59/month** average in that dataset

A broader restaurant dataset shows higher medians, including a **$251/month BOP**, so actual commissary-required limits and payroll exposure matter more than internet averages.

**Rule:** obtain actual quotes against The Commissary's required limits before lease commitment.

---

# 8. Commissary hidden charges and storage

The base Snell rate is not the full cost until verified.

Potential leakage:

- extra refrigerator shelf
- freezer shelf
- dry shelf
- cleaning
- grease/oil disposal
- trash
- utilities
- reservation penalties
- cancellation charges
- insurance requirements
- key/access fees
- equipment add-ons
- dedicated HALAL storage/equipment

A $200/month hidden fee is trivial at 3,000 meals/month (~$0.07/meal) but painful at 300 meals/month (~$0.67/meal).

This reinforces the launch rule: keep fixed cost low until volume is proven.

---

# 9. Equipment bottlenecks and rework

Weak equipment creates invisible cost through:

- slower throughput
- waiting for shared stations
- repeated reheating
- rejected CKT
- noodle overcooking while waiting for burner access
- fryer queues
- unnecessary labor overlap

A kitchen with cheaper rent but poor equipment access can therefore cost more per meal than a slightly more expensive kitchen.

**CKT is the test case.** Burner recovery over consecutive portions matters more than nominal burner presence.

---

# 10. Customer acquisition cost

The danger is paying consumer-ad acquisition cost for an $11.95 one-time customer.

Prefer:

1. office manager / executive assistant / lab manager direct outreach
2. office captain referral
3. repeat email/SMS/direct-order customers
4. organic social
5. controlled paid acquisition tests
6. marketplace discovery only when incremental contribution is positive

One recurring 30-meal office account can justify substantially more acquisition effort than dozens of one-off consumer orders.

Track:

- CAC per first order
- CAC per first *repeat* customer
- 30/60/90-day contribution by account
- repeat interval

---

# Ranked economic attack plan

## Tier 1 — solve before launch

1. **Throughput:** demonstrate >=18 consumer / >=24 corporate main-equivalents per total paid kitchen hour.
2. **Snell all-in economics:** confirm no material hidden fees and reliable equipment access.
3. **Delivery density:** design corporate drops around 20+ meals and no default single-order subsidy.
4. **Direct ordering:** preserve direct/card/ACH channels and avoid marketplace dependence.
5. **Halal chicken:** determine whether the ~$2.14/lb Koch/CHEF'STORE candidate is HFSAA-acceptable; otherwise negotiate local wholesale toward <=$3.00/lb landed.
6. **Beef:** target <=$6.25/lb landed and compare cooked usable yield.
7. **Lap cheong:** obtain a real U.S. supply + certification + landed-cost solution.

## Tier 2 — validate in production simulation

8. Packaging <=$1.15 consumer / <=$0.65 corporate without degrading food.
9. Waste <=5% after stabilization.
10. Shrimp spec that preserves quality at lowest usable cost.
11. Oil consumption per 100 meals.
12. Egg sourcing redundancy.
13. Rice/noodle/produce supplier case pricing.

## Tier 3 — control as volume grows

14. insurance
15. certification annual costs
16. accounting/payroll software
17. marketing CAC
18. equipment replacement/repair reserve
19. additional storage
20. employee bonus system only after baseline measurement

---

# Core economic principle

Do not chase a $0.20 ingredient saving while tolerating:

- $2-$4/meal of poor kitchen utilization
- $3-$4/meal marketplace commission
- $7-$10 single-order courier cost
- $0.50-$1 packaging creep

The largest cost savings are structural.

**DAMB GOOD LAH wins economically by producing many excellent meals in a short paid window, moving them in dense orders, keeping customers direct, and buying proteins intelligently.**

---

## Current-source checkpoint

Accessed 2026-09-07:

- City of San Jose 2026 minimum wage notice: https://www.sanjoseca.gov/home/showpublisheddocument/125072/638949248001170000
- Square restaurant pricing: https://squareup.com/us/en/point-of-sale/restaurants/pricing
- Uber Direct merchant page: https://merchants.uber.com/uber-direct.html
- DoorDash Drive pricing: https://developer.doordash.com/en-US/docs/drive/overview/pricing_payment/
- Uber Eats merchant terms: https://www.uber.com/us/en/legal/uber-eats-merchant-terms-and-conditions/
- Santa Clara County Environmental Health fee schedule: https://files.santaclaracounty.gov/exjcpb1761/2026-01/deh-fee-march-2026.pdf
- Insureon California restaurant insurance: https://www.insureon.com/food-business-insurance/restaurants/california
- AHF California halal certification: https://halalfoundation.org/halal-certification-in-california/
- WebstaurantStore 36 oz 3-compartment container benchmark: https://www.webstaurantstore.com/choice-32-oz-black-9-3-4-x-7-1-4-x-2-3-compartment-rectangular-microwavable-heavy-weight-container-with-lid-case/129MCS323CB.html
- WebstaurantStore foil container benchmark: https://www.webstaurantstore.com/choice-8-1-2-x-6-3-8-3-compartment-foil-take-out-tray-with-board-lid-case/612D3COMP.html
- WebstaurantStore canola oil benchmark: https://www.webstaurantstore.com/canola-oil-35-lb/101CANOLABLK.html
- Foodomarket raw P&D shrimp wholesale reference: https://www.foodomarket.com/en-us/products/frozen-fish-and-seafood/frozen-raw-peeled-and-deveined-tail-on-shrimp
