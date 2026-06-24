# RC-045: Returns to Education and Earnings

**Claim:** "Schooling has substantial causal effects on individual earnings — each additional year of education increases wages by approximately 8–10%, a finding replicated across contexts and identification strategies, justifying public investment in education as an economic development priority."

**Sources:** Mincer JA (1974), *Schooling, Experience, and Earnings*; Becker GS (1964), *Human Capital*; Card D (1999), "The Causal Effect of Education on Earnings," *Handbook of Labor Economics*; Psacharopoulos G and Patrinos HA (2018), "Returns to Investment in Education: A Decennial Review of the Global Literature," World Bank Policy Research Working Paper 8402; Angrist JD and Krueger AB (1991), "Does Compulsory School Attendance Affect Schooling and Earnings?", *Quarterly Journal of Economics*; Oreopoulos P (2006), "Estimating Average and Local Average Treatment Effects of Education when Compulsory Schooling Laws Really Matter," *American Economic Review*

**Key formulations:**
- Psacharopoulos and Patrinos (2018): Average private return of 8.8% per year of schooling globally; returns highest in low-income countries (10.4%) and for primary education; consistent across 139 countries over six decades.
- Card (1999): IV estimates of returns to schooling typically in the range of 8–14%, somewhat above OLS estimates, suggesting positive ability bias in OLS is partially offset by downward attenuation bias.
- Oreopoulos (2006): Compulsory schooling reforms in US, Canada, and UK all produce similar positive returns, with one additional year of schooling raising earnings by approximately 12%.
- Mincer (1974): Developed the standard log-linear earnings function that remains the empirical workhorse: log(earnings) = α + β·schooling + γ·experience + δ·experience² + ε.

**Status:** Unresolved
**Date:** 2026-06-24

---

## Cross-Audit Pre-Registration Reference

Prediction on record ([status/rc045-cross-audit-prediction.md](../status/rc045-cross-audit-prediction.md)), committed 2026-06-24 before this audit:

- **Maturity score:** High (NEA=High, DAM=Intermediate-High, SRC=High, RD=High)
- **Institutional authority:** Weak (no IARC/WHO/GBD equivalent; World Bank reviews present but not veto-holding)
- **Gradient prediction:** APG primary, Watch B minimal
- **CMech-001 prediction:** APG primary, Watch B minimal — evidential capacity suppresses Watch B even without centralized institutional authority
- **Alternative A prediction:** Watch B materially active — absent institutional gatekeeping means Watch B persists despite high evidential capacity
- **Alternative A support criterion:** Watch B presence *plausibly sustained by the absence of institutional authority*, not merely Watch B present
- **Stage 5 role:** First audit where CMech-001 and Alternative A generate divergent predictions before evidence review

---

## Why This Claim Matters

Returns to education is the empirical foundation for education policy worldwide. The 8–10% average estimate justifies compulsory schooling laws, subsidized public universities, student loan programs, and development assistance directed toward school construction and teacher training. If the returns are genuine — causal human capital accumulation — then education spending is among the highest-return investments governments can make. If they are primarily signaling artifacts — employers paying for credentials that sort pre-existing ability — then expanded education may not increase aggregate productivity and could represent a zero-sum positional competition among workers.

The policy implications diverge sharply: a signaling world calls for occupational licensing reform and direct skills certification rather than school attendance; a human capital world calls for curriculum reform and quality improvement. Both worlds have the same observed correlation between education and earnings, making the causal mechanism question non-trivial.

---

## Maturity Score

| Criterion | Score | Evidence |
|---|---|---|
| NEA | High | Quarter-of-birth compulsory schooling IV (Angrist-Krueger 1991); UK/Canada/US school-leaving age reforms (Oreopoulos 2006); Indonesia school construction program (Duflo 2001); US state compulsory schooling variation (Acemoglu and Angrist 2000); Vietnam draft lottery; multiple European reforms; RD designs at school-entry age cutoffs. 10+ natural experiments across multiple countries and identification strategies |
| DAM | Intermediate-High | Mincer earnings equation is named, taught, and consistently applied; IV methodology for returns to schooling is a standard named approach; Psacharopoulos/Patrinos apply a named methodology globally for World Bank. No institution applies these methods to produce a GBD-equivalent certification of "education causes human capital accumulation." |
| SRC | High | Consistent positive direction across countries, time periods, and identification strategies; Card (1999), Psacharopoulos and Patrinos (2018), and Heckman et al. systematic reviews find consistent positive returns; no research program disputes that education correlates with earnings; debate is about mechanism and magnitude, not direction |
| RD | High | Replicated by dozens of independent teams using OLS, IV, RD, DiD, and structural approaches; positive returns found in US, Europe, developing countries, historical data; cross-strategy convergence (OLS and IV agree in direction; IV somewhat higher in magnitude) |

