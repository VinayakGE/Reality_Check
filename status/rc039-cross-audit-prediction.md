# RC-039 Cross-Audit Prediction

**Date recorded:** 2026-06-24
**Status:** Pre-registered — audit not yet conducted

This prediction constitutes the fifth cross-audit ontology prediction in the repository's history. The predictor (domain maturity score) was independently committed before domain selection, satisfying the anti-circularity condition established by OQ-Maturity.

---

## Two-Era Context

The cross-audit prediction program now splits into two eras with different evidential status:

**Pre-operationalization (RC-035, RC-036, RC-037):** Maturity classified during or after audit. Predictions correct, but vulnerable to OQ-Maturity circularity criticism. Answer Question A (does the gradient exist?) but not Question B (does it survive independent measurement?).

**Post-operationalization (RC-038 onward):** Maturity score committed from operationalization criteria before domain selection. RC-038 provided the first observation answering both questions. RC-039 is the second.

---

## Maturity Score Reference

The maturity score for this domain was committed prospectively in `status/domain-maturity-operationalization.md` as **Candidate B — Vitamin A Supplementation and Child Mortality**, dated 2026-06-24, before RC-039's specific claim was selected.

| Criterion | Score |
|---|---|
| NEA (Natural Experiment Availability) | High |
| DAM (Dedicated Attribution Methodology) | High |
| SRC (Systematic Review Consensus) | High |
| RD (Replication Depth) | High |

**Domain maturity classification: High.**

---

## Prediction

**Domain:** Child Health Nutrition / Epidemiology

**Claim:** "Vitamin A supplementation reduces all-cause child mortality by approximately 24% in populations where vitamin A deficiency is prevalent." — Cochrane Collaboration / WHO / UNICEF / Alfred Sommer

**Predicted Primary Object:** Attribution Precision Gap

**Predicted Secondary Object:** Watch B — minimal or absent

**Predicted Non-Appearance:** Counterfactual Unavailability

**Reason:**

High-maturity classification across all four criteria predicts APG dominance. The RCT evidence base (Cochrane meta-analysis, dozens of trials across countries) has largely resolved the causal-role question: VAS reduces child mortality in settings with vitamin A deficiency. This is not seriously disputed. Watch B is therefore predicted minimal.

The live frontier is at the precision level. The DEVTA trial (Awasthi et al., 2013) — the largest nutrition RCT ever conducted, 1 million children in Uttar Pradesh — found only a 4% mortality reduction, not statistically significant. The Cochrane pooled estimate is 24%. Reconciling these estimates requires decomposing: (a) whether population vitamin A deficiency prevalence moderates effect size; (b) whether delivery mode (community-based vs. facility-based) affects coverage and hence effect; (c) whether the comparison populations in older trials had higher baseline deficiency than contemporary India. These are precision questions — they dispute not whether VAS works, but where, by how much, and in which populations. That is an APG dispute.

Counterfactual Unavailability is predicted absent because RCTs construct explicit comparison groups.

---

## Gradient Position and Symmetry

This prediction, if confirmed, creates post-operationalization observations at both Low and High ends of the gradient:

| Maturity | Pre-operationalization | Post-operationalization |
|---|---|---|
| Low | RC-035 (Watch B) | RC-038 (Watch B) |
| Intermediate | RC-037 (APG) | — |
| High | RC-036 (APG) | RC-039 (APG, predicted) |

A confirmed RC-039 answers Question B (gradient survives independent measurement) at the High end for the first time, matching what RC-038 provided at the Low end.

---

## What Would Constitute a Real Failure

**Watch B primary:** The causal role of VAS is contested at the domain level, not merely the precision level. This would mean the Cochrane evidence is less settled than the High-maturity score suggests — requiring re-examination of the SRC and RD criteria.

**Counterfactual Unavailability primary:** Would be structurally surprising given RCT design; would require that even the RCT comparison groups are inadequate for attributing effects. Very unlikely.

**New object (effect modification as structural bottleneck):** A possible outcome given the DEVTA puzzle. If the dispute is better described as "VAS works conditionally and the condition is unknown" rather than "VAS works and we disagree about how much," it may be neither standard Watch B nor standard APG. This possibility is flagged as an edge case to watch.
