# DAMB GOOD LAH — Test Kitchen + Scale Validation Plan

## Purpose

Convert culinary prototypes and economic assumptions into measured commercial reality.

A recipe is not commercially validated because it tastes good once. It must survive:
- batch production;
- repeat cooks;
- station constraints;
- holding and packaging;
- delivery time;
- measured food cost/yield;
- paid labor;
- actual customer consumption.

---

# 1. Experimental philosophy

Treat the launch process like a controlled engineering program.

Change as few variables as possible per run.

For every run distinguish:
- **input variables** — recipe, raw quantity, equipment, team, packaging;
- **process variables** — cook time/temp, batch size, hold time, assembly order;
- **outputs** — yield, quality, speed, waste, cost, delivery performance.

Do not declare a change better because one plate looked better.

---

# 2. Recipe validation levels

## Level R0 — development
Recipe exists but quantities/process remain exploratory.

## Level R1 — repeatable bench recipe
Same operator can reproduce it twice within agreed sensory tolerance.

## Level R2 — measured commercial batch
Raw inputs, final yield, portions and time are recorded.

## Level R3 — second-operator reproduction
A trained second person can reproduce from the written recipe/process without improvisation.

## Level R4 — delivery validated
Passes intended 0/15/30-minute delivery/holding window.

## Level R5 — production validated
Works inside 20+ meal production with target station throughput.

Only R4/R5 recipes are launch-ready.

---

# 3. Component validation

Each component receives a production spec.

## Padang curry
Record:
- raw ingredient weights.
- batch volume/weight.
- reduction loss.
- final usable yield.
- minutes active labor.
- total cook time.
- hold/reheat quality.
- 1x/2x/4x scale behavior.

Pass criteria:
- flavor consistency.
- correct viscosity after 30-minute delivery.
- stable oil/emulsion behavior.
- predictable portion yield.

## Main chicken preparation
Measure:
- raw thigh weight.
- trim loss.
- cooked weight.
- cooked yield %.
- food-safety cooling/hold/reheat timing as permitted.
- tenderness at service and 30 minutes.

Because the same main chicken preparation feeds multiple dishes, variability here propagates across the menu. This is a high-priority process-control point.

## Beef braise
Test candidate cuts based on finished usable economics.

Record:
- raw cut/case.
- trim.
- cooked yield.
- fat/connective tissue loss.
- serving texture.
- shredding/breakage loss.
- finished $/100g serving.

## Coconut rice
Test:
- cooker/batch size.
- rice:liquid ratio.
- hot-hold time.
- portion consistency.
- condensation in package.

## House sambal
Need defined base plus dish-specific finishing, not one generic finished sauce.

Measure:
- batch yield.
- refrigeration life under approved process.
- separation.
- portion speed.

## Mee Goreng sauce
Protect dedicated Mamak-style flavor lane.

Test across consecutive pans to ensure sauce dosing is fast enough for production.

## CKT seasoning/chile
Keep separate from mee goreng and curry lanes.

Validation requires actual high-heat consecutive-pan testing.

## Crispy garnishes
Chicken-skin crisp, beef-fat shallot crisp, ikan bilis-peanut crunch, crispy potato and curry tofu crisp need:
- batch yield.
- prep labor.
- storage conditions.
- crispness after 4/8/24 hours as relevant.
- crispness after 30-minute meal delivery.

Service-time fryer demand must remain limited.

---

# 4. Dish scorecard

Every launch dish is scored 1–5 on:
- flavor.
- aroma.
- texture.
- appearance.
- portion satisfaction.
- authenticity/identity.
- delivery survival.
- assembly complexity.
- station bottleneck risk.
- ingredient availability risk.
- cost confidence.

A dish does not pass because its average is high if its core identity metric fails.

CKT example: a beautiful plate with weak wok character is a failure.

---

# 5. Delivery validation protocol

For every launch dish prepare three identical portions.

## T0
Taste immediately after packing.

## T15
Hold in realistic closed delivery packaging for 15 minutes; simulate transport handling.

## T30
Hold/transport for 30 minutes.

Record at each time:
- food temperature.
- sauce leakage.
- rice texture.
- noodle clumping.
- noodle oversteaming.
- crisp-component integrity.
- vegetable texture.
- package deformation.
- aroma release.
- overall acceptability.

### Additional CKT measures
- flat-noodle breakage.
- clumping.
- wok aroma retention.
- sprout/chive texture.
- rendered lap-cheong texture.

If T30 fails but T15 passes, the business response may be a tighter delivery radius rather than changing the recipe.

---

# 6. Packaging A/B test

Never select packaging from appearance alone.

For each candidate container test:
- fill speed.
- close speed.
- leakage.
- stack stability.
- condensation.
- microwave behavior if relevant.
- label adhesion.
- unit cost.
- case storage footprint.
- 15/30-minute food quality.

Test vented versus non-vented only where food-safety and spill requirements remain acceptable.