**Classification: High** (3 High: NEA, SRC, RD + 1 Intermediate-High: DAM)

---

## Alternative Explanations

**H1 — Pure Signaling (Spence 1973, Arrow 1973)**

Education functions primarily as a signal of pre-existing ability to employers who cannot directly observe productivity. Employers use education as a sorting device: workers who are more able find it less costly to obtain credentials, so completing degrees or achieving more years of schooling credibly signals ability. The wage premium to education reflects not skill acquisition but information revelation.

The strongest version (Caplan 2018, *The Case Against Education*): most of the observed wage return to education is signaling, not human capital. Caplan estimates that signaling accounts for 80% or more of the college premium. His evidence: sheepskin effects (wages jump at graduation years more than in intermediate years), low transferability of academic skills to workplace tasks, high rates of "credential inflation" (workers increasingly need degrees for jobs that formerly required only diplomas), and the absence of plausible channels through which academic content directly improves job performance.

*Watch B character if H1 is the correct alternative:* This is Theoretical (existence) Watch B — a genuine causal-mechanism dispute about whether education causes the observed earnings increase through any human capital channel. However, the pure-signaling view has not displaced the human capital view as the mainstream. The existence of some human capital effect is widely accepted; the debate is about the fraction. H1 at its strongest represents a heterodox challenge, not a dominant competing account.

**H2 — Heterogeneous Returns and LATE Interpretation**

IV estimates identify Local Average Treatment Effects (LATE) — causal returns for compliers, the students who stayed in school longer because of the compulsory schooling law or other instrument. These compliers are often at the margin of educational decisions; their returns may differ systematically from the population-average return. If marginal students have lower returns than high-ability students who would have continued regardless, IV estimates understate average returns. If marginal students benefit more from additional education than high-ability inframarginal students (heterogeneous marginal returns), IV may overstate average returns.

Heckman, Urzúa, and Vytlacil (2006) argue that LATE-based estimates cannot easily be extrapolated to policy-relevant average treatment effects and that the resulting estimates are instrument-specific rather than structural. This complicates the claim that a specific return percentage generalizes to evaluate education investment.

*Watch B character:* This is primarily a methodological dispute about what IV estimates identify and how they should be extrapolated — Methodological Watch B rather than existence-level Theoretical Watch B. The causal claim is accepted; the question is whether the estimates apply to the population of interest.

**H3 — Credential and Institutional Effects**

Much of the education-earnings correlation reflects the institutional structure of labor markets: occupational licensing requirements, credential screens for entry-level hiring, union contracts specifying pay by education level, and degree inflation in hiring practices. The "returns to education" captures a combination of genuine human capital effects, signaling, and regulatory/institutional rents that would not exist in a market with better information.

Black and Smith (2006), Carneiro and Heckman (2002), and others have documented that a substantial portion of the college wage premium is concentrated in specific occupations and industries with credential requirements rather than uniformly across the labor market. This suggests that institutional structure mediates the education-earnings relationship in ways that the Mincer earnings equation does not capture.

*Watch B character:* APG and methodological Watch B. The contribution of institutional effects to the education-earnings relationship is an attribution-precision question — how much of the observed premium is human capital, signaling, and institutional rents? The existence of the relationship is not disputed; its decomposition is contested.

---

## Evidence Supporting the Claim

**The IV literature — the strongest causal evidence:**

The compulsory schooling IV literature provides the most credible causal evidence. Key studies:

*Angrist and Krueger (1991):* Used quarter of birth as an instrument for schooling, exploiting the fact that children born in the first quarter of the year enter school at slightly older ages and can therefore drop out at the legal minimum age with less schooling than children born later. IV estimates: approximately 7–8% return per year of schooling, close to OLS.

*Duflo (2001):* Used the Indonesian government's construction of 61,000 primary schools between 1973 and 1978 as exogenous variation in schooling access. Children in high-construction regions received more schooling; IV estimates yield approximately 6.8–10.6% returns per year of schooling in a developing country context, consistent with the global literature.

*Oreopoulos (2006):* Pooled UK, Canadian, and US data on compulsory schooling reforms to estimate returns of approximately 12% per year, with no evidence that the effects differ substantially across countries with different institutional structures.

