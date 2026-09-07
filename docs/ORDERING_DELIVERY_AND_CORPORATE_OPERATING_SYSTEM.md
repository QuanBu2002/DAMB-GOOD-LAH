# DAMB GOOD LAH — Ordering, Delivery + Corporate Operating System

## Objective

Own the customer relationship, keep channel leakage low, make office ordering extremely easy, and ensure an ordering-platform outage cannot stop a confirmed production run.

---

# 1. Channel hierarchy

Preferred order economics:

1. **Direct corporate preorder**
2. **Direct pickup**
3. **Direct consumer delivery using flat-fee courier**
4. **Selective marketplace discovery / overflow**
5. High-commission marketplace only when incremental contribution is positive

Do not judge channels by revenue alone. Judge by contribution, customer ownership and repeat rate.

---

# 2. Launch ordering stack

## Recommended primary — Square Free to start

Current public Square pricing provides:
- $0/month Free plan.
- commission-free direct ordering profile.
- current online processing around 3.3% + $0.30 on Free.
- in-person processing around 2.6% + $0.15 on Free.
- pickup/local delivery settings.

This is adequate for launch unless testing reveals a specific missing capability.

### Why not overbuy the POS

DAMB GOOD LAH's early complexity is production, HALAL, corporate logistics and demand—not table service.

Do not spend on restaurant software modules that solve problems we do not yet have.

## Upgrade trigger

Consider paid Square / Toast / another system when measured pain exists in:
- kitchen display/ticket routing.
- multi-device order management.
- inventory integration.
- large recurring catering account management.
- customer CRM/loyalty.
- volume-based processing economics.

---

# 3. Ordering redundancy

## Primary
Square direct order page / payment.

## Warm backup
A second direct ordering capability can be activated if needed, including DoorDash Commerce/Online Ordering or another low-fixed-cost system after fee review.

## Manual emergency order path

For known corporate clients:
1. email/phone order accepted by authorized operator.
2. standardized order form entered manually.
3. written confirmation sent.
4. payment collected by approved invoice/payment-link/ACH/card method.
5. offline production packet created.

Manual ordering is a failover, not the preferred consumer experience.

---

# 4. Corporate order format

For every office order capture:
- organization.
- organizer name.
- mobile.
- email.
- billing contact if different.
- exact delivery address.
- building/floor/suite.
- parking/loading instruction.
- handoff location.
- meal count.
- mains/count by SKU.
- dietary/allergen requests.
- roti/add-ons.
- delivery time.
- arrival window promised.
- labeling requirement.
- payment terms/status.
- cancellation cutoff.

Never rely on a loose email thread once order size is meaningful.

---

# 5. Office menu architecture

## Preferred 20+ meal format

Encourage 2–3 mains.

Best early batching candidates:
- Padang Chicken Rice.
- Nasi Lemak Lah.
- Padang Beef Rice.
- Damb Good Mee Goreng.

CKT:
- include only after high-volume wok behavior is validated.
- cap quantity per drop if needed to protect execution.

Roti:
- strong attachment opportunity.
- test table-share bundle and per-meal add-on.

## Menu concentration incentive

Do not necessarily offer a cash discount.

Possible benefits for concentrated orders:
- complimentary/discounted table roti at low product cost.
- delivery inclusion above threshold.
- organizer meal after threshold.

The incentive should reflect operational savings.

---

# 6. Corporate pricing

Consumer menu prices are not a ceiling on corporate pricing.

Corporate buyers purchase:
- delivery coordination.
- one invoice/order.
- reliable timing.
- labeling.
- dietary accessibility.
- simplified organizer workload.

Therefore model corporate pricing independently.

Track realized price/paid meal after:
- discounts.
- organizer reward.
- delivery subsidy.
- payment fee.

Do not use a universal 10–20% catering discount without evidence.

---

# 7. Corporate payment

Preferred for new/small account:
- card/direct online checkout.

For recurring trusted larger accounts:
- invoice/ACH may reduce payment leakage depending on system and administrative burden.

Square's current published ACH fee can be lower than card processing for larger invoices, subject to current plan caps/terms.

Do not introduce Net-30 accounts early without a business reason. Cash conversion matters.

---

# 8. Cancellation policy

Need enough protection to avoid converting a large preorder into waste.

Development starting architecture:
- small orders: reasonable cutoff.
- 20+ meal orders: final count/cancellation cutoff at least one business day ahead unless production data supports shorter.
- very large/custom orders: deposit/prepayment or stronger cancellation terms.

Final policy should be customer-friendly but must reflect irreversible prep.

---

# 9. Delivery architecture

## Corporate primary

One coordinated delivery per destination.

The driver should receive:
- business name.
- destination.
- organizer phone.
- order count.
- pickup-ready time.
- promised arrival.
- parking instruction.

The organizer receives:
- ETA/tracking where available.
- one contact number.

## Corporate delivery costing

Measure delivery per **drop**, then divide by meals.

Example:
- $12 delivery / 20 meals = $0.60/meal.
- the same drop cost / 40 meals = $0.30/meal.

This is one reason corporate density matters.

---

# 10. White-label courier redundancy

## Uber Direct

Current public model:
- 0% marketplace commission.
- per-delivery fee.
- no startup cost/monthly minimum advertised.
- pricing varies by distance/region/channel.

Use only actual San Jose test quotes in the model.

