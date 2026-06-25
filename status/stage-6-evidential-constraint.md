# Stage 6 Evidential Constraint

**Date committed:** 2026-06-25
**Status:** Pre-registered — Stage 6 has not yet begun
**Purpose:** Define what would count as evidence for practical utility before any deployment, application, or Stage 6 observation is taken.

This document follows the same pattern as RSQ-001 (promotion criteria before application), OQ-Maturity (maturity operationalization before prospective testing), RSQ-002 Stage 5 entry conditions (mechanism competition rules before RC-045), and the Prestige Coordination Operationalization (new predictor frozen before RC-046). The consistent repository principle: introduce the evidential constraint before the first observation that could benefit from it.

Stage 6 has not begun. This document does not begin Stage 6. It defines what beginning Stage 6 would require.

---

## What This Document Does Not Contain

Deployment details, product ideas, customer selection criteria, experimental protocols, pricing, or distribution plans. Those belong after the evidential constraint is frozen, for the same reason maturity scores are committed before claim evidence is reviewed: if the standard is written after the first practical success, it cannot be distinguished from a standard written to fit that success.

---

## Question 1: What Claim Is Stage 6 Allowed to Make?

**Permitted Stage 6 claim:**

> The RC methodology improves decision quality — specifically, decisions made using the RC epistemic classification are better, on predefined outcome measures, than decisions made without it.

**What this is distinct from:**

The repository has demonstrated that it can classify epistemic structure accurately and prospectively. That is a Stage 1–5 achievement. It is not the same as improving decisions.

The distinction matters because accurate epistemic classification and improved decisions are separable outcomes. A decision-maker could receive an accurate RC classification (Watch B Methodological; APG primary; specific technique contribution share unresolved) and still make the same decision they would have made without it — because the decision does not depend on resolving that uncertainty, or because the classification arrived too late, or because the decision-maker could not act on the uncertainty type identified. Conversely, an inaccurate classification could produce a better outcome by luck.

Stage 6 is the stage where that gap is measured, not assumed closed. The permitted claim requires evidence that the gap has been crossed, not evidence that the classification was accurate.

**Explicitly not permitted as Stage 6 evidence:**

"The methodology correctly classified the epistemic structure of this domain" is a Stage 2–5 result. Relabeling it as decision improvement does not make it Stage 6 evidence.

---

## Question 2: What Evidence Would Count?

A valid Stage 6 observation must satisfy all three of the following conditions:

### Condition A — Prospective

The decision must be made using the RC methodology before the outcome is known, under conditions where the methodology could have produced a different classification that led to a different decision. Retrospective narratives ("if the decision-maker had known the Watch B was Methodological rather than Theoretical, they would have acted differently") do not satisfy this condition.

### Condition B — Comparative

The observation must include a comparison condition: an otherwise similar decision made without RC methodology input, or a decision made with a different epistemic framework applied to the same question. The comparison condition must be specified before the Stage 6 observation is taken, not selected after the fact to maximize apparent improvement.

### Condition C — Predefined Outcome Measure

The outcome measure — what counts as a "better" decision — must be committed before the Stage 6 observation is taken. The outcome measure must be:

- Observable independently of RC classification accuracy (a measure that is satisfied whenever the RC classification is correct is not a decision-improvement measure; it is a classification-accuracy measure in disguise)
- Specifiable in advance of the decision outcome being known
- Resistant to the objection that it was chosen because it happened to show improvement

What outcome measures are likely to qualify: decision-maker updates their confidence in a claim in a direction that turns out to be warranted; resources allocated to a domain based on RC Watch B classification show measurably different downstream value; policy adoption or rejection decisions informed by RC epistemic classification are tracked against independent assessments of those decisions over time.

What outcome measures are unlikely to qualify: "the decision-maker found the classification useful" (self-report is insufficient without behavioral evidence); "the classification was accurate" (classification accuracy, not decision improvement); "the decision-maker would recommend the methodology" (preference is not outcome).

---

## Question 3: What Would Not Count?

The following are explicitly excluded from Stage 6 evidence, regardless of how compelling they appear:

| Excluded observation | Why excluded |
|---|---|
| Additional successful RC audits | Stages 2–5 evidence; does not bear on decision improvement |
| More accurate or precise epistemic classifications | Stage 5 evidence; classification accuracy ≠ decision improvement |
| Retrospective narratives that a better decision "would have been made" | Non-prospective; cannot be distinguished from post-hoc rationalization |
| Decision-maker reports that the methodology "seemed useful" | Self-report without behavioral outcome; preference ≠ improvement |
| Successful prediction of Watch B character in a new domain | Stage 5 evidence (Track 1); does not constitute Stage 6 observation |
| Track 2 resolution (Alternative B addressed) | Stage 5 evidence (Track 2); necessary for mechanism completeness, not sufficient for decision-improvement claim |

Anti-compression applies to Stage 6 as it applies to all repository stages: a single Stage 6 observation, even one that satisfies all three conditions, constitutes evidence but not a promoted conclusion. Promotion of "the methodology improves decision quality" as a repository finding requires at least three independent Stage 6 observations under the conditions specified here.

---

## The Comparison Condition Problem

Stage 6 requires specifying what "a decision made without RC methodology" looks like. This is harder than the analogous operationalization problems in prior stages, because decision quality is harder to observe than Watch B character.

Two candidate comparison conditions, recorded here as candidates rather than commitments:

**Candidate A — Within-decision-maker comparison:** The same decision-maker makes a sequence of decisions on related questions, with and without RC methodology input, in a design that prevents the methodology from contaminating the non-methodology arm. Difficult to implement without cross-contamination.

**Candidate B — Between-decision-maker comparison:** Decision-makers using RC methodology are compared against otherwise similar decision-makers on the same question without it. Difficult to match decision-maker quality and information access. Selection into RC methodology use may introduce systematic differences unrelated to the methodology.

The comparison condition operationalization is not committed in this document. It is recorded as the primary unresolved specification problem that must be addressed before the first Stage 6 observation is designed. Writing the comparison-condition operationalization before Stage 6 begins is the document that would play the same role for Stage 6 that OQ-Maturity played for Stage 3.

---

## Stage 6 Entry Condition

Stage 6 may begin when:

1. A comparison-condition operationalization document is committed (analogous to OQ-Maturity)
2. At least one predefined outcome measure is specified and committed
3. A prospective Stage 6 observation is designed under conditions where the methodology could fail to show improvement

**Stage 6 does not begin by starting to deploy the methodology.** It begins by committing the evidential standard the deployment will be evaluated against.

---

## Relation to Prior Stages

Stage 6 does not replace or supersede Stages 1–5. The constraint-introduction pattern requires that Stage 6 evidence is evaluated against the Stage 6 standard, not against earlier standards. Specifically:

- Stages 1–5 provide the classification capability Stage 6 will deploy. They do not provide Stage 6 evidence.
- Track 1 (mechanism competition) and Track 2 (artifact challenge) remain open in Stage 5. Stage 6 can proceed in parallel with Stage 5, but Stage 5 resolution is not a Stage 6 precondition. A methodology that improves decisions while its internal mechanism remains contested is still a methodology that improves decisions.
- Stage 6 evidence cannot be used to resolve Stage 5 questions. If the methodology produces better decisions, that tells us the output is useful; it does not tell us whether CMech-001 or Alternative A correctly explains why the output is useful.

These are separable questions. The repository's constraint-introduction pattern requires keeping them separate.
