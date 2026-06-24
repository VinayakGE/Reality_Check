# RSQ-002: The Domain-Maturity Gradient — Candidate Mechanism

**Date:** 2026-06-24
**Last updated:** 2026-06-24 (Post-RC-045: Alternative A revised from formal-certification to prestige-coordination version; new DAM/prestige-coordination correlation warning; Cycle 8 entry criterion specified before RC-046)
**Type:** Repository Structure Question — Mechanism Specification
**Status:** Stage 4B complete; Stage 5 entry conditions specified; mechanism competition not yet started

This document does for the domain-maturity gradient what RSQ-001 did for promotion logic: takes a confirmed pattern and asks what process generates it. The mechanism is a candidate, not a promoted object. The wound conditions in this document are pre-registered before RC-041 is selected.

**Analogy to RSQ-001:** RSQ-001 found that the repository was applying promotion logic without specifying it. The candidate criteria were extracted from prior decisions and pre-registered before the APG promotion decision. Outcome: useful + incomplete.

RSQ-002 finds that the repository has confirmed a gradient regularity without explaining it. The candidate mechanism is extracted from the confirmed pattern and pre-registered before mechanism-directed audits begin. The same outcome (useful + incomplete) is the expected result, not a failure condition.

---

## The Confirmed Regularity

Six audits across two eras have produced the following pattern:

| Maturity | Observed primary object |
|---|---|
| Low (RC-035, RC-038) | Watch B |
| Intermediate (RC-037, RC-040) | APG |
| High (RC-036, RC-039) | APG |

Era 2 (RC-038, RC-039, RC-040) was conducted under independently committed maturity scores, removing the circularity risk identified by OQ-Maturity.

**What has been established:** The gradient exists and survives independent measurement across six domains from genuinely different methodological traditions.

**What has not been established:** Why it occurs.

---

## The Distinction: Markers vs. Mechanism

The four operationalization criteria (NEA, DAM, SRC, RD) are observable markers of literature ecology. They were designed to assess maturity before reading claim evidence. They predict object dominance reliably.

They are not the mechanism. They describe where the gradient appears. The mechanism is what produces it.

The distinction is critical because a mechanism generates predictions that markers alone do not. If the operationalization criteria were the mechanism, then every domain that scores High on NEA, DAM, SRC, and RD would show APG dominance for the same reason. But two domains could have the same composite score through different criterion profiles and still behave differently at the object level — if the mechanism operates through specific criteria rather than through the composite.

---

## The Candidate Mechanism

**Candidate mechanism (CMech-001): Causal-identification capacity determines the feasibility of Watch B as an active research frontier.**

*Process account:*

Domains accumulate causal-identification capacity over time — the methodological ability to establish, with defensible evidence, that a proposed cause had some role in producing an observed outcome. This capacity is measured imperfectly by NEA (natural experiments establish causal presence directly), DAM (named methods codify causal identification in domain-specific form), SRC (meta-analyses aggregate causal-direction evidence), and RD (replication across independent teams confirms causal direction is not method-specific).

