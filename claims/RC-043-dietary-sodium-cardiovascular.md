# RC-043: Dietary Sodium and Cardiovascular Mortality

**Claim:** "High dietary sodium intake is a primary cause of elevated blood pressure and cardiovascular disease mortality — reducing sodium consumption to WHO-recommended levels would prevent millions of premature deaths annually."

**Sources:** WHO (2012), "Guideline: Sodium Intake for Adults and Children" (<2g/day recommendation); He FJ and MacGregor GA, multiple Cochrane reviews and meta-analyses; Mozaffarian D et al. / GBD Diet Collaborators (2019), "Health effects of dietary risks in 195 countries"; Sacks FM et al. (2001), "Effects on Blood Pressure of Reduced Dietary Sodium and the Dietary Approaches to Stop Hypertension (DASH) Diet"; INTERSALT Cooperative Research Group (1988)

**Key formulations:**
- WHO (2012): "Reducing sodium intake to the recommended levels could prevent 2.5 million deaths each year." Based on GBD comparative risk assessment applying exposure-response functions to population sodium intake distributions.
- GBD Diet Collaborators (2019): High sodium intake (>3g/day vs. optimal 1–3g/day) associated with 3 million deaths globally per year from cardiovascular disease; largest dietary risk factor.
- He and MacGregor (2013 Cochrane): "A modest reduction in salt intake for four or more weeks causes significant and, from a population viewpoint, important falls in blood pressure in both hypertensive and normotensive individuals."
- PURE (Mente et al. 2016, NEJM): "Sodium intake between 3 g and 6 g per day was associated with a lower risk of death and cardiovascular events than was either a higher or lower estimated sodium intake" — a J-shaped curve directly challenging the low-sodium-is-better narrative.

**Status:** Unresolved
**Date:** 2026-06-24

---

## Cross-Audit Pre-Registration Reference

Prediction on record ([status/rc043-cross-audit-prediction.md](../status/rc043-cross-audit-prediction.md)), committed 2026-06-24 before this audit:

- **Primary object:** Attribution Precision Gap
- **Secondary object:** Watch B — present; character not pre-specified (the diagnostic question)
- **Predicted absent:** Counterfactual Unavailability
- **Composite maturity:** Intermediate (1 High DAM + 3 Intermediate)
- **Wound 6 test:** Does High DAM (WHO/GBD named methodology) coexist with Theoretical Watch B (PURE J-curve, dose-response shape debate)?
- **Additional diagnostic:** Does DAM alone drive Watch B transformation, or is SRC also required (unlike RC-041 where both were High)?

---

## Why This Claim Matters

Sodium reduction is a cornerstone of cardiovascular disease prevention policy globally. WHO member states have committed to reducing mean population sodium consumption by 30% by 2025. Food manufacturers face regulation and reformulation pressure. Public health messaging urges low-sodium diets. The burden estimate (3 million deaths annually attributable to high sodium) directly justifies the priority given to sodium reduction over competing public health interventions.

If the GBD burden estimate is well-founded, sodium reduction is among the highest-priority preventable causes of death — more consequential than many infectious diseases that receive more research funding. If the PURE findings reflect a genuine J-curve and the optimal sodium level is higher than WHO recommends, the policy guidance has potentially been directing population behavior toward harmful rather than beneficial sodium ranges for a substantial part of the distribution.

---

## Maturity Score

| Criterion | Score | Evidence |
|---|---|---|
| NEA | Intermediate (lean Low) | DASH-Sodium trial (RCT, not natural experiment); Finnish Heart Association campaign (quasi-experiment, not exogenous); UK salt reduction initiative (policy intervention, not exogenous); INTERSALT (observational); approximately 2–4 usable quasi-experiments |
| DAM | High | WHO comparative risk assessment with formal <2g/day threshold; GBD named comparative risk assessment methodology for dietary sodium; He-MacGregor systematic review process used in major policy documents; formal quantitative burden estimation |
| SRC | Intermediate | Sodium → blood pressure: consistent direction, strong consensus. Blood pressure → CVD: consistent. But PURE (2016) substantially complicates the sodium → CVD direct link; Cochrane reviews have high heterogeneity; optimal sodium level genuinely contested |
| RD | Intermediate | Sodium → blood pressure replicated extensively by independent teams; direct sodium → CVD mortality replicated less consistently; PURE internationally across 18 countries contradicts low-sodium direction |

