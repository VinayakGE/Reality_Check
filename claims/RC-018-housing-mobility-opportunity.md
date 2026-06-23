# Reality Check #018

## Claim

> "Policies that enable low-income families to move to lower-poverty areas, such as housing voucher programs, have the potential to substantially improve children's long-term outcomes."

## Source

- Speaker: Raj Chetty, Nathaniel Hendren, Lawrence Katz
- Organization: Harvard University / Opportunity Insights
- Date: May 2016 (*American Economic Review*, "The Effects of Exposure to Better Neighborhoods on Children")
- Link: https://opportunityinsights.org/paper/newmto/

*Note: The scientific claim above is Chetty et al.'s own framing of their findings. The policy inference — that expanding housing vouchers to all eligible low-income families would produce the observed outcomes at scale — is drawn from the paper's policy implications section and subsequent policy advocacy by Chetty and co-authors. The distinction between the experimental finding and the universal policy inference is the primary evaluation problem in this audit.*

---

## Why This Matters

The Moving to Opportunity (MTO) experiment ran from 1994 to 1998, randomly assigning approximately 4,600 low-income families in five US cities to receive housing vouchers. Chetty et al.'s 2016 follow-up tracked participants for 20 years, finding that children who moved before age 13 earned 31% more as adults and were more likely to attend college and live in higher-income neighborhoods than children in the control group. This is among the largest experimentally identified neighborhood effects on long-run outcomes in the economics literature.

The policy inference drawn from MTO is now shaping federal housing policy. The Biden administration's Housing Choice Voucher program expansion, HUD's Mobility Works demonstration, and multiple municipal housing programs (Seattle, Chicago, Minneapolis) have cited MTO results as justification for expanding housing mobility initiatives. If the MTO findings generalize to a universal program, housing mobility vouchers represent one of the highest-return social investments available to US policymakers. If they do not generalize, the expansion rationale is based on pilot results that cannot be reproduced at scale.

---

## Watch Items

**Watch A:** Does this claim's structure match any prior structure in the repository?
**Watch B:** Does the evaluation bottleneck recur? Where does uncertainty appear?

**Note:** RC-018 is the second consecutive pilot-to-policy inference claim, following RC-017 (UBI/cash transfers). If the structure matches, this would be the first Watch A instance in the repository — the first clean structural repeat across 18 audits. This is noted before the Watch Item Assessment to flag the significance of the finding.

---

## Alternative Explanations

### H1 — The MTO findings are robust and generalize: expanded housing vouchers would produce similar outcomes at scale
The causal identification in MTO is unusually strong — lottery assignment to vouchers eliminates selection bias, and the 20-year follow-up period captures genuine long-run outcomes rather than short-term adjustments. The mechanism is well-understood: younger children benefit most because they spend formative years in lower-poverty environments with better schools, safer streets, and stronger social networks. The effect size (31% earnings increase for young movers) is large enough to survive downward adjustment for imperfect generalization. Expanding the program does not require the mechanism to change — it requires more vouchers and more landlord participation. These are administrative constraints, not causal limits.

### H2 — Universal expansion would change the neighborhood composition that makes the program work
The MTO experiment moved approximately 4,600 families out of high-poverty areas — a small fraction of the eligible population. At universal scale, large numbers of low-income families moving to high-opportunity areas would change those areas: schools would become more crowded, housing demand would increase rents, and the characteristics that produced MTO's outcomes (low poverty rates, high-quality schools, strong social capital) would attenuate. The experiment's outcomes may depend on moving into a neighborhood whose characteristics are fixed; universal expansion would change those characteristics. This general equilibrium effect does not appear in a small pilot precisely because the pilot is too small to move equilibrium prices and compositions.

### H3 — The bottleneck is not causal mechanism but program implementation at scale
Even if the mechanism generalizes perfectly, expanding housing mobility vouchers nationally faces implementation constraints that do not exist in pilots: landlord refusal rates (currently 40–70% of voucher holders cannot find accepting landlords in high-opportunity areas), zoning and land use restrictions that limit housing supply in high-opportunity neighborhoods, and political resistance from existing residents. The question is not whether moving to opportunity works — it does — but whether the voucher instrument can successfully place families in the high-opportunity neighborhoods required for the mechanism to operate. If voucher holders cannot actually move to high-opportunity areas due to supply constraints and landlord discrimination, the policy does not fail because the mechanism is wrong; it fails because the instrument cannot deliver families to the required destination.

