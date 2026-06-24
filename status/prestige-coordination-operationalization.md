# Prestige Coordination Operationalization

**Date committed:** 2026-06-24
**Purpose:** Specify how prestige coordination is scored before RC-046 is selected

This document serves the same function for Stage 5 mechanism competition that `domain-maturity-operationalization.md` served for the gradient predictions. Without independent operationalization committed before domain selection, prestige coordination can be assessed retrospectively from the claim evidence and audit findings — generating apparent confirmation with no falsification potential.

The failure mode: "That field turned out to have fragmented prestige, which explains the Watch B." If prestige fragmentation is assessed after seeing the Watch B result, the variable becomes a description of the outcome rather than an independent predictor. This is OQ-Maturity applied to Stage 5.

---

## The Variable Being Operationalized

**Prestige Coordination:** The degree to which epistemic authority in a domain is concentrated in a network of journals, citation clusters, review bodies, and research programs that coordinate around a shared causal conclusion, rather than distributed across competing traditions that do not converge.

Prestige Coordination is distinct from:
- **Formal Certification** (IARC Group 1, GBD comparative risk assessment, WHO guideline): A single institutional authority that formally classifies the causal claim. RC-045 showed this is not necessary for Watch B suppression.
- **DAM** (Dedicated Attribution Methodology): Named toolkit for causal attribution. Prestige Coordination and DAM are currently correlated across all repository domains. The purpose of this operationalization is to allow them to be scored independently before that correlation is tested.

The question Prestige Coordination answers: *Is there a coordination mechanism in this research community — distinct from formal certification and distinct from methodological development — that marginalizes existence-level causal skepticism regardless of whether a single authoritative body has certified the claim?*

---

## Four Indicators

### Indicator 1 — Journal Structure

*Question: Is there a dominant certifying publication venue for causal claims in this domain?*

**High (coordinated):** One or two journals receive the majority of definitive causal claims; publication in those venues functions as legitimacy certification; editors and reviewers share methodological commitments that serve as implicit gatekeeping for causal conclusions.

**Intermediate:** Three to five journals of roughly comparable prestige for causal claims; different journals have different methodological emphases but acknowledge each other's results as legitimate; no single journal monopolizes legitimacy but a small cluster does.

**Low (fragmented):** Many journals of roughly comparable prestige for causal claims within the domain; paradigm-specific journals (one for each competing tradition) have comparable prestige within their communities; publication in any one journal does not confer legitimacy for the other traditions.

---

### Indicator 2 — Citation Concentration

*Question: Does one analytic community anchor the causal literature?*

**High (coordinated):** One meta-analysis group or one set of foundational papers receives the large majority of citations when researchers establish the causal baseline; competing groups' results are referenced in comparison but not as independent anchors; new papers orient around one center of gravity.

**Intermediate:** Two to four competing groups whose papers are referenced as alternative positions; one group may be somewhat more cited but others are acknowledged as legitimate anchors; new papers must engage multiple reference points.

**Low (fragmented):** Multiple competing groups of roughly equal citation weight; mutual criticism in the literature (not merely independent work, but active citation of competing claims as problematic); no group whose estimates are treated as the undisputed reference point by researchers from other traditions.

---

### Indicator 3 — Review Body Convergence

*Question: Do major systematic review bodies reach similar causal conclusions for this domain?*

**High (coordinated):** The major bodies with resources to produce systematic evidence reviews (Cochrane, relevant professional associations, government agencies, international organizations) reach broadly similar conclusions about causal existence and direction; disagreements are primarily about magnitude, method implementation details, or policy thresholds — not about whether the causal relationship exists.

**Intermediate:** Some convergence on direction but substantial methodological disputes among review bodies; different bodies use different inclusion criteria and reach somewhat different causal conclusions; a consensus statement commands partial but not universal acceptance.

**Low (fragmented):** Multiple major review bodies reach different conclusions about causal existence or direction; competing systematic reviews using the same underlying evidence base reach contradictory causal conclusions; no consensus statement commands broad acceptance; new reviews from credentialed groups regularly challenge prior reviews' causal conclusions rather than merely updating them.

---

### Indicator 4 — DAM Presence

*Question: Are formal attribution methods present and developed in this domain?*

This indicator is included specifically to prevent Prestige Coordination from becoming a proxy for DAM. It must be scored independently of the other three. If Prestige Coordination and DAM are scored as separable in a domain (one High, the other Low or Intermediate), that domain becomes a candidate for the correlation-breaking test RSQ-002 requires.

**High:** Named toolkit for causal attribution applied consistently across the domain; institutional application of the named methods to produce authoritative estimates; methods are taught as the domain's standard.

**Intermediate:** Named methodology for individual studies within the domain; no institution applies the methods to produce global or authoritative attribution estimates; method is standard but not institutionally applied.

**Low:** No named methodology specific to the domain; each study designs its own causal identification strategy; no convergence on a standard attribution approach.

---

## Composite Classification

| Profile | Classification |
|---|---|
| 3+ High indicators | High Prestige Coordination |
| 2 High + 2 Intermediate | High (lean Intermediate) |
| Mixed without clear pattern | Intermediate |
| 2 Low + 2 Intermediate | Low (lean Intermediate) |
| 3+ Low indicators | Low Prestige Coordination |
| 3 High + 1 Low | High |
| 1 High + 3 Low | Low |
| 2 High + 2 Low | Intermediate |