**Classification: Intermediate** (1 High + 3 Intermediate)

---

## Alternative Explanations

**H1 — J-Shaped Dose-Response (PURE hypothesis)**

The PURE study (Prospective Urban and Rural Epidemiology), a cohort of 103,570 individuals across 18 countries, found that both very high sodium intake (>6g/day) and very low sodium intake (<3g/day) were associated with higher rates of cardiovascular events and death, while the lowest risk was in the 3–6g/day range. This directly contradicts the WHO guideline of <2g/day, which falls below the PURE-optimal range.

PURE's mechanistic explanation: sodium restriction activates the renin-angiotensin-aldosterone system (RAAS), which increases angiotensin II levels and may cause cardiovascular harm through pathways that offset blood-pressure reduction benefits. Very low sodium may also impair cardiovascular autonomic function.

*Theoretical Watch B character:* If PURE reflects a real J-curve, the mechanism through which sodium causes harm at high levels is partially offset by harm from RAAS activation at low levels. The net causal effect of sodium reduction from current Western diet levels (approximately 3.5–4g/day) to WHO levels (<2g/day) is then genuinely contested — not merely uncertain in magnitude, but potentially wrong in direction for some populations.

**H2 — Measurement Error in Dietary Sodium Assessment**

Most cohort studies measure sodium intake through 24-hour dietary recall or food frequency questionnaires, both of which have substantial measurement error. A single or even multiple 24-hour urine collections (the gold standard) represent only a snapshot of long-term sodium intake. Cohort studies that rely on dietary recall or estimated intake may show attenuated associations. Some PURE critics argue the J-curve reflects measurement error and regression dilution bias — people who appear to have very low sodium intake actually consume more than measured.

*Methodological Watch B dimension:* This is a measurement quality concern within an accepted causal framework (sodium causes hypertension; the question is whether study designs accurately measure long-term intake). This is methodological, not theoretical Watch B.

**H3 — Confounding by Disease — Reverse Causation**

Individuals with existing cardiovascular disease may reduce sodium intake in response to medical advice — producing apparent low sodium → high CVD risk through reverse causation. PURE attempted to control for this by examining only individuals free of CVD at baseline, but reverse causation from subclinical disease (pre-hypertension reducing sodium before clinical diagnosis) may still operate. Similarly, very ill individuals who eat less of everything may appear to have low sodium intake.

*Methodological Watch B dimension:* This is a confounding concern within an accepted causal structure — the causal direction (high sodium causes disease) is accepted; the methodological concern is whether reverse causation biases the dose-response estimate at low sodium levels.

**H4 — Potassium-Sodium Ratio as the Operative Variable**

Nutritional epidemiology increasingly suggests that the sodium-potassium ratio, rather than absolute sodium intake, determines cardiovascular risk. High potassium intake offsets adverse effects of high sodium through renal and vascular mechanisms. Studies that fail to account for potassium intake may misattribute to sodium what is actually a potassium-deficiency effect. If sodium-potassium ratio is the true causal variable, reducing sodium without increasing potassium may have smaller effects than predicted.

*APG and Watch B mixed:* This challenges whether sodium per se causes CVD (Watch B) or whether the attributed burden correctly accounts for the joint effect of sodium and potassium (APG — contribution share incorrectly specified).

---

## Evidence Supporting the Claim

