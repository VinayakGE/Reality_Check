# RC-040: Minimum Wage and Employment Effects

**Claim:** "Minimum wage increases do not cause significant employment losses — and may in some cases increase employment — demonstrating that the standard competitive labor market model fails to describe low-wage labor markets."

**Sources:** David Card and Alan Krueger (1994), "Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania"; Arindrajit Dube, T. William Lester, Michael Reich (2010), "Minimum Wage Effects Across State Borders: Estimates Using Contiguous Counties"; Arindrajit Dube (2019), "Impacts of Minimum Wages: Review of the International Evidence" (UK Treasury); Doruk Cengiz, Arindrajit Dube, Attila Lindner, Ben Zipperer (2019), "The Effect of Minimum Wages on Low-Wage Jobs"

**Key formulations:**
- Card and Krueger (1994): Comparing New Jersey fast food employment before and after a $0.05 minimum wage increase to Pennsylvania as a control, "we find no indication that the rise in the minimum wage reduced employment" — employment in NJ fast food *increased* relative to PA.
- Dube, Lester, Reich (2010): Using contiguous county pairs across state borders, find "small and mostly insignificant employment effects for restaurant employment" from minimum wage increases, contrasting with earlier studies that found negative effects using comparisons between non-adjacent states.
- Cengiz et al. (2019): Using a bunching estimator across all US state minimum wage changes 1979–2016, find minimum wages "reduced the number of jobs paying below the new wage floor, but there was no significant change in the number of jobs paying just above the floor" — total low-wage employment barely changed.
- Neumark and Wascher (2000, 2008): Extensive review and meta-analysis finds "minimum wages reduce employment" particularly for low-skilled workers, teenagers, and in industries with high minimum wage coverage; estimate elasticities around -0.1 to -0.2 for teen employment.

**Status:** Unresolved
**Date:** 2026-06-24

---

## Cross-Audit Pre-Registration Reference

Prediction on record ([status/rc040-cross-audit-prediction.md](../status/rc040-cross-audit-prediction.md)), committed 2026-06-24 before this audit:

- **Primary object:** Attribution Precision Gap
- **Secondary object:** Watch B — present, secondary
- **Predicted absent:** Counterfactual Unavailability
- **Key rationale:** Intermediate-maturity domain; natural experiment literature has partially resolved Watch B (no catastrophic disemployment); but directional disagreement between research programs keeps Watch B active at the margin; APG (magnitude, hours, heterogeneity) is the primary frontier
- **Specific role:** Third post-operationalization prediction; Intermediate cell test; completes or breaks gradient under anti-circularity conditions

---

## Why This Claim Matters

The minimum wage debate is one of the most heavily studied questions in labor economics, with direct policy stakes for hundreds of millions of workers globally. The standard competitive model predicts that a price floor above the market wage creates unemployment; the claim asserts that this prediction fails in low-wage labor markets because monopsony power, search frictions, and efficiency wages make the labor market non-competitive.

If the claim is correct, minimum wage policy is a tool for reducing poverty and inequality without significant efficiency costs — the tradeoff the standard model predicts does not materialize. If the claim is wrong, minimum wage increases transfer income to employed workers at the cost of employment for the most marginal workers, raising equity questions about who benefits and who is excluded.

The claim also tests whether the natural experiment revolution in empirical economics has settled a previously theoretical dispute — and specifically whether the Card-Krueger methodology change generated a genuine empirical advance or a methodology-specific finding.

---

## Alternative Explanations

**H1 — Standard Competitive Model with Disemployment (Neumark-Wascher)**

In competitive labor markets, a binding minimum wage reduces employment by raising the cost of low-skilled labor above its marginal product. The effect is small for small increases (minimum wage slightly above market wage) and larger for larger increases. Neumark and Wascher (2008) review hundreds of studies and conclude the weight of evidence supports disemployment effects, particularly for teenagers, young adults, and workers with low skills. The effects are difficult to see in aggregate employment data because low-wage workers who lose jobs are a small fraction of total employment, but they are real and meaningful for affected groups.

*Watch B dimension:* If this model is correct, minimum wage increases do cause employment reductions; the Card-Krueger finding reflects specification errors, omitted variable bias, or selection of an unusually favorable comparison period.