The cross-study and cross-country consistency of IV estimates in the 6–14% range, using genuinely different instruments and institutional contexts, is strong evidence that the causal return to education is positive and substantial.

**Global returns consistency (Psacharopoulos and Patrinos 2018):**

Based on 1,120 estimates from 139 countries covering 1950–2014, average private returns to schooling are 8.8% globally — 10.4% in low-income countries, 8.1% in middle-income, and 6.9% in high-income. The consistency across settings with radically different institutional structures, labor market designs, and educational systems makes it difficult to attribute the entire premium to any single institutional artifact.

**Sheepskin effects — evidence against pure signaling:**

Signaling theory (in its strongest form) predicts that intermediate years of schooling between diploma thresholds add little to wages because they don't resolve the sorting problem. The evidence on sheepskin effects is mixed: there is an earnings jump at graduation relative to adjacent non-graduation years, consistent with signaling, but returns to intermediate years are also positive and substantial, more consistent with human capital accumulation. The evidence on sheepskin effects weakens but does not eliminate the human capital interpretation.

---

## Evidence Against / Creating Doubt

**LATE and external validity concerns:**

The IV estimates that provide the strongest causal evidence also have the sharpest external validity limitations. Compulsory schooling IVs identify returns for students at the margin of minimum schooling thresholds — often students from lower-income families, in lower-quality schools, who would have dropped out absent the law. Whether these returns extrapolate to higher levels of education (college, graduate school) or to students not at the compulsory schooling margin is an unresolved question.

Oreopoulos and Salvanes (2011) note that IV estimates may overstate returns if they identify high-value vocational pathways enabled by minimum additional years. Heckman et al. (2006) argue more forcefully that LATE-based policy advice is structurally limited — the instrument answers "what is the return for the marginal student affected by this law?" not "what would be the return to expanding education more broadly?"

**The Spence-Caplan heterodox challenge:**

Caplan (2018) argues for an 80% signaling share using cross-national evidence: if education primarily builds skills, countries should see substantial productivity returns from educational expansion; the mixed cross-country evidence on education and growth suggests the aggregate return is much lower than individual-level Mincer estimates imply. The macro-micro discrepancy — individual returns 8–10%, aggregate growth effects smaller or inconsistent — is an important puzzle.

Lochner and Moretti (2004) find social returns to education beyond private returns through crime reduction, supporting the human capital view. But critics note this could reflect signaling effects on employment stability rather than skill acquisition per se.

**The signaling-human capital separation problem:**

The most fundamental limitation: it is very difficult to separately identify signaling and human capital components of education in observational or even IV data, because both predict positive private returns to education and because natural experiments that affect education also affect the signaling environment. Tests that try to exploit variation in employer information quality (Lange 2007) or variation in credential recognition across contexts have been attempted but haven't produced consensus estimates of the signaling fraction.

---

## Missing Evidence

**Direct experimental evidence on skills vs. credentials:** A true test of signaling vs. human capital requires separately varying skills acquired and credentials awarded. Employer learning studies (Altonji and Pierret 2001) track whether the wage return to measured ability increases with tenure (consistent with signaling dissipating over time), with mixed results. A randomized study directly varying credential receipt and skill acquisition would be definitive but is not feasible at scale.

**Macro returns to educational expansion:** Individual Mincer returns of 8–10% do not necessarily imply that aggregate educational expansion produces comparable social returns. Cross-country evidence on education and economic growth is mixed (Pritchett 2001 "Where has all the education gone?"), partly because quality rather than quantity of schooling matters enormously. A credible macro-level causal estimate of the social return to educational expansion would help anchor whether the individual-level IV estimates are picking up true productivity effects or primarily signaling and institutional effects.

---

## Current Status and Confidence

**Status: Unresolved**

The causal effect of education on individual earnings is among the better-established findings in economics. The natural experiment evidence is extensive, methodologically sophisticated, and cross-nationally consistent. The direction and approximate magnitude (positive, roughly 8–10% per year) are not seriously in dispute among mainstream economists. What is disputed is the mechanism (human capital vs. signaling vs. institutional) and the policy implications (expand access vs. reform credentials vs. improve quality).

---

## Watch Item Assessment

**APG — Primary: Confirmed.**

The live frontier among researchers who accept that education causes earnings increases is contribution-share and magnitude questions:
- What fraction of the education premium reflects human capital vs. signaling vs. institutional rents?
- Do IV estimates correctly identify effects that generalize beyond marginal compliers?
- How much of the return is specific to credential thresholds (sheepskin) vs. continuous year effects?
- What is the social vs. private return divergence, and how should it affect policy?

