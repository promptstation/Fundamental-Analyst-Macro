---
name: section-11-macroeconomics-time-series-econometrics
description: Develop comprehensive, professional-level learning modules and training materials on time-Series Econometrics — Stationarity, Dynamics, and Cointegration within Macroeconomics & Econometrics — command macro time-series econometrics through the stationarity framework (definitions, trend versus difference stationarity, unit-root persistence, ACF-PACF reading), testing toolkit (ADF-Perron-KPSS confirm pairs, break-aware tests, panel methods), the ARMA-ARIMA family (components and conditions, Box-Jenkins.... Use this skill whenever the user asks to create, teach, or deepen training on series, econometrics, stationarity, dynamics, cointegration, macroeconomics and econometrics, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Fundamental Analyst course 01, section 11)
  version: 1.0.0
  category: professional-education
---

# Time-Series Econometrics: Stationarity, Dynamics, and Cointegration — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **time-Series Econometrics: Stationarity, Dynamics, and Cointegration** within The macroeconomic and econometric foundation of the futures fundamental analyst discipline — how interest rates, inflation, GDP, and central bank policy drive global capital flows, and how predictive statistical models quantify the correlations between these variables over time.

Subject scope: Covers the specialized econometrics of macro time series where trends, persistence, and long-run relationships demand purpose-built methods: the stationarity framework (the strict-versus-covariance-stationarity definitions where mean, variance, and autocovariances must be time-invariant for standard inference; the trend-stationary versus difference-stationary distinction whose confusion generates spurious results; the unit-root concept where shocks persist permanently, the defining feature of most macro series; the autocorrelation-function and partial-autocorrelation reading for dependence structure); the unit-root testing toolkit (the Dickey-Fuller and augmented-DF tests with their lag-selection and deterministic-term decisions; the Phillips-Perron alternative handling serial correlation non-parametrically; the KPSS test reversing the null to stationarity with the confirm-pair practice of running both directions; the structural-break-aware tests where ignoring breaks biases toward finding unit roots; the panel unit-root methods for cross-country macro analysis); the ARMA and ARIMA family (the autoregressive and moving-average components with their stationarity and invertibility conditions; the Box-Jenkins identification-estimation-diagnosis cycle; the ARIMA differencing integration for unit-root series; the seasonal-ARIMA extension for monthly macro data; the model-comparison discipline where parsimony beats fit through information criteria); the VAR revolution (the vector-autoregression structure treating every variable as endogenous, answering the simultaneous-equations critique through atheoretical reduced form; the VAR estimation and lag-order selection; the impulse-response analysis tracing shock propagation with the identification problem requiring ordering assumptions, sign restrictions, or narrative approaches; the forecast-error-variance decomposition quantifying shock contributions; the structural-VAR traditions identifying policy shocks central to macro-finance research); the cointegration system (the cointegration concept where non-stationary series share stochastic trends leaving stationary long-run combinations, the formal basis for equilibrium-relationship modeling such as parity conditions and pass-through systems; the Engle-Granger two-step approach with its single-cointegrating-vector limitation; the Johansen multivariate methodology estimating cointegrating rank and vectors; the error-correction-model representation where short-run dynamics adjust toward long-run equilibrium with the speed-of-adjustment coefficient as a directly interpretable trading parameter; the spurious-versus-cointegrated regression distinction resolved through residual stationarity testing); the volatility and regime dynamics (the ARCH and GARCH conditional-variance models capturing volatility clustering relevant to macro-surprise impact analysis; the Markov-switching models formalizing the regime framework of the cycle section with estimated transition probabilities; the local-projection method estimating impulse responses robustly under misspecification); the long-memory and fractional concepts (the fractional-integration continuum between stationarity and unit roots; the persistence-measurement refinements for series like inflation whose memory exceeds ARMA capacity); the practical modeling workflow (the data-preparation sequence covering logs, differencing, seasonality, and outlier treatment; the unit-root-first protocol testing every series before regression; the cointegration-search discipline when theory predicts long-run relationships; the forecast-oriented model selection where in-sample diagnostics yield to out-of-sample comparison per the next section; the real-time-vintage construction for genuine backtesting of macro models) together with the section anti-patterns — the failure library: the levels-regressor who regresses non-stationary series in levels and reports significant nonsense, remedied by the unit-root-first protocol; the differencing-overkiller who differences stationary series destroying long-run information and inducing MA-unit artifacts, remedied by the confirm-pair testing; the VAR-interpreter who reads impulse responses from unidentified reduced forms as causal effects, remedied by the identification-transparency discipline; the cointegration-fisherman who searches variable combinations until some vector cointegrates, remedied by the theory-prior requirement; the ECM-ignorer who models long-run equilibrium without the adjustment dynamics that make it tradable, remedied by the error-correction representation; the GARCH-forcaster who extrapolates volatility models beyond their conditional-variance purpose into mean prediction, remedied by the purpose-boundary literacy; and the switching-model overfitter who estimates regime models with more states than data supports, remedied by the parsimony and out-of-sample discipline with detection methods as the diagnostic.

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
# Time-Series Econometrics: Stationarity, Dynamics, and Cointegration [— audience/context subtitle]

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

The goal is not more content about macroeconomics and econometrics. The goal is that a practitioner could take this material and perform: Command macro time-series econometrics through the stationarity framework (definitions, trend versus difference stationarity, unit-root persistence, ACF-PACF reading), testing toolkit (ADF-Perron-KPSS confirm pairs, break-aware tests, panel methods), the ARMA-ARIMA family (components and conditions, Box-Jenkins cycle, seasonal extension, parsimony comparison), VAR systems (structure and estimation, impulse responses with identification honesty, variance decomposition, structural traditions), cointegration (concept and equilibrium modeling, Engle-Granger and Johansen methods, error-correction representation with adjustment speeds, spurious-resolution testing), volatility and regimes (GARCH clustering, Markov switching, local projections), fractional persistence, and the practical workflow (preparation sequence, unit-root-first protocol, theory-prior cointegration search, forecast-oriented selection, real-time vintages), avoiding levels regression, differencing overkill, unidentified VAR reading, cointegration fishing, ECM ignorance, GARCH misuse, and switching overfitting failures, Command macro time-series econometrics through the stationarity framework (definitions, trend versus difference stationarity, unit-root persistence, ACF-PACF reading), testing toolkit (ADF-Perron-KPSS confirm pairs, break-aware tests, panel methods), the ARMA-ARIMA family (components and conditions, Box-Jenkins cycle, seasonal extension, parsimony comparison), VAR systems (structure and estimation, impulse responses with identification honesty, variance decomposition, structural traditions), cointegration (concept and equilibrium modeling, Engle-Granger and Johansen methods, error-correction representation with adjustment speeds, spurious-resolution testing), volatility and regimes (GARCH clustering, Markov switching, local projections), fractional persistence, and the practical workflow (preparation sequence, unit-root-first protocol, theory-prior cointegration search, forecast-oriented selection, real-time vintages), avoiding levels regression, differencing overkill, unidentified VAR reading, cointegration fishing, ECM ignorance, GARCH misuse, and switching overfitting failures — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