**H2 — Monopsony / Search-Friction Model (Dube-Card)**

In low-wage labor markets characterized by employer market power (monopsony, oligopsony, or search frictions that limit worker mobility), firms set wages below the competitive equilibrium. A minimum wage that raises wages up to the competitive level does not reduce employment and may increase it, because the market was previously at a monopsonistic rather than competitive equilibrium. This model predicts that employment effects of minimum wage increases are small or zero for moderate increases, and that they may become negative only when the minimum wage exceeds the competitive equilibrium level.

*APG dimension:* Both this model and H1 agree minimum wage affects employment in principle. The dispute is about the sign and magnitude in the relevant range — which is an APG dispute about contribution shares and effect magnitudes.

**H3 — Specification/Comparison Group Heterogeneity**

Much of the apparent disagreement between research programs is methodological: which comparison groups are appropriate. Neumark and Wascher use broader state-level comparisons; Dube et al. use contiguous county pairs to control for local economic conditions. The two approaches find different results because they implicitly use different counterfactuals. The "true" effect depends on which comparison is valid — if contiguous counties are appropriate controls, Dube et al. are right; if broader comparisons are valid, Neumark-Wascher estimates are valid.

*APG and Watch B combined:* This explanation does not resolve the empirical question but explains why the methods produce different answers. Both research programs may be correctly estimating effects within their identification assumptions; the dispute is which identification assumption is valid.

**H4 — Heterogeneous Effects by Level and Context**

Effects may be zero or positive for small increases in tight labor markets and significantly negative for large increases or in weak labor markets. The Seattle minimum wage study (Jardim et al. vs. Reich et al.) illustrates this: two research teams studying the same policy found contradictory results using different data sources. Aggregate estimates may pool contexts where effects are zero with contexts where effects are negative, producing estimates that are correct on average but misleading for specific policy decisions.

*APG dimension:* The operative question becomes: in what contexts and at what levels do disemployment effects materialize? This is a precision question about heterogeneous treatment effects, not a causal-presence question.

---

## Evidence Supporting the Claim (No Significant Disemployment)

**Card and Krueger (1994) — founding natural experiment:** The NJ vs. PA comparison after NJ's 1992 minimum wage increase from $4.25 to $5.05 per hour produced the core finding: fast food employment in NJ increased relative to PA in the comparison period. The paper was methodologically influential for introducing the state-border comparison design into minimum wage research.

**Dube, Lester, Reich (2010) — contiguous county design:** Using contiguous county pairs across state borders from 1990–2006, DLR find that within contiguous-county pairs, minimum wage increases are associated with wage increases but not employment decreases in restaurant employment. Their design controls for local economic shocks more tightly than prior cross-state studies, which may have confounded minimum wage increases (which occur more in high-wage, tight-labor-market states) with state-level economic differences.

**Cengiz et al. (2019) — bunching estimator, comprehensive scope:** Covering all US state minimum wage changes from 1979–2016 using a bunching approach that estimates the distribution shift in wages, Cengiz et al. find that minimum wages raise wages for workers below the new floor but produce "no significant effect on the overall number of low-wage jobs." The study is methodologically distinct from both Card-Krueger and Dube et al.

**International evidence:** Minimum wage increases in the UK (following the 1999 introduction of the National Minimum Wage at a level many predicted would cause significant unemployment) did not produce the predicted disemployment. The UK experience is frequently cited as cross-country confirmation that moderate minimum wage increases do not destroy jobs.

**Meta-analyses consistent with small effects:** Doucouliagos and Stanley (2009) applied publication bias correction to the minimum wage literature and found that when publication bias is corrected for, the disemployment effect shrinks toward zero. This supports the view that the negative findings in older literature reflect publication bias rather than true effects.

---

## Evidence Against the Claim / Creating Doubt

**Neumark and Wascher meta-analysis (2008) — evidence for disemployment:** A comprehensive review of the pre-2010 literature finds that the majority of studies, particularly those using longer panel data and less restrictive specifications, find negative employment effects, especially for teenagers. Neumark, Salas, and Wascher (2014) directly critique the DLR contiguous-county design, arguing the comparison groups are not appropriate controls and that the apparent zero effects reflect specification choices.

