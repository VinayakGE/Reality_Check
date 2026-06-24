# RSQ-002: The Domain-Maturity Gradient — Candidate Mechanism

**Date:** 2026-06-24
**Type:** Repository Structure Question — Mechanism Specification
**Status:** Candidate mechanism under development; wound conditions pre-registered; no audits selected yet

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

RSQ-002 is open. The candidate mechanism is committed. Wound conditions are pre-registered. RC-041 has not yet been selected.

Unlike RSQ-001 (which had a designated test case — the APG promotion decision — built into its resolution path), RSQ-002's test cases must be designed from the differential predictions. The resolution path requires audit selection that differs from the selection logic used in Cycles 5 and 6.
