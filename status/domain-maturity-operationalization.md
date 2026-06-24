# Domain Maturity Operationalization

**Date:** 2026-06-24
**Purpose:** Independent pre-audit operationalization of "domain maturity" for the domain-maturity hypothesis.

**Problem this solves:** In RC-035–RC-037, domain maturity was assessed during or after the audit — introducing circularity risk (maturity inferred from the same evidence that determined the bottleneck). This document specifies maturity criteria using observable, domain-level literature features that can be assessed before reading claim-specific evidence.

**The anti-circularity requirement:** Each criterion must be assessable from the structure and ecology of a domain's literature, not from reading the evidence about a specific claim within that domain.

---

## Four Criteria

### Criterion 1 — Natural Experiment Availability (NEA)

*What to assess:* How many published, peer-reviewed studies in this domain use natural experiment designs (instrumental variables, difference-in-differences with exogenous timing variation, regression discontinuity, randomized controlled trials) to isolate causal effects?

*How to assess:* Literature database search using domain terms AND methods terms (natural experiment, instrumental variable, quasi-experiment, RCT, difference-in-differences) before reading claim evidence.

| Score | Description |
|---|---|
| High | 10+ peer-reviewed natural experiment studies in domain; multiple independent research teams |
| Intermediate | 3–9 natural experiment studies; OR fewer with high methodological quality (major journal publication, widely cited) |
| Low | 0–2 natural experiment studies; domain relies primarily on observational correlations, case studies, or comparative analysis |

---

### Criterion 2 — Dedicated Attribution Methodology (DAM)

*What to assess:* Does the domain have a named, established causal attribution toolkit — formal methods developed specifically to answer "did X cause Y?" questions in this domain?

*How to assess:* Methodological literature search (domain + "attribution" or "causal inference" or "identification strategy") and examination of whether domain-specific methods textbooks or methodological standards exist.

| Score | Description |
|---|---|
| High | Named attribution methodology exists (e.g., event attribution science, DALY burden estimation, epidemiological attributable fraction methods); taught in domain-specific methodology courses; used in official reports |
| Intermediate | Domain borrows general econometric or epidemiological methods without domain-specific adaptation; no named attribution toolkit; methods applied variably across studies |
| Low | No standardized causal attribution methods; causation assessed through theoretical reasoning, comparative case analysis, or process tracing |

---

### Criterion 3 — Systematic Review Consensus (SRC)

*What to assess:* Do systematic reviews or meta-analyses find consistent causal direction AND reasonably convergent magnitude estimates across studies?

*How to assess:* Search for Cochrane reviews, Campbell Collaboration reviews, or equivalent systematic reviews in the domain. Examine: (a) whether the direction finding is consistent, (b) whether magnitude estimates fall within a 2x range of each other across the main meta-analyses.

| Score | Description |
|---|---|
| High | Multiple independent systematic reviews; consistent causal direction; magnitude estimates within a 2x range across reviews |
| Intermediate | Consistent causal direction across reviews but magnitude estimates diverge by more than 2x; OR only 1–2 systematic reviews exist |
| Low | Systematic reviews find inconsistent causal direction; OR no systematic reviews exist in the domain |

---

### Criterion 4 — Replication Depth (RD)

*What to assess:* How many independent research teams, using different datasets and methods, have replicated the core causal direction finding?

*How to assess:* Literature count of studies finding positive causal effect, negative causal effect, or null effect, across independent datasets and research teams.

| Score | Description |
|---|---|
| High | Core causal direction replicated by 10+ independent research teams; findings robust across countries, time periods, and data sources |
| Intermediate | Core direction replicated by 3–10 teams; OR robust within one regional context but not globally; OR robust for some sub-populations but not others |
| Low | Core direction from primary research program only; limited replication by independent teams; contradicted by significant replications |

---

## Maturity Classification

| Classification | Criteria |
|---|---|
| High | 3 or more criteria score High |
| Intermediate | Mixed — some High, some Low; no clear majority; OR 2 High and 2 Low |
| Low | 3 or more criteria score Low |

