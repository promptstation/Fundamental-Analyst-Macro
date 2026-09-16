---
name: section-10-macroeconomics-regression-diagnostics
description: Develop comprehensive, professional-level learning modules and training materials on regression Diagnostics — When Assumptions Break within Macroeconomics & Econometrics — diagnose broken assumptions through heteroskedasticity (detection tests, robust errors, WLS), autocorrelation (DW and Breusch-Godfrey, HAC corrections, the spurious-regression bridge to unit roots), multicollinearity (VIF diagnostics, variance versus instability distinction, remedy hierarchy), non-normality.... Use this skill whenever the user asks to create, teach, or deepen training on regression, diagnostics, assumptions, break, macroeconomics and econometrics, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Fundamental Analyst course 01, section 10)
  version: 1.0.0
  category: professional-education
---

# Regression Diagnostics: When Assumptions Break — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **regression Diagnostics: When Assumptions Break** within The macroeconomic and econometric foundation of the futures fundamental analyst discipline — how interest rates, inflation, GDP, and central bank policy drive global capital flows, and how predictive statistical models quantify the correlations between these variables over time.

Subject scope: Covers the diagnostic toolkit for detecting and correcting the assumption violations that plague macro data: heteroskedasticity (the non-constant-variance reality of cross-section and some macro series where OLS stays unbiased but standard errors fail; the White and Breusch-Pagan detection tests; the robust-standard-error corrections of the White and Huber lineage with the small-sample cautions; the weighted-least-squares alternative when the variance structure is known); autocorrelation (the serial-correlation ubiquity in macro time series where consecutive observations share trend and cycle components; the Durbin-Watson and Breusch-Godfrey detection with the lag-order selection; the consequences split where coefficient bias is absent under strict exogeneity but inference collapses; the Newey-West HAC corrections for autocorrelation-and-heteroskedasticity-robust inference; the spurious-regression danger where trending series produce significant relationships from common trends alone, the bridge to the unit-root theory of the next section); multicollinearity (the high-correlation reality of macro aggregates where inflation, rates, and activity variables move together; the variance-inflation diagnostics; the distinction between harmless collinearity inflating variance and pathological near-singularity destabilizing estimates; the remedy hierarchy where more data beats variable-dropping in most cases); non-normality and heavy tails (the residual-distribution checks with skew and kurtosis measures and the Jarque-Bera test; the fat-tail reality of financial and macro data where crisis observations dominate tail behavior; the normality-relevance clarification where inference depends on large-sample approximations rather than exact normality; the robust-regression alternatives for genuinely contaminated errors); specification failures (the RESET-style functional-form tests; the omitted-variable probing through residual correlation analysis; the parameter-stability tests including Chow tests for known breakpoints and the CUSUM monitoring for unknown drift; the structural-break taxonomy distinguishing abrupt regime shifts from gradual evolution, with the break-dating methods that connect to the regime framework of the cycle section); endogeneity and simultaneity (the reverse-causality detection through timing and economic logic; the simultaneous-equations bias where market-clearing data mixes supply and demand shifts, the identification problem in its classic commodity form; the Hausman-test logic for endogenous-regressor detection; the two-stage-least-squares remedy with the instrument-validity requirements and weak-instrument diagnostics); the diagnostic workflow (the residual-plot-first habit where visual inspection precedes formal tests; the test-battery discipline running the standard suite on every specification; the remedy-sequencing logic where data problems get fixed before model problems; the documentation requirement recording diagnostics and decisions in the specification log from the previous section); and the macro-data-specific traps (the preliminary-versus-revised data divergence where diagnostics on final vintages misrepresent real-time conditions; the seasonal-adjustment residue where adjustment artifacts create autocorrelation patterns; the aggregation-induced heterogeneity where national estimates mask regional variation; the look-ahead bias in real-time analysis where later information leaks into predictors through revisions and benchmark restatements) together with the section anti-patterns — the failure library: the blind-OLS runner who never plots residuals and ships invalid inference, remedied by the residual-first workflow; the HAC-washing practitioner who applies robust standard errors to fix a misspecified model, remedied by the remedy-sequencing logic; the spurious-regression publisher who celebrates R-squared of 0.9 between two trends, remedied by the unit-root literacy and detrending discipline; the VIF-panic dropper who removes collinear variables destroying the theoretical structure, remedied by the harmless-versus-pathological distinction; the Chow-test fisher who searches breakpoints until stability fails somewhere, remedied by the multiple-testing discipline; and the real-time ignoramus whose diagnostics run on vintages unavailable when trades were placed, remedied by the vintage-aware practice with detection methods as the diagnostic.