**Edge-case rule:** As with domain maturity, 3H+1L = High; 1H+3L = Low; 2H+2L = Intermediate.

---

## Retroactive Application to Repository Domains

The operationalization criteria must reproduce prior domain assessments approximately correctly when applied without knowledge of the Watch B outcomes. This is the same retroactive check performed in `domain-maturity-operationalization.md`.

| Domain | Journal | Citation | Review | DAM | Composite PC |
|---|---|---|---|---|---|
| RC-041 Air Pollution | High | High | High | High | High |
| RC-036 Climate Attribution | High | High | High | High | High |
| RC-039 Vitamin A | High | High | High | High | High |
| RC-043 Dietary Sodium | High | High | Intermediate | High | High |
| RC-044 Alcohol | High | High | Intermediate | High | High |
| RC-045 Returns to Education | High | High | Intermediate | Intermediate-High | High (lean Intermediate) |
| RC-040 Minimum Wage | Intermediate | Intermediate | Low | Intermediate | Intermediate |
| RC-037 Lead-Crime | Intermediate | Low | Low | Low | Low |
| RC-038 Monetary Policy | Intermediate | Low | Low | Low | Low |
| RC-035 Industrial Policy | Intermediate | Low | Low | Low | Low |
| RC-042 Incarceration | Intermediate | Low | Low | Low | Low |

**Retroactive consistency check:**

High Prestige Coordination domains (Air Pollution, Climate, Vitamin A, Dietary Sodium, Alcohol, Returns to Education) all show Watch B minimal or Methodological — consistent with prestige coordination suppressing Theoretical Watch B. Low Prestige Coordination domains (Lead-Crime, Monetary Policy, Industrial Policy, Incarceration) all show Theoretical Watch B — consistent with prestige coordination absence leaving Watch B active.

*Critical observation:* The retroactive check reproduces the same pattern as the maturity gradient and as DAM scoring. All three variables (Maturity, DAM, Prestige Coordination) predict Watch B character in the same direction for every repository domain. This means the retroactive check does not tell us which variable is doing the causal work. That is the correlation structure this operationalization is designed to break.

**Returns to Education's position:** RC-045 scores Intermediate-High on DAM and High (lean Intermediate) on Prestige Coordination. The slight deviation from unambiguous High in both may explain why Watch B is Methodological (secondary) rather than Minimal — it is on the boundary. This observation is consistent with either CMech-001 or narrowed Alternative A, which is why the next test must more cleanly separate the two.

---

## The Correlation-Breaking Requirement

For Cycle 8 to provide diagnostic evidence, the target domain must have:

**Prestige Coordination: Low**
**DAM: Intermediate or higher**

This combination has not appeared in any repository domain to date. All Low Prestige Coordination domains also have Low DAM. If such a domain can be identified and audited, the result would for the first time allow CMech-001 and narrowed Alternative A to generate predictions that do not overlap:

| Domain profile | CMech-001 prediction | Narrowed Alt. A prediction |
|---|---|---|
| Low PC + Intermediate DAM | Watch B Methodological or weaker (DAM transforms) | Watch B Theoretical or Directional (PC absent → no suppression) |

A Watch B outcome in the Methodological range would support CMech-001 (DAM transforms without needing PC). A Watch B outcome in the Theoretical or Directional range would support Alternative A (PC needed, DAM insufficient alone). This is the only currently available design that allows one mechanism to lose.

---

## Application to Psychotherapy Effectiveness (Candidate for RC-046)

Pre-scored before claim evidence is reviewed:

| Indicator | Assessment | Score |
|---|---|---|
| Journal Structure | Multiple competing venues of roughly comparable prestige: JCCP, Psychotherapy Research, Behaviour Research and Therapy, British Journal of Psychiatry, Journal of Psychotherapy Integration, Depression and Anxiety; paradigm-specific journals exist for psychodynamic (PPAD), humanistic, and integrative traditions; no single journal functions as legitimacy certifier across traditions | Low |
| Citation Concentration | Multiple competing meta-analyst groups of roughly equal citation weight: Wampold (common factors, universal efficacy), Cuijpers (CBT primacy for depression), Shedler (psychodynamic efficacy), Hofmann (CBT superiority claims), Lambert (therapeutic alliance); mutual criticism is active, not merely parallel publication | Low |
| Review Body Convergence | Cochrane, NICE, APA Practice Guidelines, and independent academic meta-analyses reach different conclusions: NICE recommends CBT preferentially; Cochrane reviews by different teams reach different conclusions about specific modalities; APA Divisions (12 and 29) have reached contrary positions on specific modalities; the "Dodo Bird Verdict" (all therapies equivalent) vs. "CBT superiority" debate has not converged across review bodies | Low |
| DAM | Treatment manuals and adherence measures are named and consistently applied (CTS, CTRS for CBT; PQS for psychodynamic); randomized trial methodology is standard; network meta-analysis applied to comparative effectiveness; but no GBD-equivalent producing population-level attribution of mental health burden to therapy type | Intermediate |

**Psychotherapy Prestige Coordination Classification: Low** (3 Low indicators + 1 Intermediate DAM)

**Correlation break confirmed:** Low Prestige Coordination + Intermediate DAM. This combination has not appeared in any prior repository domain. The correlation-breaking test is available.