Edge cases: 3 High + 1 Low = High. 1 High + 3 Low = Low. 2 High + 2 Low = Intermediate.

---

## Prediction from Maturity

| Maturity | Predicted primary object | Predicted Watch B status |
|---|---|---|
| High | Attribution Precision Gap | Minimal or absent |
| Intermediate | Attribution Precision Gap | Present as secondary |
| Low | Watch B | Primary |

*These predictions follow from the domain-maturity hypothesis. They are not definitions — the hypothesis can fail.*

---

## Retroactive Check: Prior Domains

This section verifies that the operationalization criteria would have produced the same classifications used in the pre-registrations for RC-035, RC-036, and RC-037. If they do not, the criteria require revision before prospective use.

**RC-035 — Industrial Policy (East Asian Development)**

| Criterion | Assessment | Score |
|---|---|---|
| NEA | Very few natural experiments; primarily comparative case analysis across countries; some event-study designs but no clean natural experiments with exogenous timing variation | Low |
| DAM | No named industrial policy attribution methodology; development economists borrow general econometrics but no domain-specific causal attribution toolkit | Low |
| SRC | Systematic reviews do not find consensus; World Bank (1993) and heterodox economists (Amsden, Wade) reach opposite conclusions from overlapping evidence | Low |
| RD | Many studies but contradictory findings; high replication in terms of volume, low replication in terms of consistent direction | Low |

**Classification: Low.** Consistent with Watch B as primary in RC-035 pre-registration. ✓

---

**RC-036 — Climate Attribution Science (Pacific NW Heat Dome)**

| Criterion | Assessment | Score |
|---|---|---|
| NEA | Climate attribution uses counterfactual model ensembles rather than natural experiments per se; probabilistic attribution studies serve the same causal isolation function; 50+ attribution studies for various events | High |
| DAM | Event attribution science is a named methodology with formal probabilistic methods (fraction of attributable risk, probability ratio); taught in attribution science courses; used in IPCC and WMO reports | High |
| SRC | Multiple independent attribution groups (WWA, NOAA, academic groups) find consistent direction and similar magnitude ranges for major events; IPCC systematic assessment | High |
| RD | Core direction (anthropogenic warming increases extreme event probability) replicated across 100+ studies, multiple modeling centers, multiple event types globally | High |

**Classification: High.** Consistent with APG as primary in RC-036 pre-registration. ✓

---

**RC-037 — Lead-Crime (Leaded Gasoline Phaseout)**

| Criterion | Assessment | Score |
|---|---|---|
| NEA | Reyes (2007) is a major natural experiment (cross-state phaseout timing); Nevin international correlations are not natural experiments; limited additional natural experiments | Intermediate |
| DAM | Borrows econometric methods (difference-in-differences); no named lead-crime attribution methodology; no domain-specific attribution toolkit | Low |
| SRC | Studies find consistent positive direction (lead → crime) but magnitude estimates diverge dramatically: 10–20% (some estimates) to 56–90%+ (Reyes, Nevin) | Intermediate |
| RD | Replicated by multiple independent teams internationally; but significant contradictions remain; crack/abortion alternatives not ruled out by replication | Intermediate |

**Classification: Intermediate** (1 Low, 3 Intermediate — no High scores; intermediate classification applies). Consistent with APG primary + Watch B secondary in RC-037 pre-registration. ✓

---

**Retroactive check result:** All three prior domain classifications are reproduced by the operationalization criteria. The criteria are not derived from the outcomes — they are derived from the structure of causal inference quality in general and applied retroactively. The retroactive match is consistent with the criteria being valid, though not proof of it.

---

## Prospective Domain Scoring for RC-038

The following domains are scored BEFORE RC-038's claim is selected. These scores generate the prediction.

**Candidate A — Minimum Wage Effects on Employment**