---

## Evidence Supporting the Claim

- MTO lottery results, 20-year follow-up (Chetty et al., *AER* 2016): children who moved before age 13 showed 31% higher earnings as adults; the effect was driven by time spent in lower-poverty neighborhoods, consistent with cumulative exposure mechanism
- Mental health outcomes from MTO (Kling, Liebman, Katz, *Econometrica* 2007): young girls showed significant reductions in anxiety and depression; boys showed mixed results — a nuanced finding rather than a null one
- Seattle Housing Levy's Moving to Work program: expanded mobility vouchers with landlord incentives increased voucher utilization in high-opportunity areas; early results show improved school outcomes for children in the first cohort
- Opportunity Atlas (Chetty et al., 2018) demonstrates that neighborhood-level variation in intergenerational mobility is large, stable across generations, and causally linked to childhood exposure — providing the theoretical and empirical foundation for the mechanism
- The mechanism is causal at the individual level: the lottery design means MTO findings cannot be attributed to selection effects; children who moved outperformed their siblings who did not move, providing within-family causal identification

## Evidence Against the Claim

- MTO's total treatment population (4,600 families) is approximately 0.1% of households currently eligible for housing vouchers — far below the scale required to test general equilibrium effects; the evidence base supports the mechanism in a small-scale context but cannot speak to scale-up effects
- Voucher utilization crisis: HUD data show that 25–45% of households issued housing vouchers in high-demand markets fail to use them because landlords in high-opportunity areas decline to participate; the gap between "receiving a voucher" and "moving to a high-opportunity neighborhood" is large and not primarily addressed by the MTO evidence
- Age sensitivity of the effect: Chetty et al. find the earnings benefit concentrated almost entirely in children who moved before age 13; children who moved older showed no significant benefit, and adults who moved showed no earnings improvement. Universal programs that move families at all ages would produce substantially smaller average effects than the MTO follow-up suggests
- Reanalysis by Rothstein (2019) questions whether the earnings gains in MTO persisted across all subgroups or were concentrated in specific demographics — the headline 31% figure may overstate the average effect across the full eligible population
- No pilot has tested what happens to the destination neighborhood when 10x, 50x, or 100x as many low-income families move in — the experimental design by definition prevents observing this

---

## Missing Evidence

- A program at 10x–50x MTO's scale that would allow observation of whether neighborhood characteristics are stable at higher volumes of low-income inflows — this evidence cannot be obtained without implementing the program at scale
- Landlord participation rates under a universal program with stronger incentives: HUD's current landlord incentive programs are small pilots; their scale-up potential is untested
- What happens to the earnings gains when destination neighborhoods receive substantially higher inflows of voucher holders than MTO destination neighborhoods received — this is the direct test of H2's general equilibrium concern, and it does not exist

---

## Current Status

- [ ] Supported
- [x] Unresolved
- [ ] Currently Unresolvable

---

## Confidence

**Medium-High (on the pilot finding) / Low-Medium (on universal generalization)**

Reason: The pilot finding — lottery-assigned housing mobility produces large, long-run earnings gains for young children — is among the strongest causally identified results in applied economics. Confidence in the pilot finding is Medium-High. The generalization to a universal program involves three distinct concerns (general equilibrium neighborhood effects, voucher utilization constraints, age composition of a universal program vs. young-family-concentrated pilot) none of which have been empirically tested at the relevant scale. Confidence in the generalization is Low-Medium.

The confidence split has the same structure as RC-017 (UBI): high confidence in the experimental finding, lower confidence in the policy inference. The gap in both cases is the generalization step, not the mechanism itself.

---

## Watch Item Assessment

**Watch A (does the structure repeat?):**

**First clean structural repeat in the repository. Watch A count moves.**

RC-018 has the same structure as RC-017:

| Feature | RC-017 (UBI) | RC-018 (MTO) |
|---|---|---|
| Experimental evidence with control group | Yes (multiple RCTs) | Yes (lottery assignment) |
| Mechanism identified at pilot scale | Yes | Yes |
| Policy claim at universal scale | Yes | Yes |
| Universal-scale counterfactual | Unavailable | Unavailable |
| Bottleneck location | Generalization, not causal ID | Generalization, not causal ID |
| Watch B triggered | No | No (see below) |

