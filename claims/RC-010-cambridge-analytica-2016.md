# Reality Check #010

## Claim

> "We built, for the Trump campaign, a psychographic profile of every single adult in the United States of America — 220 million people — and based on this, we were able to determine how to speak to each of these personalities. This is how Donald Trump became President of the United States."

## Source

- Speaker: Alexander Nix
- Organization: Cambridge Analytica
- Date: September 27, 2016 (Concordia Annual Summit, New York)
- Link: https://www.concordia.net/annual-summit/2016

---

## Why This Matters

This is the tenth Reality Check audit and the test case for whether some claims are permanently indeterminate even after reality has had time to answer them. The 2016 US presidential election resolved on November 8, 2016. Cambridge Analytica dissolved in May 2018. Alexander Nix was banned from serving as a company director in the UK. Multiple government investigations in the US and UK examined CA's activities. The outcome is known. The deadline has passed. And yet the central causal claim — that CA's psychographic targeting *caused* Trump to win — may be genuinely unanswerable. Not because evidence is missing. Because the counterfactual required to establish causation does not exist and cannot be constructed.

---

## Alternative Explanations

### H1 — The claim is correct: CA's targeting was causally decisive
Trump won three key states (Pennsylvania, Michigan, Wisconsin) by a combined margin of approximately 77,000 votes. CA targeted these states with psychographic messaging. Narrow margins in historically Democratic states are consistent with a highly targeted persuasion campaign having a decisive effect. Without CA, Trump loses these states and the election.

### H2 — The claim is a marketing pitch: CA targeted voters who were already moving toward Trump
The states CA targeted were already trending Republican based on economic anxiety and white working-class demographic shifts that predate and are independent of CA's intervention. CA's targeting confirmed existing sentiment rather than changing it. The correlation between CA's activity and Trump's victory is real; the causal claim is false. This is the "post hoc ergo propter hoc" version of the claim.

### H3 — The claim is irrelevant because the mechanism didn't work as advertised
Multiple academic studies after 2016 found little to no evidence that psychographic targeting (the OCEAN personality model applied to Facebook data) produces measurable vote changes. Cambridge Analytica's methodology was not validated by peer review, its Facebook data access (acquired through the Kogan personality quiz) covered fewer unique voters than claimed, and the "230 million psychographic profiles" figure was inflated. The question of whether CA was decisive may be permanently undecidable not because causation is hidden but because the mechanism itself was not real enough to measure.

---

## Evidence Supporting the Claim

- Cambridge Analytica contracted with the Trump campaign and was active in the final months of the 2016 election — the relationship existed and was paid
- Steve Bannon (CA board member) was central to Trump's campaign strategy, creating a direct line between CA's data work and campaign decision-making
- Facebook's own internal research (revealed in subsequent congressional testimony) confirmed that targeted political advertising reaches voters in ways that correlate with persuasion metrics
- Trump's victory in three states by narrow margins is consistent with a targeted intervention having tipped the outcome, even if it does not prove it did

## Evidence Against the Claim

- The Senate Intelligence Committee and the House Intelligence Committee investigations found no direct evidence that CA's data work was decisive — both found evidence of Russian interference but did not attribute the election outcome to CA's targeting
- Academic researchers who examined CA's methodology (including those with access to the underlying Facebook data after Meta's research disclosures) found that psychographic targeting did not show measurable persuasion effects distinguishable from baseline demographic targeting
- Nix's claim was made in September 2016 — before the election — as a sales pitch to prospective clients at a conference. The boast was a business development presentation, not a post-election analysis
- CA made similar claims about its role in Brexit, Ted Cruz's primary campaign, and multiple other elections simultaneously — claiming decisive credit for all of them simultaneously is mathematically impossible
- CA filed for insolvency in May 2018 after the Channel 4 undercover investigation, which showed Nix claiming CA used entrapment and disinformation tactics. The company's behavior after this suggests it was not operating as a legitimate data firm making verifiable claims