| Criterion | Assessment | Score |
|---|---|---|
| NEA | Card-Krueger (1994) pioneered the state-border natural experiment; dozens of subsequent studies use state-level variation in minimum wage timing; high natural experiment density | High |
| DAM | Uses general labor economics econometrics; no named attribution methodology, but the design (cross-state, difference-in-differences) is highly standardized in this specific application | Intermediate |
| SRC | Multiple meta-analyses; direction disputed (Dube et al. find small negative or no effect; Neumark et al. find significant negative effects); systematic reviews find narrow confidence intervals but divergent central estimates | Intermediate |
| RD | Hundreds of studies from independent teams globally; but consistent disagreement on direction between two research programs — not high replication in same-direction terms | Intermediate |

**Classification: Intermediate** (1 High, 3 Intermediate). Predicted: APG primary, Watch B secondary.

---

**Candidate B — Vitamin A Supplementation and Child Mortality**

| Criterion | Assessment | Score |
|---|---|---|
| NEA | Cochrane reviews of multiple RCTs; many independent RCTs across countries | High |
| DAM | RCT methodology for child health interventions is highly standardized; epidemiological attributable fraction methods applied | High |
| SRC | Cochrane review finds consistent direction (VAS reduces all-cause mortality ~24%) with reasonably convergent estimates; though some heterogeneity | High |
| RD | Replicated across dozens of RCTs, multiple countries, multiple research teams; direction very consistent | High |

**Classification: High.** Predicted: APG primary, Watch B minimal.

---

**Candidate C — Microfinance and Poverty Reduction**

| Criterion | Assessment | Score |
|---|---|---|
| NEA | Several RCTs exist (Banerjee/Duflo et al., IPA studies); but external validity challenges and range of outcome measures | Intermediate |
| DAM | Uses development economics RCT methodology; no named attribution toolkit specific to microfinance | Low |
| SRC | Meta-analyses find small positive effects; but earlier observational literature found large effects now not replicated; magnitude inconsistency | Intermediate |
| RD | Multiple RCTs by independent teams; direction roughly consistent but magnitude highly variable; earlier findings not replicated | Intermediate |

**Classification: Intermediate.** Predicted: APG primary, Watch B secondary.

---

**Candidate D — Monetary Policy and Inflation Control**

| Criterion | Assessment | Score |
|---|---|---|
| NEA | Limited natural experiments (Volcker disinflation quasi-experiment; cross-country central bank independence variation); primarily uses macroeconomic modeling | Low |
| DAM | Macroeconomic attribution uses VAR models and DSGE models; methods contested between schools; no broadly accepted causal identification strategy | Low |
| SRC | Systematic reviews find central bank independence and inflation targeting associated with lower inflation, but mechanism and magnitude debated; alternative fiscal theories exist | Low |
| RD | Cross-country evidence exists but confounded by many concurrent factors; replications reach different conclusions depending on period and specification | Low |

**Classification: Low.** Predicted: Watch B primary.

---

## RC-038 Domain Selection

This section is completed AFTER the prospective scores are committed and BEFORE the specific claim is selected.

The most diagnostically valuable RC-038 choice would be:

**Option 1 — Candidate D (Monetary Policy):** Low maturity classification → Predicts Watch B primary. Tests the low end of the gradient without revisiting industrial policy. Different domain, same maturity class.

**Option 2 — Candidate B (Vitamin A):** High maturity classification → Tests the high end without revisiting climate attribution. A health intervention with strong RCT evidence. Would extend the pattern into a second high-maturity domain.

**Option 3 — Candidate A (Minimum Wage):** Intermediate maturity → Tests the intermediate range again (like lead-crime), but in a different domain (labor economics vs. environmental epidemiology). Additional data point at the same level.

The choice depends on repository priority: another intermediate-level test adds less information than a test at an under-tested maturity level. The gradient currently has stronger evidence at intermediate and high levels (two confirmed) and one low-level case. A second low-level test (Candidate D) or a second high-level test (Candidate B) would add more to the gradient's credibility than a third intermediate test.

*This selection decision is left for the repository to make before RC-038 begins.*