**DASH-Sodium trial (Sacks et al. 2001):** A randomized controlled trial assigned 412 participants to different sodium intake levels (high: 3.5g/day; intermediate: 2.3g/day; low: 1.2g/day) while controlling background diet. Blood pressure decreased dose-responsively with sodium reduction in both the DASH and control diet conditions. The trial is the strongest controlled evidence that sodium reduction causes blood pressure reduction. For the subset with hypertension, the low-sodium condition reduced systolic blood pressure by 11.5 mmHg.

**He and MacGregor Cochrane reviews:** Multiple systematic reviews and meta-analyses by He and MacGregor find that modest, sustained sodium reductions (approximately 40–50 mmol/day) produce significant blood pressure reductions in both hypertensive (average −5/−2 mmHg) and normotensive (average −2/−1 mmHg) individuals. The Cochrane reviews find no evidence of harm from reduced sodium in trials.

**Epidemiological association and mechanistic chain:** The sodium → blood pressure → CVD chain has two well-established links. Sodium → blood pressure: established through RCTs (DASH-Sodium), cohort studies (INTERSALT), and mechanistic studies. Blood pressure → CVD: established through RCTs of blood pressure-lowering medications. The two-step mechanistic chain provides indirect evidence that sodium reduction should reduce CVD.

**GBD burden estimation:** The GBD's comparative risk assessment applies sodium-blood pressure and blood-pressure-CVD exposure-response functions to population sodium intake distributions to estimate attributable mortality. The methodology is formally specified, peer-reviewed, and used in official WHO and national policy documents. Among dietary risk factors, high sodium intake is the largest contributor to CVD deaths in the GBD 2019 analysis.

**Population-level correlations:** Countries and time periods with lower sodium intake tend to have lower cardiovascular mortality after controlling for other major risk factors. The Finnish Heart Association's salt reduction campaign (1972–1992), which reduced mean sodium intake by approximately 3g/day, coincided with a 60–75% reduction in cardiovascular mortality — though the intervention also included other cardiovascular risk factor changes.

---

## Evidence Against / Creating Doubt

**PURE (Mente et al. 2016, NEJM) — the central Wound-6 activating observation:**

The PURE study enrolled over 100,000 participants across 18 countries spanning all economic levels, using multiple 24-hour urine collections (the gold standard for sodium measurement). The primary finding was a J-shaped association: both low sodium (<3g/day, which includes the WHO guideline range) and high sodium (>6g/day) were associated with higher cardiovascular mortality than the 3–6g/day range.

PURE's finding is not easily dismissed:
- 18-country sample provides cross-cultural replication
- Multiple 24-hour urine collections reduce single-measurement bias
- The J-shape persisted in multiple sensitivity analyses
- The finding implies WHO guidelines may be directing populations toward harm, not benefit

PURE's interpretation is contested:
- He, MacGregor, and others argue the J-curve reflects measurement error and reverse causation at low sodium
- The Cochrane review authors maintain trial evidence (DASH-Sodium) shows blood pressure reduction without harm at low sodium
- There is no agreed methodological resolution between the PURE authors and the consensus camp

**The 2021 WHO guideline controversy:** Despite PURE and subsequent observational evidence of J-shaped associations, WHO (2021) reiterated its <2g/day recommendation. Critics argue WHO's evidence review methodology excluded observational evidence unfavorable to the guideline. Supporters argue trial evidence of blood pressure reduction is more reliable than observational evidence of mortality outcomes.

**Sodium sensitivity heterogeneity:** Approximately 25–40% of normotensive and 50–60% of hypertensive individuals are "salt-sensitive" — their blood pressure responds substantially to sodium changes. Salt-insensitive individuals show minimal blood pressure response to sodium changes. If population-level sodium reduction targets primarily benefit salt-sensitive individuals, the population-average effect is smaller than guideline-based burden estimates assume.

**RAAS activation concern:** There is mechanistic evidence that sodium restriction activates the RAAS system (increasing renin, aldosterone, and angiotensin II), which has adverse cardiovascular effects through pathways independent of blood pressure. This provides a mechanistic basis for the J-curve that is distinct from measurement error explanations.

---

## Missing Evidence