**Seattle minimum wage study conflict (Jardim et al. vs. Reich et al.):** Two teams studied Seattle's 2015–2016 minimum wage increase. Jardim et al. (UW, using linked employer-employee tax data) found employment reductions in hours worked for low-wage workers, with an overall negative wage-bill effect. Reich et al. (UC Berkeley, using restaurant industry payroll data) found small positive employment effects. The same policy, same city, same time period — contradictory results depending on data source and methodology. This directly illustrates that identification choices, not just genuine effects, drive the divergent estimates.

**Heterogeneous effects for specific subgroups:** Several studies find that even when aggregate employment effects are small, effects on specific groups — teenagers, low-education workers, workers in high-minimum-wage jurisdictions — are more negative. If the minimum wage primarily benefits moderate-income households at the cost of employment for the most marginal workers, equity effects are more complex than the simple claim implies.

**Meer and West (2016) — long-run employment levels:** Using a different specification that allows for minimum wage effects on employment growth rather than levels, Meer and West find that minimum wages reduce the rate of employment growth over longer horizons. If the effect operates through reduced hiring rather than outright layoffs, cross-sectional studies focused on employment levels may systematically underestimate disemployment effects.

**Large increases — the unknown territory:** The Card-Krueger, DLR, and Cengiz et al. findings are mostly within the range of minimum wages that existed in the US through 2019 ($7.25 federal or modest state increases). The policy debate has moved toward $15 federal minimum wage and higher state rates. Whether zero-to-small effects at historical levels generalize to larger increases is genuinely unknown.

---

## Missing Evidence

**Clean resolution of the Seattle conflict:** The Jardim vs. Reich contradiction arose partly from different data sources (administrative tax records vs. commercial payroll data). A study that reconciles the two datasets and explains the divergence — rather than choosing sides — would substantially clarify whether the disagreement reflects genuine effect heterogeneity or data artifacts.

**Dose-response across minimum wage levels:** If disemployment effects are small at low minimum wage levels and larger at higher levels, there should be evidence of a threshold or nonlinearity. No study has convincingly identified where, if anywhere, this threshold lies. Studies at the frontier of current minimum wage levels ($15–$17) are emerging but not yet comprehensive.

**Employer pricing and wage-bill transmission:** If minimum wage increases are not transmitted to disemployment, they must be funded through some combination of higher prices, reduced profits, reduced non-wage benefits, or reduced hours. Studies that trace the full wage-bill transmission — not just employment headcounts — would clarify whether the claim's framing (no significant *employment* losses) is technically correct while obscuring costs in other dimensions.

**Heterogeneous labor market monopsony measurement:** The theoretical prediction from monopsony models is that effects depend on the degree of employer market power. If markets with measurable monopsony features (high concentration, low worker mobility) show systematically different minimum wage employment effects than competitive markets, that would validate the monopsony mechanism and explain the heterogeneous findings across studies.

---

## Current Status and Confidence

**Status: Unresolved**

The minimum wage employment effects debate is not settled. The natural experiment literature has credibly established that moderate minimum wage increases do not cause large, visible disemployment — the competitive model's strong prediction fails at the observed magnitudes. Whether effects are exactly zero, slightly negative, or slightly positive for the relevant range of increases is genuinely indeterminate from current evidence. Large increases (e.g., $15 federal) are inadequately studied.

---

## Watch Item Assessment

**APG — Primary: Confirmed.** The live scholarly frontier is about magnitude and direction of effect: how large is the disemployment effect, in which populations, at which minimum wage levels? Cengiz et al., DLR, and Card-Krueger cluster near zero or slightly positive; Neumark-Wascher cluster negative with elasticities around -0.1 to -0.2 for vulnerable subgroups. The Seattle conflict illustrates the precision problem starkly: same event, contradictory magnitude estimates. This is APG structure — accepted causal framework (minimum wage affects labor markets), disputed magnitude and sign.

**Watch B — Secondary, present: Confirmed.** Watch B does not fire at the "did minimum wages affect anything?" level — no one seriously argues minimum wages have zero effect on anything. But Watch B is genuinely present at a more specific level: the directional question for overall low-wage employment has not been settled. Neumark-Wascher and Dube-Card genuinely disagree on the *direction* of the effect on overall low-wage employment, not just its magnitude. Directional disagreement is Watch B territory — it is closer to "did the credited mechanism operate?" than to "how much?" A research program that asserts minimum wages reduce employment and a research program that asserts they do not reduce employment are in a Watch B dispute, not merely an APG magnitude dispute.