## DoorDash Drive On-Demand

Current public model:
- orders originate through our own ordering channel.
- flat fee per delivery rather than marketplace commission.
- no signup/subscription/payment processing/termination fees currently described for Drive On-Demand itself.

## Decision

Set up/quote both before broad direct delivery.

Use:
- cost.
- reliability.
- geographic coverage.
- batching/order size limitations.
- support quality.

as the selection criteria.

---

# 11. Driver failure SOP

If courier has not arrived by pickup-ready + 5 minutes:
- check assignment/ETA.

At +10:
- contact courier/platform.
- prepare backup dispatch if projected arrival threatens customer window.

At +15 or earlier if ETA is clearly unacceptable:
- invoke backup courier/self-delivery route if feasible.
- notify organizer proactively.

Record:
- scheduled pickup.
- actual pickup.
- arrival.
- food temperature if significant delay.
- customer impact.

---

# 12. Delivery radius

Do not begin with a large consumer delivery radius.

Determine radius empirically from:
- travel time distribution.
- food quality by dish.
- courier cost.
- lunch traffic.

Possible architecture:
- core direct zone where T15 is typical.
- outer zone only for dishes proven at T30 or for scheduled corporate deliveries.

CKT may have a narrower radius than rice dishes.

---

# 13. Offline order packet

For every confirmed 20+ meal order generate a human-readable packet before production day.

Page/section 1 — customer
- contact/address/time/payment.

2 — counts
- exact menu quantities.

3 — batch plan
- component quantities and prep needs.

4 — station plan
- cook/assembly responsibilities.

5 — packaging
- labels and box counts.

6 — delivery
- driver/handoff/route notes.

This packet must work even if internet/POS is unavailable.

---

# 14. Corporate acquisition funnel

## Prospect definition

High-value prospect has:
- 15+ people colocated at lunch.
- identifiable organizer.
- recurring meetings/lunch need.
- South Bay delivery feasibility.
- possible value from HALAL inclusion.

## Priority segments

Tier A:
- larger medical/clinical departments.
- university/research labs.
- startups/tech offices with workplace operations.
- recurring team lunch programs.

Tier B:
- professional offices.
- coworking spaces.
- small conferences/events.
- community organizations.

## Contacts

Best roles:
- workplace experience.
- office manager.
- executive assistant.
- People/HR.
- operations.
- department administrator.
- lab manager.
- clinic manager.
- event coordinator.

---

# 15. Initial outreach offer

Do not lead with a large discount.

Lead with:
- distinctive Malaysian lunch.
- clear per-person pricing.
- fully HALAL status **only after certification**, or accurate pre-certification language before approval.
- easy 2–3-option office menu.
- coordinated delivery.
- optional roti/table add-on.

Possible first-drop incentive:
- table roti or organizer meal above threshold.

Use incremental product cost as CAC, not full menu value.

---

# 16. Corporate CRM fields

Maintain:
- company.
- office location.
- employee count estimate.
- contact.
- title.
- email.
- phone.
- source.
- first outreach date.
- response.
- discovery notes.
- food restrictions.
- sample/pilot date.
- first paid order.
- order size.
- realized $/meal.
- contribution.
- reorder date.
- reorder interval.
- next action.

The most important field is **reorder**.

---

# 17. Sales experiment cadence

Early experiments should answer specific questions.

Examples:
- Does free table roti increase conversion vs no incentive?
- Do lab/clinic groups reorder more than startups?
- Is 20-meal minimum too high for first purchase?
- Does a fixed 3-main office menu outperform custom six-main choice?

Do not change multiple offer variables at once if trying to learn causal effects.

---

# 18. Marketplace strategy

Marketplace is permitted for:
- discovery.
- incremental unused capacity.
- customer acquisition when conversion to direct repeat can occur legally and organically.

Do not:
- build staffing around unpredictable marketplace spikes.
- accept orders that degrade corporate commitments.
- let 25–30% commissions dictate consumer menu economics.

Track channel-level contribution separately.

---

# 19. Customer service recovery

For a materially late, wrong or poor-quality order:
1. acknowledge quickly.
2. determine affected meals.
3. refund/credit proportionally as appropriate.
4. record root cause category.
5. correct system failure.

Do not create generous recovery policies that hide recurring operational defects.

---

# 20. Go-live gates

Before direct ordering goes public:
- [ ] checkout tested on mobile.
- [ ] confirmation received correctly.
- [ ] taxes/fees reviewed.
- [ ] pickup/delivery windows correct.
- [ ] sold-out controls tested.
- [ ] order reaches production workflow.
- [ ] refund process tested.
- [ ] backup manual process documented.

Before corporate outreach scales:
- [ ] office menu finalized.
- [ ] delivery pricing/radius defined.
- [ ] order form exists.
- [ ] cancellation policy exists.
- [ ] 20-meal production validated.
- [ ] sample/pilot feedback workflow exists.
- [ ] CRM exists.

---

# 21. Core commercial scoreboard

Weekly track:
- direct consumer orders.
- corporate orders.
- meals/order.
- revenue.
- realized $/meal.
- payment/channel leakage.
- delivery cost/order + meal.
- contribution/order + meal.
- repeat customers.
- office reorder rate.
- average days to reorder.
- roti attach rate.
- refunds/remakes.
- on-time %.

Do not scale based on gross sales without these economics.