Potentially separate crisp garnish in a small dry component if the quality gain clearly exceeds packaging/labor cost.

---

# 7. Production simulation architecture

## 10-meal mechanics run

Recommended menu:
- 4 chicken rice.
- 3 nasi lemak.
- 3 mee goreng.
- roti add-ons.

Purpose:
- validate assembly line and package staging.
- no CKT complexity required in first mechanics run.

## 20-meal Run A

Use 3 mains maximum.

Example:
- 8 chicken rice.
- 6 nasi lemak.
- 6 mee goreng.

Purpose: corporate-constrained batching.

## 20-meal Run B

Repeat same mix or intentionally vary one variable such as staffing or packaging.

Purpose: reproducibility.

## 30-meal run

Suggested 3-main architecture.

Test:
- prep scaling.
- rice capacity.
- hot holding.
- packing line.
- delivery carrier capacity.

## 50-meal run

Do not attempt until 30-meal bottlenecks are fixed.

Purpose:
- determine whether production scales approximately linearly or collapses from shared-resource contention.

---

# 8. CKT dedicated production test

CKT must be validated separately because average batch metrics can hide a bad wok station.

### Test 1 — single portion benchmark
Compare against the intended sensory standard.

### Test 2 — five consecutive portions
Measure:
- pan-to-pan time.
- burner recovery.
- noodle temperature.
- char/aroma.
- smoke/hood performance.

### Test 3 — ten-portion production sequence
Determine realistic CKT capacity/hour without degrading execution.

### Test 4 — delivery
0/15/30 minute.

CKT can remain selectively limited even if the rest of the menu scales faster. Do not bulk steam-fry CKT into mediocrity just to report a higher meals/hour number.

---

# 9. Paid labor accounting

Economic productivity denominator = **all paid kitchen labor time attributable to production**, not only minutes during the lunch rush.

Include:
- receiving/putaway attributable time.
- prep.
- setup.
- cooking.
- assembly.
- packaging.
- cleaning.
- breakdown.

Track owner labor as if it were paid when evaluating true business viability.

---

# 10. Waste measurement

Separate:
- trim loss expected by recipe.
- cooking yield loss.
- expired/spoiled inventory.
- overproduction.
- portioning error.
- remake/error waste.
- test/R&D waste.

Do not combine normal cooking yield with preventable waste.

Target ~5% preventable food waste after stabilization, with preordered corporate production ideally lower.

---

# 11. Portion validation

Current portions are test bases, not dogma.

Validate using:
- finished plated/boxed appearance.
- satiety/customer feedback.
- cost.
- delivery behavior.
- competitive value.

Portion reduction is not a valid economics fix if it makes the $11.95–$14.95 value proposition feel cheap.

---

# 12. Sensory panel

Early internal panel should include people familiar with Malaysian/Singaporean food where possible, plus target consumers.

Ask separate questions:
- Is it delicious?
- Does it taste like the dish it claims to be?
- Would you order it again at this price?
- Does it still work after delivery?

These are different questions.

Avoid leading panelists with the recipe change being tested.

---

# 13. Customer feedback

For paid pilots collect only high-value signals:
- favorite dish.
- weakest dish.
- portion satisfaction.
- delivery condition.
- price/value perception.
- would order again? yes/no.
- desired reorder frequency.

Behavior beats compliments. Track actual reorder.

---

# 14. Stop/fix thresholds

Pause scaling when:
- food-safety process cannot be executed reliably.
- a HALAL control cannot be maintained.
- >2% order accuracy failure persists.
- packaging leakage/damage is recurrent.
- one station creates >20% idle waiting elsewhere.
- throughput remains <~15 main-equiv/paid hour after basic process tuning.
- 30-minute quality failure affects core dishes.

The response is diagnosis, not price increases.

---

# 15. Process optimization order

When throughput is weak, investigate in this order:
1. batch/prep sequencing.
2. equipment contention.
3. mise-en-place completeness.
4. assembly layout.
5. packaging choreography.
6. menu concentration.
7. labor staggering.
8. recipe/process redesign that preserves flavor identity.
9. only then incremental equipment/labor spend.

---

# 16. Scale graduation gates

## Graduate 10 → 20 meals when
- zero critical process failures.
- order assembly map is clear.
- packaging selected provisionally.

## 20 → 30 when
- two 20-meal runs are reasonably reproducible.
- no recurring safety/quality failure.
- throughput trend is improving toward target.

## 30 → 50 when
- 30-meal bottlenecks have defined fixes.
- equipment capacity is adequate.
- packing/delivery capacity is proven.

## Simulation → paid pilot when
- dishes R4+.
- operator permit/insurance/HALAL requirements are satisfied for commercial sale.
- cost model uses measured yields.

## Paid pilot → wider launch when
- positive contribution is demonstrated.
- repeat demand exists.
- critical supplier redundancy exists.
- service can run without constant improvisation.