Watch B is secondary — not the dominant frontier — because: (1) the "no catastrophic disemployment" finding is robust across methods; (2) the directional dispute is about small effects, not presence/absence of any effect; (3) the mechanism (labor market non-competitiveness) is accepted by both research programs, which disagree on its quantitative significance. But Watch B is genuinely present, not merely residual.

This structure matches the pre-registration: APG primary, Watch B present as secondary.

**Counterfactual Unavailability — Absent: Confirmed.** Natural experiments (state-border, contiguous county, bunching estimator) explicitly construct counterfactual groups. The debate is about which counterfactual is valid — an APG/Watch B dispute about identification, not counterfactual unavailability.

**Sequential structure (behavioral test):** Sixth consecutive application. APG primary where Watch B is partially resolved; Watch B secondary where directional dispute remains. No re-derivation required.

---

## Domain-Maturity Hypothesis Assessment

**Prediction outcome: Confirmed.** Intermediate-maturity classification predicted APG primary, Watch B secondary. Both confirmed.

**Post-operationalization gradient — complete:**

| Maturity | Post-operationalization audit | Primary object |
|---|---|---|
| Low | RC-038 (Monetary Policy) | Watch B |
| Intermediate | RC-040 (Minimum Wage) | APG |
| High | RC-039 (Vitamin A) | APG |

The gradient has survived its first complete pass under independently committed maturity scores. All three levels predicted correctly; all three observed without circularity.

**What this adds:**

Era 2 is complete. The gradient exists and survives independent measurement at all three levels. Five predictions across two eras:

| | Era 1 | Era 2 |
|---|---|---|
| Low | RC-035 ✓ | RC-038 ✓ |
| Intermediate | RC-037 ✓ | RC-040 ✓ |
| High | RC-036 ✓ | RC-039 ✓ |

**What this does not establish:**

Six confirmations is not promotion. The gradient pattern has now survived the first operationalization-era test, but:
- The mechanism linking maturity to object dominance is still unspecified
- Boundary conditions for the operationalization criteria (when does a domain score Intermediate vs. Low or High?) are not formally specified
- The Intermediate cell was the last to be confirmed — the gradient could have failed here and the failure would have been interpretable, which is exactly the condition the checkpoint was designed to enable
- The two-era structure now shows all six cells correct, but Era 2 has only three observations

---

## The Watch B / APG Boundary — Minimum Wage as a Diagnostic Case

The minimum wage literature is useful as a boundary case because the Watch B and APG structures are unusually visible and separable.

The Watch B question: *Did minimum wage increases cause disemployment?* Research programs genuinely disagree on direction, not only magnitude. This is the clearest Watch B dimension in the minimum wage debate.

The APG question: *How large are the effects — for which workers, at which wage levels, in which labor markets?* The heterogeneous effects literature (teenagers vs. prime-age workers, competitive vs. monopsonistic markets, small vs. large increases) is an APG dispute about contribution shares under different conditions.

The sequential structure applies: APG is active because causal presence (minimum wage affects labor markets) is accepted; Watch B is secondary because the directional question (does it increase or decrease employment?) is live but not the primary research frontier.

---

## Ledger Entry

**APG:** Confirmed primary at Intermediate maturity, second time at this level (RC-037 first, RC-040 second). APG now confirmed across all three maturity levels in Era 2.

**Watch B:** Present as secondary in Intermediate domain. Pattern across maturity levels: dominant at Low, secondary at Intermediate, minimal at High — confirmed in both eras.

**Domain-maturity hypothesis:** Six predictions correct; three under independent measurement; Era 2 complete. First complete post-operationalization gradient. Not promotable — mechanism unspecified, boundary conditions unspecified — but the evidential base for the pattern is materially stronger than at Checkpoint #008.

**Sequential Watch B→APG structure:** Sixth consecutive application across six different evidentiary domains. Established operational behavior; no longer requires tracking as a watch item.
