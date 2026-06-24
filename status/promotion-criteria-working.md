# Promotion Criteria — Working Specification

**Status:** Working document. Not a governing principle.
**Date:** 2026-06-24
**Source:** Extracted from repository practice across prior object-classification decisions. Not derived theoretically.
**Applications:** 1 (Attribution Precision Gap promotion decision, RSQ-001)

---

## Origin and Hazard

The repository has been applying different promotion logics to different object types without having named the distinction. This document extracts the implicit criteria from observed behavior.

The hazard: retrospective reconstruction may overstate the coherence of prior decisions. These criteria fit the observed behavior. They may need extension when applied to new cases. A specification that fits the first test case completely is more suspicious than one that produces edge cases, because a complete first-pass fit suggests the specification was derived with the test case in view.

The four data points from which these criteria were extracted:
- Watch B promotion (recurrence + accumulation + naming)
- Watch B non-promotion phase
- Attribution Precision Gap deferral (pending boundary specification)
- Four-cell map handling (observation only; explicit upgrade criterion)

This is a small sample. The criteria should be treated as candidate specifications subject to revision.

---

## Three Object Classes

### Class 1 — Explanatory Objects

*Examples: Strong selector, Weak selector, Adaptation, Technical-only model, Discovery infrastructure*

These answer the question: *Why did the outcome occur?*

They compete. They wound each other. They generate predictions.

**Promotion path:**
- Survive pre-registered wound conditions
- Generate testable ordering predictions
- Withstand discriminating tests designed to fail them

Confidence accumulates through test survival, not instance accumulation. One instance surviving a genuine wound condition carries more weight than three instances that faced no discriminating test.

**Demotion:** Failure of a pre-registered prediction under conditions that preclude ad hoc defense.

**Note:** Explanatory objects do not have a terminal promotion point — they accumulate evidence continuously. The question is not "is this object promoted" but "what is the current evidentiary level."

---

### Class 2 — Epistemic Structure Objects

*Examples: Watch B, Attribution Precision Gap, Implementation-documentation limitation, Counterfactual unavailability*

These answer the question: *Why can't this question be resolved cleanly?*

They do not compete to explain outcomes. They explain limits on evaluation.

**Promotion path — all three required:**
1. **Instance count across distinct domains** — sufficient recurrence to suggest a general pattern rather than case-specific circumstances
2. **Structural consistency** — the bottleneck takes the same form across instances; the same underlying limit is operating
3. **Boundary specification** — explicit differentiation from the nearest adjacent epistemic object, with different evidential requirements identified

**Resolution path types:**
- *Tractable:* Evidence could resolve it but requires demanding study designs
- *Difficult:* Evidence exists but is costly, rare, or requires institutional access not currently available
- *Permanent:* No conceivable evidence path exists (RC-010 is the clearest example)

All three are valid resolution-path specifications. Permanent irresolvability is informative, not a failure of the object.

**Note on Watch B's promotion:** Watch B was promoted before Criterion 3 was articulated. It met Criteria 1 and 2 at promotion. Its boundary from Attribution Precision Gap was specified retroactively at Checkpoint #007. This is normal — categories are often defined by contrast, and contrast requires a second object.

---

### Class 3 — Observation Maps

*Examples: Four-cell discovery timing map*

These answer the question: *How do observed cases distribute across a structured space of possibilities?*

They do not explain outcomes. They classify implementations.

**Advancement:** Occupancy — observed cases filling cells.

**Upgrade criterion (explicit, from Checkpoint #007):** Cell classification must be made before the outcome is known, and the resulting prediction must hold. This is the condition for moving from observation map to explanatory relevance.

**Not promotable to explanatory model** until predictive relevance is demonstrated prospectively.

---

## Test Matrix for Specifications

When a promotion-criteria specification is applied to a new case:

| Outcome | Meaning |
|---|---|
| Wrong | Specification fails to explain prior or current decisions; requires revision |
| Redundant (weak) | Specification says nothing new; low value |
| Redundant (strong) | Specification makes existing implicit logic explicit; creates testability where none existed before |
| Incomplete | Specification explains part of the decision space but encounters unhandled edge cases; requires extension |
| Useful | Specification changes or materially clarifies the classification decision |

Incomplete is the modal expected outcome for a first-pass specification extracted from a small sample. Incompleteness that generates new work is evidence against overfitting, not evidence of failure.

---

## Known Gaps

This specification does not cover:

1. **What counts as "sufficient" instance count** for Class 2 promotion — Watch B was promoted at approximately 8 instances; Attribution Precision Gap at 3. The threshold appears context-dependent (how distinct are the domains? how consistent is the structure?) rather than a fixed number.

2. **Intensity threshold at Watch B / Attribution Precision Gap boundary** — at what point does a very small accepted contribution become a causal-role question rather than a decomposition question?

3. **Counterfactual unavailability boundary** — the relationship between Attribution Precision Gap and counterfactual unavailability has not been specified.

4. **Multi-class cases** — some objects may contain elements of more than one class. The four-cell map is an observation tool (Class 3) whose potential explanatory relevance is being tracked (Class 1 logic). Whether mixed-class objects require a separate handling logic is unspecified.

---

## Revision History

- 2026-06-24: First draft, extracted from four prior classification decisions. Applied to Attribution Precision Gap promotion decision. Outcome: Useful + Incomplete. Two boundary conditions surfaced (see `attribution-precision-gap.md`).