**Large RCT of sodium reduction on hard cardiovascular endpoints:** No RCT has directly tested the effect of sustained, substantial sodium reduction on cardiovascular mortality or major cardiovascular events. DASH-Sodium tested blood pressure; the intervention was 30 days; the outcome was blood pressure, not CVD events. A long-term (3–5 year) RCT of sodium reduction targeting <2g/day vs. 3–4g/day, with cardiovascular events as the primary outcome, would resolve the dose-response shape question. The TOHP (Trials of Hypertension Prevention) follow-up provided some evidence but with limited power.

**Mechanistic resolution of RAAS debate:** RAAS activation from sodium restriction is documented but its net cardiovascular effect is contested. A study that simultaneously quantifies blood pressure reduction benefit and RAAS-mediated harm from sodium restriction, with net cardiovascular outcome, would clarify whether the J-curve is causal or artifactual.

**Dose-response in salt-sensitive vs. insensitive populations:** A trial with genetic or biomarker stratification of salt sensitivity, testing the hypothesis that sodium reduction benefits salt-sensitive individuals but is neutral or harmful for salt-insensitive individuals, would address the heterogeneity concern and potentially reconcile the PURE and Cochrane review findings.

---

## Current Status and Confidence

**Status: Unresolved**

The sodium → blood pressure mechanism is firmly established. The public health case for avoiding very high sodium intake (>6g/day) is widely supported. What is unresolved is whether sodium reduction to WHO-recommended levels (<2g/day) from current Western intake levels (3.5–4g/day) reduces cardiovascular mortality at the population level, given (a) the J-curve evidence, (b) salt-sensitivity heterogeneity, and (c) RAAS activation concerns. The GBD burden estimate reflects one methodological position on a genuinely contested question.

---

## Watch Item Assessment

**APG — Primary: Confirmed.** The primary frontier among researchers who accept sodium's causal role (at some level) is precision: what is the dose-response shape? What is the optimal sodium range? What share of CVD deaths is attributable to sodium intake above 3g/day vs. above 2g/day vs. above any threshold? The GBD's estimate of 3 million attributable deaths depends on the TMREL and the exposure-response function shape — these are APG disputes about contribution shares.

**Watch B — Secondary, character: Theoretical and Methodological simultaneously.** This is the critical Wound 6 result.

Watch B is present in two simultaneous forms:

*Watch B Theoretical:* PURE's J-curve introduces genuine theoretical uncertainty about whether sodium reduction to WHO-recommended levels is net-beneficial or net-harmful for the portion of the population currently consuming 3–4g/day (most Western populations). This is not a confounding concern about the observational evidence — it is a theoretical claim that RAAS activation at low sodium causes cardiovascular harm through a different pathway than high-sodium-blood-pressure-CVD. The net causal effect direction for sodium reduction from 3.5g to 2g/day is genuinely uncertain, not just imprecisely estimated. That is Theoretical Watch B: the causal role (is it beneficial?) is contested, not just the magnitude.

*Watch B Methodological:* Simultaneously, the PURE critics argue the J-curve reflects measurement error and reverse causation — methodological artifacts, not genuine biology. This is Methodological Watch B: confounding concerns within an accepted framework (sodium reduction is beneficial; the J-curve is a methodological artifact).

Both forms are live simultaneously. The field has not resolved which account of PURE is correct.

**Counterfactual Unavailability — Absent: Confirmed.** GBD comparative risk assessment constructs explicit counterfactuals (TMREL). Trial evidence (DASH-Sodium) uses randomized comparison groups.

---

## CMech-001 / Wound 6 Assessment

**Wound 6 partially inflicted.** The pre-registration specified Wound 6 as: High DAM + Theoretical Watch B. This is partially what appeared. Theoretical Watch B is active in RC-043 despite High DAM — the GBD comparative risk assessment and WHO formal guidelines did not suppress the J-curve theoretical dispute.