These are classic APG-structure disputes: the causal relationship is accepted; the attribution shares among mechanisms and the magnitude applicable to policy are contested.

**Watch B — character determination:**

*Existence-level Theoretical Watch B — Largely Absent.*

The mainstream economics literature does not contain an active research program that disputes whether education causes earnings increases. The Caplan/Spence signaling challenge is heterodox but does not constitute a live existence-level dispute in the sense of competing research programs challenging the causal direction. Researchers who accept the signaling view still accept that education causes the earnings premium — they dispute the mechanism (signaling is still a causal relationship between education and earnings; it is not a denial that education causes earnings). A pure human capital skeptic who claimed education *does not* cause earnings would be arguing against the IV evidence, which is strong enough to have substantially settled the existence question.

*Methodological Watch B — Present but secondary.*

The LATE/external validity concern is a genuine methodological dispute within an accepted causal framework: different IV studies identify different LATE parameters; whether those parameters are relevant to policy decisions is contested; the magnitude applicable beyond the compulsory-schooling margin is uncertain. This is Methodological Watch B: the causal existence is accepted, the methodological concern is about whether the available estimates correctly measure the policy-relevant effect.

*Directional Watch B — Absent.*

No active research program disputes that education has a positive effect on earnings. The signaling debate accepts the positive direction; it disputes the mechanism.

**Counterfactual Unavailability — Absent: Confirmed.** IV literature explicitly constructs counterfactual non-education outcomes.

---

## Mechanism Competition Assessment — Stage 5 Verdict

**CMech-001 prediction: Confirmed.**

Watch B is minimal (primarily methodological and secondary) despite weak centralized institutional authority. The returns-to-education literature has no IARC, no GBD, no WHO formal guideline certifying that "education causes human capital accumulation." Yet existence-level Theoretical Watch B is largely absent. The causal direction is accepted by mainstream researchers. The frontier has moved to APG-structure disputes about contribution shares and mechanism decomposition.

This is difficult to explain under Alternative A: if institutional gatekeeping were necessary to suppress Watch B, the absence of a centralized gatekeeping authority in the economics profession should leave Watch B more active than in IARC/GBD-backed domains. Instead, Watch B is minimal — comparable to RC-039 (Vitamin A, High maturity, institutional authority present) and RC-036 (Climate Attribution, institutional authority high).

**Alternative A: Pressured — not eliminated, but pressured.**

Alternative A predicted Watch B would remain materially active in returns to education due to absent institutional authority. It did not. The Watch B that is present (Methodological) is the form CMech-001 predicts DAM-equivalent methodology would produce — not the form Alternative A predicted (Theoretical existence-level, sustained by absence of certification structures).

The remaining space for Alternative A: one could argue that the IV literature itself, combined with top-journal publication norms in economics, functions as a *de facto* gatekeeping mechanism even without a formal WHO-equivalent. On this reading, the prestige hierarchy of economics (AER, QJE, JPE, NBER) provides the effective gate that prevents Theoretical Watch B from being sustained. If so, Alternative A has not been truly tested — it merely encountered a different institutional structure than the one its operationalization assumed.

This is a genuine interpretive residual. The pre-registration specified that Alternative A support requires Watch B "plausibly sustained by absence of institutional authority" — not merely Watch B present. The absence of Watch B in returns to education is therefore more damaging to Alternative A than a straightforward Watch B presence would have been. But the residual interpretation is available and would need to be addressed by a domain with more genuinely fragmented prestige infrastructure.

---

## Ledger Entry

**Stage 5 verdict:** CMech-001 cleared the first Stage 5 test. Evidential capacity (strong IV literature, named methodological framework, extensive replication) appears sufficient to suppress existence-level Watch B even without centralized institutional authority. Alternative A's prediction (Watch B materially active) did not materialize.

**Alternative A status:** Pressured, not eliminated. The domain's prestige infrastructure (top economics journals, NBER) may provide some institutional function analogous to gatekeeping, preventing clean separation. Alternative A retains a residual interpretation path but now carries an empirical burden it did not face before RC-045.

**Alternative B:** No new evidence. The returns-to-education research program was not clearly founded before or after causal existence was established. Mincer (1974) and Becker (1964) were engaged in causal theorizing about human capital; the IV methodology came later. The history does not clearly identify whether the program selected into measurement without testing existence.

**Anti-compression:** One Stage 5 test does not validate CMech-001. It puts Alternative A under first empirical pressure. The gap between "passed one test" and "validated" remains substantial.