---

## Missing Evidence

Evidence that exists but cannot establish causation:

- CA's internal targeting files and delivery metrics (partially obtained by the ICO in the UK) show what voters were targeted; they cannot show what those voters would have done without targeting
- Post-election surveys of swing-state voters in PA, MI, WI show voting behavior and stated reasons for their votes; survey data cannot isolate the CA effect from the thousands of other campaign touchpoints
- Facebook's ad delivery data for the 2016 election exists and was provided to Congress; it shows impressions and engagement, not vote changes attributable to specific ad content

**The missing evidence in this audit is not missing because it wasn't collected. It is missing because it cannot exist. The counterfactual — Trump's 2016 campaign without Cambridge Analytica — was never run. No data collection could have captured it. The evidence gap is structural, not circumstantial.**

---

## Current Status

- [ ] Supported
- [ ] Unresolved
- [x] Currently Unresolvable

**First use of "Currently Unresolvable" in the repository — but for a different reason than the category implies.**

The original template included "Currently Unresolvable" alongside "Supported" and "Unresolved." It appeared, implicitly, to describe claims that *could not yet* be evaluated — claims waiting on future evidence. No audit in RC-001 through RC-009 used it, because every unresolved claim had at least some future evidence that could, in principle, change the assessment.

RC-010 uses "Currently Unresolvable" — but for a different reason. The election is over. The deadline passed. The evidence was collected. The investigation was conducted. And the claim is *still* not decidable, because establishing "CA caused Trump to win" requires a counterfactual that can never be run.

This is not "currently unresolvable" in the sense of "waiting for future data." It is permanently indeterminate. The distinction between "evidence hasn't arrived yet" and "counterfactual cannot be constructed" is a meaningful one that the current status vocabulary does not capture. Both map to the same checkbox.

---

## Confidence

**High — that the claim is Currently Unresolvable. Low — on whether H1, H2, or H3 is closest to true.**

Reason: The most confident statement this audit can make is about the *decidability* of the claim, not its truth value. Whether CA was decisive is not answerable from available evidence. This is not a failure of investigation — multiple serious investigations examined it. It is a structural feature of the causal question. Claims about what *caused* a binary event with a narrow margin, where the causal factor cannot be isolated, may be a class of claims that Reality Check cannot adjudicate.

H3 deserves specific attention: if CA's methodology was not empirically valid, the claim was never testable in the first place — not because the election didn't resolve, but because the mechanism being claimed was not a real mechanism. This is a different kind of "currently unresolvable" than a valid mechanism with an unmeasurable effect.

---

## Review Trigger

None. The event is over. Further investigation would not change the structural inability to establish counterfactual causation. A review would be warranted only if a new methodology for retroactively estimating persuasion effects at the individual voter level became available — which is not anticipated.

---

## Open Questions

1. "Currently Unresolvable" in the original template was presumably intended for claims like "is there life on Mars" — claims that await future evidence. RC-010 finds a different use: claims where the event has occurred but the causal question cannot be established because the counterfactual is unavailable. Should these be the same status, or does the distinction matter?
2. H3 raises a more disturbing possibility: some claims are not just causally unresolvable but *mechanism-invalid* — the causal process being asserted was never real enough to measure. Does a claim with an invalid mechanism belong in "Currently Unresolvable," or in a different category entirely?
3. RC-007 found that prediction and mechanism can resolve on different timelines. RC-009 showed the split can be visible at entry. RC-010 shows a claim where the mechanism may have been fictitious from the start and the prediction (Trump won) is trivially true for unrelated reasons. Is this a third structure, or a degenerate case of the prediction/mechanism split?

---

## Ledger Entry

Claim Status: Currently Unresolvable (permanently — not awaiting future evidence)
Date Assessed: 2026-06-23
Next Review: None. Structural indeterminacy, not evidential gap.
Reviewer: Reality Check