Structure: **Pilot-to-policy inference claim.** RC-017 and RC-018 share this structure. After 17 consecutive audits with zero structural repeats, RC-018 produces the first one.

The distinction from prior structures that might look similar:
- RC-004 (India 500GW): government commitment claim, not experimental pilot inference
- RC-013 (Hall RCT / UPF): contributory cause claim overstated to primary causation, not pilot-to-policy inference
- RC-009 (China lost decade): analogical prediction, not experimental pilot generalization

The "pilot-to-policy inference claim" structure involves: (1) causally identified evidence at test scale, (2) universal policy claim at a scale where the counterfactual is unavailable, and (3) the primary uncertainty located at the generalization step rather than the causal identification step. Both RC-017 and RC-018 fit this precisely.

**Watch A count: 1 structural repeat (RC-017 and RC-018). First movement after 17 audits.**

**Watch B (does the bottleneck recur?):**

Watch B does not fire in RC-018, for the same reason it did not fire in RC-017.

The primary uncertainty is not "outcome visible, cause uncertain." The pilot outcome is visible and its cause is well-identified. The primary uncertainty is "can the pilot mechanism survive the generalization step?" — which is about transferability, not causal attribution.

The specific bottleneck in RC-018 is **implementation transferability** — the mechanism is causally established at pilot scale but the instrument (housing vouchers) may not successfully deliver families to the required conditions (high-opportunity neighborhoods) at universal scale, due to landlord refusal, supply constraints, and general equilibrium effects on destination neighborhoods.

This is distinct from prior Watch B instances in a specific way: prior Watch B instances had observable outcomes whose causes were contested. RC-018's uncertainty is upstream of the outcome — the bottleneck is whether the intervention can be implemented in the form required for the mechanism to operate, not whether the mechanism is correct.

**Watch B count: still 7.** Two consecutive Type B audits (RC-017, RC-018) without triggering Watch B.

**Type A / Type B dependency update:**

| Type | Count | Watch B |
|---|---|---|
| Type A (event occurred, counterfactual world missing) | 3 (RC-010, RC-015, RC-016) | 3/3 |
| Type B (event not occurred at policy scale, outcome unavailable) | 2 (RC-017, RC-018) | 0/2 |

Two Type B audits without Watch B is a meaningful pattern. The dependency has now been tested twice at Type B and has not fired either time. The bottleneck in both cases was located at the generalization/transferability step, not the outcome-cause attribution step.

**Additional observation:** RC-017 and RC-018 together suggest a new bottleneck type that is not Watch B and is not counterfactual unavailability (as previously understood):

**Transferability bottleneck** — causally identified evidence exists at tested scale; universal policy claim extends beyond tested scale; primary uncertainty is whether mechanism survives the generalization step. This bottleneck is located upstream of any observable outcome, which is why Watch B does not fire.

This is not yet a watch item. It is recorded as an emerging observation: two instances, both Type B, both with transferability as the primary bottleneck.

---

## Open Questions

1. The Watch A structural repeat (RC-017 + RC-018 = pilot-to-policy inference claim) is the first in 18 audits. Does a structure need to appear in three audits, or in two audits across separate cycles, to be promoted beyond "tentative"? The current repository has no promotion rule for structural recurrences.

2. RC-017 and RC-018 both have a "transferability bottleneck" that is distinct from Watch B. If RC-019 or RC-020 also has this bottleneck type, should it be tracked separately from Watch B? The generating structure is different (upstream of observable outcome rather than downstream) but the effect is similar (causal inference blocked). Does the upstream/downstream location matter?

3. The age-sensitivity finding in MTO (children who moved after age 13 showed no earnings benefit) suggests the effect is developmental-window-specific. A universal housing voucher program would move families at all ages, not just those with young children. Should Reality Check flag claims where the eligible population for a universal program has a different demographic composition than the pilot population? This is a specific form of the generalization problem that could apply to multiple claims in the repository.

---

## Ledger Entry

Claim Status: Unresolved
Date Assessed: 2026-06-23
Next Review: HUD Mobility Works national expansion results (expected 2026–2028); publication of long-run outcome data from Seattle or Chicago mobility programs; or any national housing voucher utilization rate study at 2x+ current scale
Reviewer: Reality Check