As causal-identification capacity increases, causal-role disputes become increasingly difficult to sustain. A researcher who asserts "X did not cause Y" in a domain with strong natural experiments and replicated meta-analyses must contend with an accumulated evidentiary burden that requires either methodological objection (the natural experiments are invalid) or scope restriction (X didn't cause Y in this specific context). Both responses are possible but increasingly costly as identification capacity grows.

Once causal-role uncertainty falls below a functional threshold — not zero, but below the level at which "did it cause?" sustains an active research frontier — the live dispute shifts from Watch B ("did the credited cause have any causal role?") to APG ("how much of the outcome belongs to the accepted cause?").

**The threshold is not sharp.** Intermediate-maturity domains show both Watch B and APG present because causal-identification capacity has established causal presence for part of the research community but not all. The threshold has been crossed for some researchers (who argue about contribution shares) but not others (who still contest causal role). This is exactly the structure observed in RC-037 and RC-040: both Watch B and APG present, APG primary, Watch B secondary.

---

## What CMech-001 Predicts Beyond the Regularity

If the composite maturity score were the mechanism rather than a marker, then composite score alone would predict object dominance. CMech-001 predicts something more specific:

**Prediction 1 — Criterion interaction:** Domains with high NEA but low DAM (natural experiments exist but no named attribution methodology) should show APG as primary — because natural experiments establish causal presence — but Watch B should be weaker than in Low-DAM, Low-NEA domains. NEA does the work of suppressing Watch B; DAM amplifies it but is not necessary.

**Prediction 2 — Criterion non-equivalence:** Not all criteria contribute equally to Watch B suppression. NEA (natural experiments) and DAM (named attribution methods) directly establish causal presence. SRC and RD measure whether those methods have produced consensus — they are downstream consequences. CMech-001 predicts that domains where NEA or DAM is High should show Watch B suppression even when SRC and RD are not High.

**Prediction 3 — Developmental trajectory:** Every current APG-dominant domain should have Watch B as its historical prior. CMech-001 implies that domains develop through a Watch B phase before reaching APG dominance — they cannot skip it, because APG's activation condition requires that causal role be established first. This is testable retroactively within specific domains.

**Prediction 4 — Watch B persistence after transitional evidence:** In domains where a single major study established causal presence (rather than accumulated replication), Watch B should remain more active as a secondary object than in domains where many independent teams have replicated causal direction. The mechanism predicts that Watch B's residual strength after APG becomes primary correlates with how much of the causal-identification burden was carried by a single study vs. distributed replication. RC-037 (lead-crime: Watch B secondary, single major natural experiment) vs. RC-036 (climate attribution: Watch B minimal, 100+ attribution studies) is consistent with this.

These predictions distinguish CMech-001 from the composite-score regularity. They generate audit designs that could falsify the mechanism while confirming the regularity.

---

## Wound Conditions

A wound condition is an observation that reduces confidence in CMech-001 without necessarily eliminating it. Unlike the gradient regularity (which requires three or more out-of-pattern observations to challenge), the mechanism is a causal claim about a process — a single well-specified counter-case can wound it.

**Wound 1 — High identification capacity, Watch B primary:**
A domain that scores High on NEA and DAM (strong natural experiments and a named attribution methodology) but shows Watch B as the primary epistemic object. This would mean causal-identification capacity does not suppress Watch B as predicted. The mechanism's core claim fails.

*Example type:* A domain where a named attribution methodology exists (DAM = High) and natural experiments exist (NEA = High) but researchers still actively contest whether the credited cause had any causal role.

**Wound 2 — Low identification capacity, APG primary:**
A domain that scores Low on NEA and DAM (few or no natural experiments, no named attribution methodology) but shows APG as the primary epistemic object. This would mean APG can be the live frontier without causal-identification capacity having established causal role — inconsistent with APG's activation condition.

*Example type:* A domain where contribution-share disputes dominate despite the absence of methods that would establish causal presence. Note: this would also require re-examining whether APG was correctly identified — the mechanism's wound condition and the object identification's accuracy are not independent.

**Wound 3 — Criterion non-interaction (CMech-001's differential prediction fails):**
If a domain with High NEA but Low DAM shows the same Watch B strength as a domain with Low NEA and Low DAM, the mechanism's Prediction 1 is wrong. The criteria would function only as a composite — not as independent contributors to causal-identification capacity. This does not wound the gradient regularity but wounds CMech-001 specifically.

**Wound 4 — Non-developmental domains:**
If a currently APG-dominant domain has no historical Watch B phase — causal role was immediately accepted without a period of active contestation — CMech-001's developmental trajectory prediction fails. This would require historical examination of specific domains rather than a new audit.

---

## What Would Not Wound CMech-001

**Another gradient confirmation at the composite level:** A seventh correct prediction (High maturity → APG, or Low maturity → Watch B) adds evidence for the regularity but adds no evidence about the mechanism beyond what six confirmations already established. Continued replication at the composite level does not help adjudicate between CMech-001 and alternative mechanisms.

**A prediction failure at the composite level:** This would wound the gradient regularity (and the operationalization criteria), but it would not directly wound the mechanism unless the failure was attributable to criterion-level evidence consistent with Wound 1 or Wound 2.

---

## What CMech-001 Does Not Explain

**Why the threshold is where it is:** CMech-001 describes a threshold below which Watch B becomes unsustainable. It does not specify what determines the threshold level or why some domains cross it with fewer confirmations than others.

**Alternative mechanisms not excluded:** Two alternative mechanisms are consistent with the confirmed gradient:

*Alternative A — Prestige-driven consensus:* High-maturity domains have more prestigious publication venues, higher-profile researchers, and more institutional endorsement (IPCC, Cochrane, WHO). Watch B may recede not because evidence establishes causal role but because the institutional infrastructure of the domain prevents Watch B claims from being published or taken seriously. CMech-001 and Alternative A make similar predictions at the composite level but different predictions at the process level.

*Alternative B — Selection into measurement:* Domains with high NEA and DAM may attract research programs that presuppose causal role (they design studies to measure magnitudes, not to test causal presence). Watch B would then be absent not because it was resolved but because the research program never engaged it. This would mean APG's apparent dominance is an artifact of research program selection rather than genuine evidence accumulation.

Both alternatives are viable. CMech-001 is not uniquely supported by current evidence. It is the most parsimonious candidate, but parsimonious candidates have been wrong before.

---

## Methodological Risk: Post-Hoc Construction

CMech-001 was constructed after observing six correct gradient predictions. This is a significant risk. The mechanism was designed to fit the confirmed pattern; its fit is therefore not evidence for it.

The wound conditions in this document create the only available safeguard: if CMech-001 generates differential predictions (Predictions 1–4) that the composite-score regularity does not generate, and if those differential predictions are tested and hold, CMech-001 has earned some evidence beyond its retroactive fit.

Until such tests are run, CMech-001 should be treated as a candidate with high post-hoc risk, not as a mechanism with empirical support.

---

## Resolution Path

**Step 1 (complete):** Document the confirmed regularity and the mechanism gap at Checkpoint #009.

**Step 2 (this document):** Pre-register CMech-001 and wound conditions before RC-041 is selected.

**Step 3:** Select RC-041 to test a differential prediction — not a composite-score replication, but a criterion-interaction or intensity-gradient case. Candidate types:
- Domain with High NEA, Low DAM (tests Prediction 1 and Prediction 2)
- Domain with established causal role through a single major study (tests Prediction 4 — Watch B secondary strength)
- Historical examination within a known APG-dominant domain for prior Watch B phase (tests Prediction 3)

**Step 4:** After RC-041, assess CMech-001 against Wound conditions. Record: wounds inflicted, wounds avoided, status of differential predictions.

**Step 5:** Update or replace CMech-001 based on evidence. CMech-001 is not the last candidate mechanism; it is the first one committed to a testable form.

---

## RSQ-002 Status

RSQ-002 is open. The candidate mechanism is committed. Wound conditions are pre-registered.

---

## RC-041 Assessment — First Discriminating Observation (added 2026-06-24)

RC-041 (Air Pollution Mortality) produced the first CMech-001 differential observation — a result that the composite-score regularity alone did not predict.

**Level 1 (composite regularity):** Confirmed. Intermediate maturity → APG primary. Matches RC-037 and RC-040.

**Level 2 (CMech-001 differential):** Partially confirmed, with a stronger result than predicted. Watch B did not merely become weaker — it changed form.

### Watch B Type Table (as of RC-041)

| Domain | Composite Maturity | DAM Score | Watch B Character |
|---|---|---|---|
| RC-035 Industrial Policy | Low | Low | Theoretical — competing causal explanations (markets vs. state) |
| RC-037 Lead-Crime | Intermediate | Low | Theoretical — competing complete mechanisms (abortion, policing) |
| RC-038 Monetary Policy | Low | Low | Theoretical — competing causal structures (fiscal theory, oil prices) |
| RC-040 Minimum Wage | Intermediate | Intermediate | Directional — research programs dispute sign of effect |
| RC-041 Air Pollution | Intermediate | High | Methodological — confounding concern; no competing causal theory |
| RC-036 Climate Attribution | High | High | Minimal — residual only |
| RC-039 Vitamin A | High | High | Minimal — DEVTA vs. Cochrane is precision dispute, not causal-role dispute |

The table reveals a pattern: Watch B character tracks DAM score more than composite maturity classification. Low DAM → theoretical Watch B. Intermediate DAM → directional Watch B. High DAM → methodological Watch B or absent.

### The Watch B Transformation Hypothesis (candidate refinement — 1 observation)

RC-041 suggests CMech-001 may need refinement. The original mechanism claim was:

> As causal-identification capacity increases, Watch B recedes.

The RC-041 observation suggests a stronger version:

> As causal-identification capacity increases — specifically DAM — Watch B does not merely recede. It transforms. The content of the dispute changes from "did X cause Y?" (theoretical) to "does Y correlate with confounders?" (methodological).

This is a candidate refinement, not a new promoted object. It has one supporting observation (RC-041) and is vulnerable to alternative explanations:
- Air pollution may have unusually clear biological mechanisms that suppress theoretical Watch B independently of DAM
- The IARC Group 1 classification process may be confounded with other features of the domain that suppress theoretical Watch B

**Status:** Candidate refinement. One instance. Anti-compression constraint applies.

**Activation condition for strengthening:** A domain with High NEA but Low DAM that shows theoretical Watch B — demonstrating that natural experiments alone do not transform Watch B type without DAM certification. This would confirm that DAM specifically drives the transformation, not NEA.

### Prediction 2 Update

CMech-001's Prediction 2 (criteria are non-equivalent) is now partially tested. The hypothesis was that DAM and SRC suppress Watch B independently of NEA. RC-041 provided one observation consistent with this.

The next test: a domain with High NEA and Low DAM. If Watch B remains theoretical in that domain despite strong natural experiment evidence, DAM (not NEA) is confirmed as the Watch B-transformation driver. If Watch B is methodological (as in RC-041) despite Low DAM, then NEA is sufficient for the transformation and CMech-001's Prediction 2 fails.

**RC-042 selection criterion:** High NEA + Low DAM domain. Specific candidates:
- **Incarceration and crime reduction:** Strong natural experiment literature (Levitt 1996 prison litigation IV, Italian pardons, California realignment, mandatory sentencing variation). No named incarceration attribution methodology. DAM = Low.
- **Immigration and labor markets:** Mariel boatlift (Card 1990), EU Eastern enlargement natural experiments, refugee resettlement lotteries, E-Verify variation. Standard econometrics borrowed; no named immigration-attribution methodology. DAM = Low.
- **Returns to education:** Compulsory schooling natural experiments (Angrist-Krueger), school construction RDs, Vietnam draft lottery. Econometric methods well-established but not domain-specific named attribution toolkit. DAM = Intermediate (borderline).

Incarceration is the cleanest High NEA + Low DAM candidate. The Watch B in that domain is expected to be theoretical (does marginal incarceration reduce crime or is it criminogenic at current levels?) — which is what the mechanism test requires.

---

## RC-042 Assessment — Criterion-Separation Evidence (added 2026-06-24)

RC-042 (Incarceration/Crime Reduction) produced the result the CMech-001 test needed: theoretical Watch B persisted despite High NEA. The Levitt (1996) prison litigation IV and Italian pardons are among the most celebrated natural experiments in applied econometrics — yet Watch B remained theoretical in character, because the criminogenic-effects mechanism operates over timescales and pathways that the natural experiments do not identify.

**Watch B Type Table (updated through RC-042):**

| Domain | Composite | NEA | DAM | Watch B Character |
|---|---|---|---|---|
| RC-035 Industrial Policy | Low | Low | Low | Theoretical |
| RC-037 Lead-Crime | Intermediate | Intermediate | Low | Theoretical |
| RC-038 Monetary Policy | Low | Low | Low | Theoretical |
| RC-040 Minimum Wage | Intermediate | High | Intermediate | Directional |
| RC-042 Incarceration | Low | High | Low | Theoretical |
| RC-041 Air Pollution | Intermediate | Intermediate | High | Methodological |
| RC-036 Climate Attribution | High | High | High | Minimal |
| RC-039 Vitamin A | High | High | High | Minimal |

The criterion-separation pattern is now visible: Watch B character tracks DAM, not NEA. RC-042 is the direct comparison case — same High NEA as RC-040 (Minimum Wage), but Low DAM instead of Intermediate DAM, and Theoretical Watch B instead of Directional Watch B.

**Key observation:** A natural experiment that identifies one causal pathway does not suppress the theoretical dispute about net effects when a competing pathway is live and unaccounted for. This explains the RC-042 result mechanistically: Levitt's IV identified the incapacitation pathway; it did not identify the criminogenic-effects pathway; therefore the theoretical dispute about net effect remained active.

---

## CMech-001 Candidate Revision — NEA/DAM Functional Distinction (added 2026-06-24)

The accumulated evidence from RC-041 and RC-042 suggests CMech-001 should be revised from a composite-capacity claim to a functional-distinction claim.

**CMech-001 (original):**
> As causal-identification capacity increases (jointly measured by NEA, DAM, SRC, RD), Watch B recedes and may change form.

**CMech-001 Revised (candidate — 2 observations, pre-compression):**
> NEA and DAM perform different epistemic jobs that are not interchangeable:
>
> - **NEA** answers: *Can the causal pathway from X to Y be identified?* It establishes that a causal mechanism exists and is measurable through some identification strategy. High NEA means the field has natural experiments that isolate at least one causal pathway.
>
> - **DAM** answers: *How are multiple competing pathways combined into a net causal attribution?* It provides a formal integration methodology that produces a net effect estimate by accounting for competing mechanisms, adjusting for counterfactual exposure levels, and certifying which pathways count toward the total attribution.
>
> Watch B's transformation from Theoretical → Directional → Methodological is driven by DAM, not NEA, because:
> - Theoretical Watch B is active when competing mechanisms are unaccounted for in any formal attribution framework — regardless of how many natural experiments exist for individual pathways
> - DAM transforms Watch B by formally integrating competing pathways; the theoretical dispute becomes methodological once the field has agreed on how to combine pathways into a net attribution
> - NEA alone cannot transform Watch B when multiple competing mechanisms exist, because identifying one pathway says nothing about the net effect of all pathways combined

**Status of the revision:** Candidate. Two observations supporting the functional distinction (RC-041 and RC-042 form a direct comparison: same NEA, different DAM, different Watch B type). Anti-compression constraint: two observations is not a pattern. A third observation would be the Watch B Transformation Hypothesis's second supporting case.

**Post-hoc construction risk:** The functional distinction was formulated after seeing RC-041 and RC-042. It fits the data by design. It needs to generate predictions that the data cannot retro-fit — specifically, it predicts the absence of cases where High DAM co-exists with Theoretical Watch B.

---

## Revised Wound Conditions (as of RC-042)

The original wound conditions (Wound 1–4) remain active. Two new wound conditions are added following the CMech-001 candidate revision:

**Wound 5 — Low DAM + Methodological Watch B:**
A domain with Low or Intermediate DAM where Watch B is methodological in character (confounding concern, no competing causal theory). This would mean DAM is not necessary for Watch B transformation — something else suppressed theoretical Watch B without a named attribution methodology.

**Wound 6 — High DAM + Theoretical Watch B:**
A domain with High DAM where Watch B remains theoretical — competing causal mechanisms are active despite a named attribution methodology that should formally integrate them. This is the most direct wound to the revised CMech-001. If IARC-style classification or GBD-style burden methodology coexists with a live theoretical dispute about causal mechanism, then DAM does not drive the transformation as claimed.

**Severity ranking of wounds:**
- Wound 6 is the most severe — directly contradicts the mechanism's core claim
- Wound 5 is moderately severe — introduces an alternative driver but doesn't eliminate DAM as a factor
- Wounds 1–4 remain as originally specified

---

## Phase Characterization — Mechanism Decomposition

After RC-041 and RC-042, RSQ-002 has moved from mechanism-discovery phase to mechanism-decomposition phase. The questions have changed:

| Phase | Question |
|---|---|
| Mechanism-discovery (before RC-041) | Does a mechanism exist? What is CMech-001? |
| Mechanism-decomposition (RC-041 onwards) | Which components of CMech-001 carry the explanatory weight? Are NEA and DAM doing different things? |

This is a more informative frontier than gradient replication. The gradient regularity (Low → Watch B, High → APG) is a confirmed pattern; what the repository is now asking is whether the criteria that predict it are doing different explanatory work. That question is falsifiable at the criterion level rather than only at the composite level.

**Next highest-value test:** A domain where High DAM and Low NEA co-exist — the reverse of RC-042. If such a domain shows Methodological Watch B (as the revised CMech-001 predicts), the functional distinction gains a third supporting observation. If it shows Theoretical Watch B, DAM alone is insufficient without the pathway-identification NEA provides, and the revised CMech-001 requires further revision.

**Candidate:** Epidemiological causal attribution for dietary factors (e.g., saturated fat and cardiovascular disease, or salt and hypertension) — domains where formal burden estimation methods (DAM = High, similar to GBD) exist but natural experiments are scarce and mostly of poor quality (NEA = Low to Intermediate).

---

## RC-043 Assessment — Wound 6 Partial Result and CMech-001 Scope Complication (added 2026-06-24)

RC-043 (Dietary Sodium and Cardiovascular Mortality) was selected as the Wound 6 test: does High DAM coexist with Theoretical Watch B? The result was more complex than a binary wound or confirmation.

**Watch B character observed:** Theoretical (optimum sub-type) AND Methodological simultaneously.

The PURE study (Mente et al. 2016, NEJM; 103,570 participants, 18 countries, multiple 24-hour urine collections) found a J-shaped association with cardiovascular mortality, with the lowest risk in the 3–6g/day sodium range — above the WHO guideline of <2g/day. This generates two simultaneous Watch B forms:

- **Watch B Theoretical (optimum):** The net causal direction of sodium reduction from 3.5g/day (current Western intake) to <2g/day is genuinely contested. RAAS activation at low sodium provides a competing mechanistic pathway. Whether the WHO guideline places populations in a beneficial or harmful range is a live theoretical dispute.
- **Watch B Methodological:** PURE critics argue the J-curve reflects measurement error and reverse causation, not genuine biology. This is a confounding concern within an accepted causal framework (sodium reduction is beneficial; the J-curve is an artifact).

Both forms are live. The field has not resolved which account of PURE is correct.

**Wound 6 assessment — Partial.**

Wound 6 requires: High DAM + Theoretical Watch B. Theoretical Watch B is present. But the Theoretical Watch B is specifically about the optimal threshold level, not about whether sodium causes cardiovascular harm at any level. The GBD comparative risk assessment and WHO formal guidelines appear to have suppressed the existence-level Theoretical dispute while leaving the optimum-level dispute open — and potentially sharpening it by specifying a precise threshold that PURE then challenged at that exact level.

Wound 6 is partially inflicted rather than cleanly inflicted or avoided.

### Watch B Type Table (updated through RC-043)

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

RC-043 introduces a Watch B sub-type not previously present in the table: **Theoretical (optimum)**. The sub-type is distinct from Theoretical (existence): it accepts that the causal mechanism exists at some level but disputes whether the policy-relevant intervention is in the direction of benefit or harm at the specified dose.

**Status:** One instance. Anti-compression applies. The sub-type is a candidate distinction, not a promoted taxonomy entry.

---

### CMech-001 Scope Refinement Required

The partial Wound 6 result forces a scope qualification on the revised CMech-001 candidate.

**Revised CMech-001 (before RC-043):** DAM transforms Watch B by formally integrating competing pathways. High DAM should suppress Theoretical Watch B because the attribution methodology accounts for competing mechanisms and produces a net attribution.

**RC-043 complication:** High DAM (GBD comparative risk assessment) suppressed the existence-level Theoretical dispute (is sodium harmful at any level?) but did not suppress the optimum-level Theoretical dispute (is sodium reduction from 3.5g to <2g/day net beneficial?). DAM specifies the attribution methodology for computing the burden given a TMREL; it does not resolve where the TMREL belongs.

**Proposed scope refinement (candidate — one observation):**

> DAM resolves the *existence question*: Does X cause harm at some level? A named attribution methodology that produces quantitative burden estimates presupposes a positive answer and encodes it in institutional form (GBD, IARC classification). This suppresses existence-level Theoretical Watch B.
>
> DAM does not resolve the *optimum question*: What is the best level of X? Attribution methodologies require a TMREL (theoretical minimum risk exposure level) as an input; they do not derive the TMREL from first principles. The optimum-level question — where to set the policy threshold — generates its own Theoretical Watch B that DAM does not address even when it resolves the existence question.

**Status of the refinement:** Candidate. One observation (RC-043). Anti-compression applies. A second domain with High DAM + Theoretical (optimum) Watch B would constitute the Watch B Transformation Hypothesis's first complication with replication.

**What would falsify the refinement:** A domain with High DAM where the optimum-level Theoretical Watch B is also absent — the TMREL or policy threshold is not contested despite active natural experiments or conflicting observational evidence at low exposure levels. This would suggest that something besides DAM scope explains the RC-043 result.

---

### Phase Update

RSQ-002 has entered a new sub-phase: **mechanism scope delimitation**. The questions have shifted again:

| Sub-phase | Question |
|---|---|
| Mechanism-discovery (before RC-041) | Does a mechanism exist? What is CMech-001? |
| Mechanism-decomposition (RC-041–RC-042) | Which criteria carry the explanatory weight? NEA vs. DAM? |
| Mechanism scope delimitation (RC-043 onwards) | What questions does the mechanism actually answer? What is outside its scope? |

The transition from decomposition to scope delimitation is significant. In decomposition, we learned that DAM and NEA do different things. In scope delimitation, we are learning that DAM itself has bounded scope — it resolves some Watch B forms (existence-level) and not others (optimum-level). This is a more nuanced finding than Wound 6 either inflicted or avoided; it suggests the mechanism is real but partial.

**Next highest-value test options:**

1. **Second High DAM + optimum-level contested domain:** Confirms or disconfirms the scope refinement's generalizability. Candidate: saturated fat and cardiovascular disease (High DAM via GBD; optimum intake contested; existence-level dispute partially suppressed but dietary guidelines at saturated fat thresholds contested).

2. **High DAM domain where TMREL is uncontested:** Tests whether the optimum-level Watch B in RC-043 is domain-specific or a general feature of all High DAM domains with a specified policy threshold. If such a domain shows Methodological Watch B without the optimum sub-type, the scope refinement's first condition (TMREL specification creates optimum-level Watch B) needs further specification.

3. **Low DAM + optimum-level contested domain:** If such a domain shows Theoretical (existence) Watch B but not Theoretical (optimum) Watch B, it would confirm that optimum-level disputes require the existence question to be settled first — i.e., optimum-level Watch B is a downstream product of existence-level Watch B resolution, not an independent category.

---

## RC-044 Assessment — Discriminant Result and Scope Boundary Survives (added 2026-06-24)

RC-044 (Alcohol Consumption and Mortality) was designed as the discriminant for RC-043's Wound 6 partial result. The specific question: does Theoretical (optimum) Watch B persist despite GBD's explicit TMREL=0 defense?

**Watch B character observed:** Theoretical (optimum) + Methodological simultaneously — identical to RC-043.

**Discriminant function assessment:**

The GBD 2018 analysis (Griswold et al., *The Lancet*) explicitly:
1. Modeled sick-quitter contamination in the abstainer reference category
2. Corrected for this contamination
3. Concluded that after correction, no protective effect at any consumption level is detectable
4. Set TMREL=0 as the substantive biological conclusion, not merely as a conservative methodological default

Despite this, Theoretical (optimum) Watch B persisted among researchers who dispute not GBD's methodology but its biological premise — specifically, that the HDL-protective mechanism is real and that MR evidence is insufficient to eliminate it.

**Interpretation B is supported:** GBD explicitly engaged the optimum question and took a defended position. Theoretical (optimum) Watch B persisted anyway among researchers who dispute the biological premises of that position. The scope boundary is not an artifact of incomplete DAM engagement — it reflects that DAM can formalize a position on the optimum question but cannot resolve the dispute when the disagreement is about the underlying biology, not about whether the methodology correctly implements agreed premises.

**Interpretation A is partially supported:** GBD's explicit engagement did transform Watch B for the subset of researchers who accepted DAM's sick-quitter correction as valid — for them, the Watch B became Methodological (GBD addressed the confounding; residual J-curve proponents are implementing the correction incorrectly). This confirms that explicit DAM engagement does affect Watch B character for part of the research community.

**Net result:** The scope boundary is real but its location is more precise than the RC-043 reading suggested. DAM cannot suppress Theoretical (optimum) Watch B when the dispute is about the *biological premises* generating the optimum. DAM can transform Theoretical (optimum) Watch B into Methodological Watch B for the subset of researchers whose dispute is about *implementation of agreed premises*. This explains the persistent co-occurrence of both forms in RC-043 and RC-044 simultaneously.

### Watch B Type Table (updated through RC-044)

| Domain | Composite | NEA | DAM | Watch B Character |
|---|---|---|---|---|
| RC-035 Industrial Policy | Low | Low | Low | Theoretical (existence) |
| RC-037 Lead-Crime | Intermediate | Intermediate | Low | Theoretical (existence) |
| RC-038 Monetary Policy | Low | Low | Low | Theoretical (existence) |
| RC-040 Minimum Wage | Intermediate | High | Intermediate | Directional |
| RC-042 Incarceration | Low | High | Low | Theoretical (existence) |
| RC-041 Air Pollution | Intermediate | Intermediate | High | Methodological |
| RC-043 Dietary Sodium | Intermediate | Intermediate (lean Low) | High | Theoretical (optimum) + Methodological |
| RC-044 Alcohol | Intermediate | Intermediate (lean Low) | High | Theoretical (optimum) + Methodological |
| RC-036 Climate Attribution | High | High | High | Minimal |
| RC-039 Vitamin A | High | High | High | Minimal |

RC-043 and RC-044 now form a two-observation pair: identical criterion profiles (1 High DAM + 3 Intermediate, NEA lean Low) and identical Watch B character (Theoretical optimum + Methodological simultaneously). This is the first two-observation pattern for a specific Watch B sub-type under High DAM. Anti-compression: two instances, not a promoted pattern. But the pattern is structurally visible and the next observation carries more weight.

### Refined Scope Statement (candidate — two observations)

> DAM resolves Watch B about causal existence by encoding the positive answer institutionally. DAM can take a formal position on the optimum question (TMREL specification, sick-quitter correction, TMREL defense). DAM transforms Theoretical (optimum) Watch B into Methodological Watch B for researchers whose dispute is about whether DAM's methodology correctly implements agreed biological premises. DAM cannot suppress Theoretical (optimum) Watch B among researchers who dispute the biological premises that generate DAM's optimum position — their Watch B is rooted in a biological claim that no attribution methodology can resolve by formalizing a different biological claim.

**Status:** Candidate. Two observations. Anti-compression applies.

### Phase Update — Mechanism Scope Delimitation Deepens

The transition from mechanism-decomposition to mechanism scope delimitation is now two audits deep. The questions have become increasingly precise:

| Stage | Question |
|---|---|
| RC-041 | Does DAM transform Watch B differently than NEA? |
| RC-042 | Does NEA alone transform Watch B without DAM? |
| RC-043 | Can High DAM coexist with Theoretical Watch B? |
| RC-044 | Can DAM's explicit engagement with the optimum question suppress Theoretical (optimum) Watch B? |

Each question is a refinement of the previous one, not a repetition. The mechanism is becoming more precisely bounded through this sequence. What began as "causal-identification capacity determines Watch B" has resolved into a more specific claim about what different components of that capacity do and do not accomplish.

**Next highest-value test options (revised post-RC-044):**

1. **High DAM + uncontested TMREL domain:** If Theoretical (optimum) Watch B is absent in a High DAM domain where the policy threshold is not disputed (e.g., blood pressure targets in antihypertensive treatment, where guidelines are largely accepted and the dispute is magnitude, not direction), this would confirm that the Theoretical (optimum) sub-type requires an active biological-premises dispute, not merely the presence of a TMREL.

2. **High DAM + existence-level resolution + accepted optimum:** A domain that has passed through both Watch B stages (existence resolved, optimum settled) into pure APG would be the first case showing that Theoretical (optimum) Watch B can be resolved — it is not a permanent feature of High DAM domains. This would show the endpoint of the trajectory.

3. **Low DAM + contested optimum:** Would clarify whether Theoretical (optimum) Watch B requires existence-level resolution as a precondition, or whether it can appear directly without the existence-level phase being completed first.

---

## Post-RC-044 Synthesis: Premise vs. Implementation Distinction (added 2026-06-24)

RC-044's key contribution is not that Theoretical (optimum) Watch B survived. It is that it survived explicit DAM engagement. That distinction tightens the mechanism candidate substantially.

### The Operating Scope Boundary

The scope boundary is no longer between "DAM addresses the optimum question" and "DAM does not address the optimum question." RC-044 showed DAM can address the optimum question directly (GBD 2018 TMREL=0 defense with explicit sick-quitter correction). The boundary is between:

**Implementation disputes:** Does DAM's methodology correctly implement the agreed biological premises? (e.g., Did GBD adequately correct for sick-quitter contamination? Is the exposure-response function specified correctly?) These are disputes about whether DAM did its job correctly. DAM transforms these into Methodological Watch B.

**Premise disputes:** Are the biological premises themselves correct? (e.g., Is the HDL-protective mechanism real? Does RAAS activation at low sodium cause cardiovascular harm?) These are disputes about the underlying biology that DAM's methodology takes as inputs. DAM cannot resolve premise disputes by formalizing a position derived from different premises.

This maps directly onto the co-occurrence structure observed in RC-043 and RC-044:
- Watch B Methodological = implementation dispute (active in both; GBD's methodology contested on its own terms)
- Watch B Theoretical (optimum) = premise dispute (active in both; biological premises contested independent of methodology)

### Refined CMech-001 Claim

**CMech-001 (original):** As causal-identification capacity increases, Watch B recedes and may change form.

**CMech-001 (revised through RC-042):** NEA and DAM perform different epistemic functions. DAM drives Watch B transformation by formally integrating competing pathways.

**CMech-001 (refined through RC-044 — candidate, two supporting observations for premise/implementation distinction):**

> DAM transforms specific sub-types of Watch B:
> - DAM resolves Theoretical (existence) Watch B by institutionally encoding causal presence
> - DAM transforms Theoretical (optimum) Watch B into Methodological Watch B for the subset of researchers whose dispute is about implementation of agreed premises
> - DAM cannot suppress Theoretical (optimum) Watch B among researchers whose dispute is about the biological premises generating the optimum position

**What this means:** CMech-001 is not a claim that DAM transforms Watch B. It is a claim about which Watch B sub-types DAM can and cannot transform. That is a more precise and more vulnerable claim. It generates cleaner wound conditions and cleaner predictions.

### New Wound Condition: Wound 7

**Wound 7 — DAM suppresses a premise-level dispute:**

A domain where High DAM coexists with an active biological premise dispute over the optimum level, and that premise dispute is resolved — not because researchers accepted DAM's methodology but because the underlying biological claim was settled (e.g., by an RCT, a mechanistic study, or accumulated MR evidence resolving the premise).

This would mean the scope boundary is not stable — that premise disputes can be resolved, and when they are, DAM's formalization of the resulting optimum also resolves the Watch B. This wound condition would not eliminate CMech-001 but would require revising the claim that premise disputes are categorically outside DAM's resolution capacity.

*What would constitute this wound:* A domain currently showing Theoretical (optimum) Watch B under High DAM, where a subsequent RCT or mechanistic study settles the premise dispute (e.g., a long-term alcohol RCT showing no J-curve effect at any consumption level; or a mechanistic study conclusively showing the HDL pathway does not reduce cardiovascular mortality net). The Watch B transformation would then be attributable to premise resolution, with DAM formalizing the result — not to DAM alone.

**Note:** Wound 7 is not a wound to the overall mechanism but to the claim that the premise/implementation boundary is permanent. It would show that premise disputes can cross into implementation disputes once the premise is settled, and that DAM then finalizes the Watch B transformation. This would refine CMech-001 further rather than eliminating it.

### Watch B Type Taxonomy (candidate — not promoted)

| Watch B Type | Core Dispute | DAM Transforms? |
|---|---|---|
| Theoretical (existence) | Is the causal pathway real? | Yes — institutional encoding suppresses |
| Directional | Is the net effect positive or negative? | Partially — Intermediate DAM associated with directional disputes |
| Methodological | Were agreed premises implemented correctly? | Yes — formalization transforms into quality dispute |
| Theoretical (optimum) | Are the premises generating the optimum correct? | No — formalization cannot resolve premise disputes |

**Status:** Candidate taxonomy, not promoted. Four Watch B types with two observations each at most. The DAM-Transforms column is the testable component: it generates specific predictions about which domains will show which Watch B types under which DAM scores.

### Object Status After RC-044

| Object | Status |
|---|---|
| Maturity Gradient | Stable — confirmed across nine domains in two eras |
| CMech-001 | Active — narrowed, not abandoned; premise/implementation distinction as operating refinement |
| NEA/DAM Functional Distinction | Supported — two direct comparison observations (RC-041 vs. RC-042) |
| Watch B Transformation Hypothesis | Supported — survives through RC-044 with scope refinement |
| DAM Scope Boundary | Two observations (RC-043, RC-044); explicit engagement test survived |
| Theoretical (Optimum) Watch B | Candidate sub-type — two instances, near-identical criterion profiles |
| Mechanism Phase | Scope Delimitation continuing |

### Significance of Narrowing

Cycle 7 has narrowed CMech-001 rather than broadened it. The mechanism candidate now makes fewer claims than it did after RC-040:

- Before Cycle 7: DAM suppresses Watch B
- After RC-041: DAM transforms Watch B type specifically
- After RC-042: DAM transforms Watch B; NEA alone does not when multiple competing mechanisms exist
- After RC-043: DAM suppresses existence-level Theoretical Watch B; optimum-level Theoretical Watch B may persist
- After RC-044: DAM suppresses existence-level Theoretical Watch B and transforms implementation disputes into Methodological Watch B; DAM cannot suppress premise disputes about the optimum

Each step makes the mechanism claim more specific and therefore more vulnerable. Narrowing is the expected trajectory of a mechanism candidate under sustained pressure. It is a stronger signal than continued broad confirmation would be, because it increases the number of ways the mechanism can fail.

---

## Stage 5 Entry Conditions — Pre-Registered Before RC-045 (added 2026-06-24)

This section is committed before RC-045 is selected. Its purpose is the same as the wound conditions and cross-audit predictions: to freeze the entry condition for the next phase before the test case is chosen, preventing retrospective rationalization about whether Stage 5 has been entered.

### Stage Map

| Stage | Description | Status |
|---|---|---|
| Stage 1 | Audit collection | Complete |
| Stage 2 | Pattern detection | Complete |
| Stage 3 | Pattern validation (two eras, independent measurement) | Complete |
| Stage 4A | Mechanism discovery — CMech-001 specified | Complete |
| Stage 4B | Mechanism scope delimitation — premise/implementation boundary identified | Complete (Checkpoint #010) |
| Stage 5 | Mechanism competition — CMech-001 vs. named alternatives | Entry conditions specified; not started |
| Stage 6 | Decision utility — methodology improves live decisions | Untested |

### The Stage 4→5 Transition Condition

Stage 5 does not begin with another successful CMech-001 prediction. It begins when:

1. A named mechanism competitor generates a **distinguishable prediction** — an observation where CMech-001 and the alternative predict different outcomes, not the same outcome for different reasons.
2. An audit is selected **specifically because either mechanism could win** — not because CMech-001's scope can be further refined.

The question changes from:

> What exactly is the mechanism claiming?

to:

> Why this mechanism rather than its competitors?

Cycle 7 (RC-041–RC-044) never crossed this boundary. It kept refining CMech-001's scope. That was productive Stage 4B work. It is not Stage 5 work.

---

### Critical Correlation Warning: DAM and Institutional Authority Have Not Been Separated

**The unresolved problem that blocks Stage 5:** In every audit conducted so far, DAM score and institutional authority have been perfectly correlated.

| Domain | DAM | Institutional Authority |
|---|---|---|
| RC-041 Air Pollution | High | High (IARC Group 1, GBD, WHO) |
| RC-043 Dietary Sodium | High | High (GBD, WHO formal guideline) |
| RC-044 Alcohol | High | High (GBD, WHO, IARC) |
| RC-036 Climate Attribution | High | High (IPCC, WWA) |
| RC-039 Vitamin A | High | High (Cochrane, WHO, UNICEF) |
| RC-035 Industrial Policy | Low | Low (no WHO equivalent) |
| RC-038 Monetary Policy | Low | Low (no IARC equivalent) |
| RC-042 Incarceration | Low | Low (no GBD equivalent) |

CMech-001 claims that evidential capacity (captured by DAM) drives Watch B transformation. Alternative A claims that institutional authority (prestige, gatekeeping, publication infrastructure) drives Watch B transformation. In every case audited, these are the same domains. CMech-001 and Alternative A have coexisted while making identical predictions. They have not competed.

This is not a criticism of any individual audit. It is a structural fact about the repository's current evidence base. The correlation must be broken before the alternatives can be tested.

**The unresolved question is not:** Which mechanism is correct?

**The unresolved question is:** Can the mechanisms be observed separately?

---

### Alternative A Design Specification

**Alternative A (Prestige/Gatekeeping):** Watch B recedes in high-maturity domains not because evidential capacity establishes causal role but because the institutional infrastructure of the domain prevents Watch B claims from being published or taken seriously. The mechanism is social and organizational, not epistemic.

**Discriminating domain design:**

A domain with high evidential capacity (strong natural experiments, named attribution methods, replicated causal direction) but **weak institutional authority** — no IARC-equivalent, no GBD burden line, no WHO guideline certifying the causal claim, consensus maintained by competing research programs without a centralized gatekeeping structure.

| Explanation | Prediction for this domain |
|---|---|
| CMech-001 | Watch B recedes — evidential capacity is sufficient |
| Alternative A | Watch B remains — institutional gatekeeping absent |

**Operational indicators for weak institutional authority:**
- No single prestigious body has classified the causal claim (no IARC monograph, no GBD comparative risk assessment, no Cochrane meta-analysis as the recognized authority)
- Consensus is distributed across competing research programs, each with institutional homes, none with veto power over the causal claim
- Publication in top journals does not require accepting the causal claim — skeptical papers appear alongside affirming papers without gatekeeping

**Candidate domain — Returns to Education:**

The returns-to-education literature has:
- High NEA: compulsory schooling natural experiments (Angrist-Krueger 1991 quarter-of-birth; Harmon and Walker 1995 UK school-leaving age reform; Duflo 2001 Indonesia school construction), card instruments, Vietnam draft lottery
- DAM: Standard IV methodology applied consistently; Mincer equation framework is named and taught
- Replication: extensive, across countries and time periods
- **But:** No institution analogous to IARC classifies "education causes earnings increases." No GBD equivalent estimates "education-attributable mortality burden." The Mincer-framework consensus is maintained by the labor economics profession without a central gatekeeping authority.

If Watch B is largely absent in returns to education — as preliminary reading suggests — that is difficult to explain on Alternative A's terms: the gatekeeping structures are weak, yet Watch B appears to have receded. If Watch B is active (researchers actively contest whether education causes earnings, rather than how much), Alternative A gains support.

**Status:** Candidate domain identified. Pre-registration of specific Watch B prediction required before audit is run.

---

### Alternative B Design Specification

**Alternative B (Selection into Measurement):** High DAM domains attract research programs that presuppose causal role. Watch B's apparent absence is not evidence that it was resolved — it is evidence that the research program never seriously engaged the existence question. Attribution studies (how much?) dominate; existence studies (does it?) are rare or absent because the program was founded after causal role was assumed.

**The problem with Alternative B:** Unlike Alternative A, it is not primarily a cross-domain discriminating hypothesis. Its claims are about the internal history of individual research programs — whether they were founded to test causal existence or founded after causal existence was assumed. This is rarely visible from a single-claim audit.

**Operational signature:** A domain where:
- Attribution methodology (DAM) is highly developed
- Watch B is minimal
- But the research program history shows that existence was assumed at founding, not demonstrated — the field began measuring magnitudes before settling the causal claim

**Why this is hard to audit cleanly:** The history of a research program's founding assumptions requires historical research rather than a claim audit. A single-claim audit can identify that Watch B is absent and that DAM is high, but it cannot easily determine whether the absence is because Watch B was resolved or because the program design selected against testing it.

**Current status:** Alternative B does not yet have a clean audit design. This is a state description, not a weakness. Recording it as undesigned is the accurate representation. Alternative B remains a named competitor to CMech-001 with a specified claim but without a specified test domain.

**What would constitute an Alternative B test:** A domain audit supplemented by a research-program history analysis — specifically, a search for the founding papers or foundational debates of the domain's attribution methodology, to determine whether causal existence was tested and confirmed before attribution methods were developed, or whether attribution methods were built on an assumed causal claim. This requires a different kind of evidence than a standard claim audit provides.

---

### What Stage 5 Does Not Require

Stage 5 does not require CMech-001 to lose. It requires CMech-001 to be tested against a competitor that could win. The selection criterion for RC-045 is not:

> A domain where CMech-001 predicts the correct object.

It is:

> A domain where Alternative A or Alternative B generates a divergent prediction, and the audit result distinguishes them.

An audit that simply confirms CMech-001 while leaving the alternatives unpressured is another Stage 4B observation. It may be informative about CMech-001's scope but it does not advance toward Stage 5.

---

## RC-045 Assessment — First Stage 5 Result (added 2026-06-24)

RC-045 (Returns to Education) was the first audit selected specifically because a named competitor (Alternative A) generated a distinguishable prediction before evidence was reviewed.

**Pre-registration predictions:**
- Maturity Gradient + CMech-001: APG primary, Watch B minimal (evidential capacity sufficient even without centralized institutional authority)
- Alternative A: Watch B materially active (institutional gatekeeping absent in economics)

**Result:** APG primary, Watch B minimal. Watch B present only in Methodological form (LATE external validity concerns; contribution-share debates between human capital and signaling are APG-structured, not Theoretical Watch B).

**Existence-level Theoretical Watch B:** Largely absent. The signaling debate (Spence 1973, Caplan 2018) disputes the mechanism behind the education-earnings relationship, not its existence. Signaling models still predict that education causes earnings increases — through credentialing, not skill acquisition. No mainstream research program argues that education does not cause earnings to increase.

**CMech-001 verdict: Cleared first Stage 5 test.** Evidential capacity (rich IV literature, named Mincer methodology, 10+ natural experiments, extensive cross-national replication) appears sufficient to suppress existence-level Theoretical Watch B even in the absence of an IARC/WHO/GBD-equivalent institutional structure.

**Alternative A verdict: Pressured, not eliminated.** The prediction (Watch B materially active) did not materialize. Watch B is Methodological, not Theoretical. The pre-registration specified that Alternative A support requires Watch B "plausibly sustained by absence of institutional authority" — that criterion was not met.

**Alternative A's residual interpretation:** The economics profession's prestige hierarchy (top journals: AER, QJE, JPE; NBER; elite department affiliation) may function as a *de facto* gatekeeping mechanism even without a formal IARC-equivalent. On this reading, RC-045 tested Alternative A in a domain with a *different* institutional structure than IARC/GBD, but not necessarily a *weaker* one. Alternative A retains this interpretive path but must now carry an empirical burden: the economics prestige hierarchy would need to function as effectively as IARC Group 1 classification at suppressing Watch B, despite its different organizational form.

### Watch B Type Table — Updated Through RC-045

| Domain | Composite | NEA | DAM | Watch B Character |
|---|---|---|---|---|
| RC-035 Industrial Policy | Low | Low | Low | Theoretical (existence) |
| RC-037 Lead-Crime | Intermediate | Intermediate | Low | Theoretical (existence) |
| RC-038 Monetary Policy | Low | Low | Low | Theoretical (existence) |
| RC-040 Minimum Wage | Intermediate | High | Intermediate | Directional |
| RC-042 Incarceration | Low | High | Low | Theoretical (existence) |
| RC-041 Air Pollution | Intermediate | Intermediate | High | Methodological |
| RC-043 Dietary Sodium | Intermediate | Intermediate (lean Low) | High | Theoretical (optimum) + Methodological |
| RC-044 Alcohol | Intermediate | Intermediate (lean Low) | High | Theoretical (optimum) + Methodological |
| RC-045 Returns to Education | High | High | Intermediate-High | Methodological (secondary) |
| RC-036 Climate Attribution | High | High | High | Minimal |
| RC-039 Vitamin A | High | High | High | Minimal |

RC-045 is the first High-composite domain without fully centralized institutional authority. Watch B is Methodological rather than Minimal — slightly stronger than RC-036 and RC-039. This may reflect DAM being Intermediate-High rather than unambiguously High.

### Stage 5 Status After RC-045

| Stage 5 Requirement | Status |
|---|---|
| First audit with divergent mechanism predictions | Satisfied (RC-045) |
| CMech-001 cleared first test | Yes |
| Alternative A eliminated | No — residual interpretation via economics prestige hierarchy |
| Alternative B tested | No — design specification still unresolved |
| Stage 5 complete | No — one passing test is not validation; residual interpretation remains open |

**Anti-compression:** One Stage 5 test passing does not validate CMech-001. The gap between "cleared first Stage 5 test" and "mechanism validated against alternatives" remains substantial.

### Next Highest-Value Candidate for RC-046

To close Alternative A's residual interpretation, the ideal domain would have:
- High evidential capacity (strong natural experiments or experimental evidence)
- Named methodological framework (some DAM)
- Genuinely fragmented institutional structure — prestige hierarchy split between competing camps, each publishing in different journals, using different methods, drawing on different disciplinary traditions; no single professional body capable of certifying the causal claim

The fragmented-prestige requirement is what RC-045 did not cleanly satisfy. A domain where the prestige hierarchy is genuinely divided — not merely differently organized than IARC — would more cleanly test whether evidential capacity alone suppresses Watch B without institutional coordination of any form.

---

## Post-RC-045 Update: Alternative A Revision and Cycle 8 Entry Criterion (added 2026-06-24)

This section is committed before RC-046 is selected. Its purpose: freeze the revised state of Alternative A and the Cycle 8 design criterion before a test domain is chosen.

### 1. Alternative A Revision — Formal Certification Wounded; Prestige Coordination Survives

RC-045 forced a specific change in what Alternative A is claiming. These are not the same mechanism:

**Alternative A (original / pre-RC-045):**
> Formal certification structures (IARC Group 1 classification, GBD comparative risk assessment, WHO formal guidelines) suppress Watch B by providing authoritative institutional endorsement of the causal claim. Without such structures, Watch B persists.

**Alternative A (revised / post-RC-045):**
> Prestige coordination — the concentration of epistemic authority in a network of elite journals, funding bodies, hiring networks, and citation structures — suppresses Watch B even without formal certification. A research community with high prestige coordination converges on a causal claim and marginalizes skeptical voices regardless of whether a formal body has certified the claim.

**What RC-045 did:** Showed that formal certification is not necessary for Watch B suppression. Returns to education has no IARC equivalent, yet existence-level Theoretical Watch B is absent. The formal-certification version of Alternative A cannot explain this.

**What RC-045 did not do:** Show that prestige coordination is absent in returns to education. Economics has elite journals (AER, QJE, JPE), concentrated citation networks (Card, Angrist, Duflo receive the bulk of citations in the IV literature), elite departments, NBER working paper series, and a relatively coherent hiring network. The prestige-coordination version of Alternative A can explain the RC-045 result: prestige coordination in economics is high, even without a formal WHO-equivalent, and that coordination suppresses Watch B.

**The implication:** Alternative A's change from "formal certification matters" to "prestige coordination matters" is not a retreat to a weaker position. It is a retreat to a position that is simultaneously narrower and harder to test — because prestige coordination is more continuous and harder to operationalize than formal certification. The next test must be designed specifically for prestige coordination, not merely for formal certification absence.

---

### 2. New Correlation Warning — DAM and Prestige Coordination Remain Unseparated

**The unresolved correlation after RC-045:**

| Domain | DAM | Formal Certification | Prestige Coordination | Watch B |
|---|---|---|---|---|
| High DAM Cycle 7 domains | High | High | High | Minimal/Methodological |
| RC-045 Returns to Education | Intermediate-High | Low | High | Methodological (secondary) |
| Low DAM domains (RC-035, RC-038, RC-042) | Low | Low | Low | Theoretical |

RC-045 separated DAM from formal certification. It did not separate DAM from prestige coordination. In every domain in the repository, DAM and prestige coordination remain correlated:
- High DAM domains have concentrated prestige (whether through IARC-type bodies or through elite academic networks)
- Low DAM domains have fragmented or weak prestige structures

**The unresolved question is now:**

Does DAM suppress Watch B (CMech-001)?

Or does prestige coordination suppress Watch B (narrowed Alternative A)?

**What the repository currently knows:** Formal certification alone is insufficient to explain the pattern — RC-045 showed this. What the repository does not yet know: whether DAM-level causal methodology, or the prestige coordination that tends to accompany high methodological development, is doing the explanatory work.

This is a narrower and more specific statement than anything Cycle 7 established. Cycle 7 showed DAM ≠ formal certification at the mechanism level. RC-045 showed formal certification is not necessary. The remaining ambiguity is DAM vs. prestige coordination — which requires a domain where these are not correlated.

---

### 3. Cycle 8 Entry Criterion — Prestige Coordination Must Be Separable

**The Cycle 8 design criterion:**

A valid Cycle 8 audit (starting from RC-046) must satisfy:

1. **Evidential capacity high** (strong natural experiments or experimental evidence; named causal methodology)
2. **Prestige coordination low or fragmented** — the research community has no concentration of authority in a small number of elite journals, departments, or funding bodies; competing methodological traditions have approximately equal prestige; no single research program dominates citation patterns or hiring for this specific domain
3. **DAM present at some level** (so it is not simply a repeat of the Low-DAM Cycle 7 cases)

Under this design, CMech-001 and the narrowed Alternative A predict different outcomes:

| Explanation | Prediction |
|---|---|
| CMech-001 | Watch B recedes — evidential capacity suppresses existence dispute regardless of prestige coordination |
| Narrowed Alternative A | Watch B remains active — prestige fragmentation means no coordination mechanism to suppress existence dispute |

**What makes this harder than RC-045:** Prestige coordination is harder to operationalize than formal certification. Formal certification is binary (IARC Group 1: yes/no; GBD comparative risk assessment: yes/no). Prestige coordination is continuous. Pre-registration of the RC-046 domain selection must include an explicit assessment of prestige coordination *before* claim evidence is reviewed — the same discipline that was applied to institutional authority in the RC-045 pre-registration.

**Candidate domain signatures for low prestige coordination:**
- Competing methodological traditions in different journals that don't cross-cite
- Researchers from different disciplines (economics, psychology, sociology, medicine) studying the same phenomenon without convergence
- Multiple systematic reviews reaching contradictory conclusions using the same underlying evidence
- No clear "consensus statement" from any professional body, and no single research group whose estimates are treated as the reference point

**Candidate domain:** Psychotherapy effectiveness and mental health outcomes. Multiple competing traditions (CBT, psychodynamic, humanistic, third-wave behavioral), competing evidence standards (RCTs vs. effectiveness studies vs. naturalistic data), competing review bodies (NICE guidelines, APA task forces, Cochrane, independent meta-analysts reaching different conclusions), no IARC equivalent, no single prestigious group dominating citations across all traditions. High NEA for specific modalities (waitlist control RCTs, stepped-care RCTs); moderate DAM (manuals and adherence measures exist but no GBD-style attribution). This is a candidate only — pre-registration of maturity score and prestige coordination assessment required before audit.

---

### Stage Map — Updated After RC-045

| Stage | Description | Status |
|---|---|---|
| Stage 1 | Audit collection | Complete |
| Stage 2 | Pattern detection | Complete |
| Stage 3 | Pattern validation | Complete |
| Stage 4A | Mechanism discovery | Complete |
| Stage 4B | Mechanism scope delimitation | Complete |
| Stage 5 | Mechanism competition — formal certification removed; prestige coordination identified as residual | Active (1 observation) |
| Stage 6 | Decision utility | Untested |

---

## RC-046 Post-Audit Assessment: Psychotherapy Effectiveness (added 2026-06-24)

### Pre-Registered Predictions Recalled

CMech-001 prediction: Existence-level Watch B weak or absent; disputes APG/Methodological/Directional at modality level.
Alternative A prediction: Existence-level Watch B active; common-factors dispute constitutes genuine existence-level Theoretical Watch B; prestige fragmentation prevents convergence.

Domain profile: Low Prestige Coordination + Intermediate DAM — first such combination in repository.

### Audit Result

**Existence-level Watch B: Absent.**

No credentialed research program argues psychotherapy produces effects no better than chance. The common-factors debate (Wampold et al.) does not constitute Theoretical Watch B at the existence level — it constitutes APG dispute about contribution share. All major research traditions (CBT, psychodynamic, humanistic, common factors) agree psychotherapy outperforms inactive controls with clinically meaningful effect sizes.

The "does psychotherapy outperform non-specific supportive contact?" question has been studied directly. Effect sizes versus active controls are smaller than versus waitlist (d ≈ 0.2–0.4 vs. d ≈ 0.7–0.9) but positive and statistically significant. This is a magnitude dispute, not an existence dispute.

**Active Watch B:**
- Directional at modality level: CBT vs. psychodynamic superiority unresolved across decades of head-to-head RCTs
- Methodological: Researcher allegiance bias; efficacy vs. effectiveness gap
- APG: Common factors vs. specific technique contribution share; dose-response; population moderators

**CMech-001 result: Supported.** Passes the correlation-breaking test — existence-level Watch B absent despite Low Prestige Coordination. DAM (named RCT methodology, adherence measures, network meta-analysis) appears sufficient to suppress existence-level Watch B without PC assistance. This is CMech-001's hardest test: RC-041 through RC-045 all had High or Intermediate-High PC; RC-046 has Low PC and CMech-001's prediction still holds.

**Alternative A result: Not confirmed at existence level.** The mechanism predicts existence-level Watch B active under Low PC; this was not observed. However, Alternative A's mechanism may correctly describe modality-level disputes: the field's fragmentation (Low PC) appears to prevent convergence on which modality is superior, even though all traditions agree on general efficacy. This is a scope-limiting observation, not a clean falsification.

---

### Candidate Refinement: Level-Differentiated Mechanism

**Candidate (n=1):** CMech-001 and Alternative A may both operate, but at different levels of the causal claim.

| Level | Operating Mechanism | Evidence |
|---|---|---|
| Existence-level Watch B | DAM suppresses (CMech-001) | RC-041, RC-042, RC-045, RC-046 all show existence-level Watch B absent when DAM ≥ Intermediate |
| Modality-superiority disputes | PC affects convergence (Alternative A residual) | RC-046: 40+ years of head-to-head trials without CBT vs. psychodynamic consensus under Low PC; contrast with High PC domains where such disputes are typically APG-structured not Watch B |

**Anti-compression discipline:** This is a candidate, not a promoted object. One observation (RC-046) is insufficient. Promotion to a settled finding requires at least two additional observations confirming the level-differentiated pattern. What would constitute confirmation: another Low PC + Intermediate DAM domain where existence-level Watch B is absent but modality-level Watch B is active and unresolved.

What would constitute disconfirmation: a Low PC + Intermediate DAM domain where existence-level Watch B is also absent AND modality disputes have converged — which would suggest PC is irrelevant at all levels.

---

### Updated Watch B Type Table

| Domain | Maturity | DAM | PC | Watch B Character |
|---|---|---|---|---|
| RC-041 Air Pollution | High | High | High | Methodological (secondary); existence minimal |
| RC-043 Dietary Sodium | Intermediate | High | High | Theoretical (optimum) + Methodological |
| RC-044 Alcohol | Intermediate | High (lean) | High | Theoretical (optimum) + Methodological |
| RC-045 Returns to Education | High | Intermediate-High | High | Methodological (secondary); existence absent |
| RC-046 Psychotherapy | Intermediate | Intermediate | **Low** | APG primary; Directional (modality) + Methodological active; **existence absent** |

**The RC-046 entry is the first row where PC is Low.** Existence-level Watch B remains absent. This is the observation the repository needed for CMech-001 vs. Alternative A to generate distinguishable outcomes — and CMech-001's prediction held.

---

### Stage 5 Status — After RC-046

| Mechanism | Pre-RC-046 status | Post-RC-046 status |
|---|---|---|
| CMech-001 | 1 supporting observation (RC-045); untested at Low PC | 2 supporting observations; passed correlation-breaking test (Low PC + Intermediate DAM); existence-level Watch B absent as predicted |
| Narrowed Alternative A | Survived RC-045 (economics has high PC); not tested at Low PC | Not confirmed at existence level; may retain scope at modality-superiority level; candidate level-differentiation finding |

**Stage 5 summary:** CMech-001 has now passed a test Alternative A cannot explain away by residual prestige coordination. RC-046 is the first genuinely discriminating observation. Alternative A's survival depends on whether its mechanism is limited to modality-level disputes rather than existence-level Watch B suppression — a narrowing that would make it complementary rather than competitive with CMech-001.

**Stage map updated:**

| Stage | Description | Status |
|---|---|---|
| Stage 1 | Audit collection | Complete |
| Stage 2 | Pattern detection | Complete |
| Stage 3 | Pattern validation | Complete |
| Stage 4A | Mechanism discovery | Complete |
| Stage 4B | Mechanism scope delimitation | Complete |
| Stage 5 | Mechanism competition — CMech-001 passes correlation-breaking test; Alternative A pressured to modality-level scope | Active (2 observations) |
| Stage 6 | Decision utility | Untested |

**Stage 5 current state:** Alternative A has been forced into a narrower and more specific claim. CMech-001 has passed one test. The competition is active but not resolved. Stage 5 continues into Cycle 8, with the revised target: separate DAM from prestige coordination.