Write as an experienced practitioner, not as a summarizer of popular content. Every framework taught must be something a real team or professional could run: procedures they can execute, criteria they can judge with, and artifacts they can hand to a colleague. Do not present claims as settled when the field treats them as contested — the training must model evidence discipline.

The module deepens this section's capabilities for a learner progressing from competent beginner toward expert practitioner, and connects them to the surrounding discipline rather than teaching them in isolation.

## Use Cases

### Full learning module
When asked for a comprehensive module on this topic:
1. Scope audience, prerequisites, duration, and discipline mix.
2. Build the evidence base from the authoritative sources below.
3. Write the full progressive module from the template.
4. Include all exercises with model solutions and all gate checklists.
5. Validate against the gate below before delivery.

### Condensed workshop
When asked for a one-day or half-day workshop:
1. Prioritize the units that match where the group is stuck.
2. Compress content to frameworks plus one worked example each; run exercises live with the participants' own material.
3. Leave behind the relevant checklists as job aids.

### Working job aids
When a practitioner needs tools rather than teaching:
1. Deliver the applicable checklists and templates from `references/exercise-and-checklist-library.md`, customized to their situation.
2. Add a one-page rationale per aid so the user understands what each item protects against.

## Core Output Requirements

- Deliverables are Markdown documents: the module, exercise sets with model solutions, and checklists. No placeholders, no "TODO" sections.
- Ground content in authoritative sources:
- The standard macroeconomics canon (the Blanchard-Fischer and Mankiw textbook traditions, the IS-LM and AD-AS lineage, the modern New-Keynesian synthesis with its microfoundations and rational-expectations heritage)
- The national-accounts and price-measurement systems (the SNA framework, the BEA and BLS statistical handbooks, the CPI and PCE construction methodologies)
- The central-bank literature (Federal Reserve, ECB, and BIS publications, the Taylor-rule tradition, the forward-guidance and quantitative-easing research)
- The econometrics canon (the Greene and Wooldridge textbook traditions for cross-section and panel methods, the Hamilton and Enders lineage for time-series econometrics)
- The forecasting literature (the Diebold and Clements traditions, forecast-evaluation methodology, the nowcasting research from the New York Fed and ECB)
- The business-cycle tradition (the NBER dating methodology, the leading-indicator systems from the Conference Board lineage, the financial-conditions-index literature)
- The market-macro interface research (the macro-finance literature connecting policy shocks to rates, FX, and equity-index futures pricing, the event-study tradition for data releases)
- Maintain an evidence ledger while writing: every factual claim or number is either sourced, flagged as disputed/popular account, or omitted. Never invent statistics, studies, or citations.
- Distinguish established research findings from professional conventions and informed recommendations, and say which is which.
- Explain each specialized term in clear language on first use.

## Module Development Workflow

### Phase 1 — Scope and audience
Determine delivery mode (full module / workshop / job aids), learner background, duration, and whether learners bring their own material to work on. Record these choices; they drive depth allocation in Phase 3.

### Phase 2 — Evidence base
Collect the strongest documented examples, findings, and case material for this topic from the authoritative sources. Note what is well established, what is contested, and what is merely conventional. Verify any numbers before publishing them.

### Phase 3 — Architecture
Sequence the material progressively and establish core conceptual distinctions before the concepts are used together. Suggested unit sequence:

1. Unit 1

### Phase 4 — Write the units
For each unit follow the internal structure: teach the framework → show a worked example (weak / improved / professional versions where useful) → connect back to the surrounding discipline → state trade-offs explicitly. Use `references/domain-content-map.md` as the unit-by-unit source of scope, bullets, and evidence guidance.

### Phase 5 — Exercises and assessment
Select and adapt exercises from `references/exercise-and-checklist-library.md`. Adapt scenarios to the audience's domain. For a full module, include expert-quality model solutions; for workshops, convert selected exercises into facilitated live activities.

### Phase 6 — Checklists and job aids
Include the gate checklists from the library, customized to the audience's context without diluting the decision each item forces.

### Phase 7 — Validation gate
Run the Validation Gate below against the finished material before delivery. Fix failures; do not ship and caveat.

## Module Template

ALWAYS use this exact template for full modules:

```markdown
# Regression Diagnostics: When Assumptions Break [— audience/context subtitle]

## Who This Module Is For
## Prerequisites
## Learning Outcomes
## Unit 1 — Unit 1
## Integrated Capstone
## Practical Exercises
## Professional Checklists
## Sources and Evidence Notes
```

Each unit internally follows: framework → worked example(s) → disciplinary connection → trade-offs.

## Writing Standards

Throughout the material, prioritize language that is:

* Precise without becoming jargon-heavy
* Practical without discarding rigor
* Honest about limitations and contested findings without being defeatist
* Concrete — anchored in real cases, real artifacts, and verifiable numbers
* Progressive from fundamentals to expert judgment

Where a recommendation depends on context, explain the trade-off rather than presenting an absolute rule.

## Validation Gate

Before delivery, verify:

### Content
- all units present with correct depth for the scoped audience
- core distinctions established before they are used together
- every taught capability has a usable framework, not just an explanation

### Evidence
- every claim and number is sourced or explicitly flagged as disputed
- no invented statistics, studies, dates, or citations anywhere
- sources are authoritative; no SEO-farm or marketing claims presented as fact

### Capability
- each absorbed capability (1 in this section) is covered by teaching content AND at least one exercise with evaluation criteria
- exercises have model solutions in full-module mode

### Artifacts
- all gate checklists included and actionable as written
- template structure followed; no placeholder sections

### Quality
- trade-offs stated wherever recommendations are context-dependent
- terminology explained on first use
- reads as practitioner-written, not generic AI advice

## Anti-Patterns

Avoid: Model worship — trusting regression output without interrogating specification, data quality, and structural stability, letting statistical significance masquerade as economic truth; Revision blindness — analyzing first-print data as final and never restating conclusions when official statistics revise, producing a research record that silently rewrites history; Correlation-as-transmission — reading historical co-movement between macro variables and futures prices as a causal channel, then getting run over when the relationship breaks under regime change; Consensus anchoring — positioning against the print rather than the expectation, forgetting that markets trade surprises versus priced-in forecasts, not absolute data levels; Indicator spaghetti — stacking dozens of overlapping indicators into an unfalsifiable composite view where every regime has some confirming signal and none has a falsifying one; exercises without evaluation criteria; modules that stop at inspiration without a single decision the learner can now make better; and any content that overstates certainty beyond what the evidence supports.

## Decision Heuristic

When allocating depth under time or length limits, ask:

1. Where will this audience actually stall in practice?
2. Which unit protects the most value if taught well?
3. Can the learner run the framework tomorrow without me?
4. Is every example doing work a plain sentence could not?
5. What would a skeptical domain expert say about this material?

If two topics compete for space, keep the one that changes a decision.

## Final Principle

The goal is not more content about macroeconomics and econometrics. The goal is that a practitioner could take this material and perform: Diagnose broken assumptions through heteroskedasticity (detection tests, robust errors, WLS), autocorrelation (DW and Breusch-Godfrey, HAC corrections, the spurious-regression bridge to unit roots), multicollinearity (VIF diagnostics, variance versus instability distinction, remedy hierarchy), non-normality (residual distribution checks, fat-tail reality, robust alternatives), specification failures (RESET, omitted-variable probing, Chow-CUSUM stability tests, break taxonomy and dating), endogeneity (reverse causality, simultaneous-equations bias, Hausman logic, 2SLS with weak-instrument diagnostics), the diagnostic workflow (residual-first, test batteries, remedy sequencing, documentation), and macro-specific traps (revision divergence, seasonal residue, aggregation heterogeneity, look-ahead bias), avoiding blind OLS, HAC washing, spurious publishing, VIF panic, Chow fishing, and real-time ignorance failures, Diagnose broken assumptions through heteroskedasticity (detection tests, robust errors, WLS), autocorrelation (DW and Breusch-Godfrey, HAC corrections, the spurious-regression bridge to unit roots), multicollinearity (VIF diagnostics, variance versus instability distinction, remedy hierarchy), non-normality (residual distribution checks, fat-tail reality, robust alternatives), specification failures (RESET, omitted-variable probing, Chow-CUSUM stability tests, break taxonomy and dating), endogeneity (reverse causality, simultaneous-equations bias, Hausman logic, 2SLS with weak-instrument diagnostics), the diagnostic workflow (residual-first, test batteries, remedy sequencing, documentation), and macro-specific traps (revision divergence, seasonal residue, aggregation heterogeneity, look-ahead bias), avoiding blind OLS, HAC washing, spurious publishing, VIF panic, Chow fishing, and real-time ignorance failures — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