However, the result is more complex than a clean Wound 6:
- Watch B is theoretical *and* methodological simultaneously
- The Theoretical Watch B is specifically about whether the WHO guideline (<2g/day) is in the beneficial range — a dispute about the target level of the policy intervention that DAM helped specify, not a dispute that DAM resolved
- DAM (GBD/WHO comparative risk assessment) may have actually *sharpened* the theoretical dispute by producing a specific quantitative guideline that PURE then challenged at that specific threshold

This suggests a refinement to the revised CMech-001: DAM may suppress Theoretical Watch B at the existence-of-causal-role level (is there any harmful effect of high sodium?) while leaving open Theoretical Watch B at the optimal-level-and-dose-response level (what sodium intake is actually optimal?). The WHO guideline certifies that high sodium causes CVD; it does not certify where the optimal minimum is, and PURE's challenge is specifically at that unspecified lower boundary.

**Implication for revised CMech-001:** DAM may resolve the *existence* question (does X cause Y at some level?) but not the *optimum* question (what is the best level of X?). The optimum question generates its own Watch B that DAM does not suppress even when it resolves the existence question.

**Watch B Type Table — updated:**

| Domain | Composite | NEA | DAM | Watch B Character |
|---|---|---|---|---|
| RC-035 Industrial Policy | Low | Low | Low | Theoretical (existence) |
| RC-037 Lead-Crime | Intermediate | Intermediate | Low | Theoretical (existence) |
| RC-038 Monetary Policy | Low | Low | Low | Theoretical (existence) |
| RC-040 Minimum Wage | Intermediate | High | Intermediate | Directional |
| RC-042 Incarceration | Low | High | Low | Theoretical (existence) |
| RC-041 Air Pollution | Intermediate | Intermediate | High | Methodological |
| RC-043 Dietary Sodium | Intermediate | Intermediate (lean Low) | High | Theoretical (optimum) + Methodological |
| RC-036 Climate Attribution | High | High | High | Minimal |
| RC-039 Vitamin A | High | High | High | Minimal |

RC-043 introduces a Watch B sub-type not previously distinguished: **Theoretical (optimum)** — the causal existence question is resolved by DAM, but the optimum level question generates new theoretical Watch B that DAM does not address.

---

## New Object Candidate — Watch B Optimum Sub-Type

A domain may have its existence-level Watch B resolved by DAM (the field accepts that X causes harm at some level) while retaining theoretical Watch B at the optimum-level question (where is the threshold between harmful and beneficial, and is current policy guidance in the right range?).

This sub-type is distinct from:
- Theoretical existence Watch B: is there any causal role?
- Directional Watch B: does the effect help or hurt?
- Methodological Watch B: confounding within an accepted framework

It is closer to directional Watch B in structure (direction of net effect at specified exposure levels is contested) but operates at a specific policy-relevant threshold rather than across the whole dose-response range.

**Status:** One instance. Anti-compression applies. Not a new promoted object.

---

## Ledger Entry

**APG:** Confirmed primary in second Intermediate domain with High DAM. Pattern consistent.

**Watch B:** Wound 6 partially inflicted — Theoretical Watch B (optimum sub-type) persists under High DAM. But the Watch B is about the optimal threshold, not the existence of causal role. Revised CMech-001 may need to distinguish DAM's scope: it may suppress existence-level Theoretical Watch B but not optimum-level Theoretical Watch B.

**Revised CMech-001:** Watch B Transformation Hypothesis has encountered its first complication. DAM suppresses Theoretical Watch B about causal existence (as in RC-041, RC-036, RC-039) but may not suppress Theoretical Watch B about optimal intervention level. This suggests the mechanism is more specific than initially stated: DAM resolves the existence question; the optimum question requires something additional (perhaps RD and SRC across the dose-response range, not just at a single threshold).

**Watch B Type complexity:** The Watch B type table now needs a sub-type column. Theoretical Watch B in RC-035/038/042 is existence-level; Theoretical Watch B in RC-043 is optimum-level. These may have different suppression mechanisms and different evidence requirements for resolution.
