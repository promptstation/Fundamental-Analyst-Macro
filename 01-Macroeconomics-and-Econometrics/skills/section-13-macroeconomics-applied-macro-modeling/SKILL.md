---
name: section-13-macroeconomics-applied-macro-modeling
description: Develop comprehensive, professional-level learning modules and training materials on applied Macro Modeling — Building the Analyst's Own System within Macroeconomics & Econometrics — build a personal macro system through architecture (requirements definition, layered design, minimum-viable philosophy, tool-stack gradient), data layer construction (source registry, automated ingestion, vintage archives, quality monitoring, calendar integration), indicator layer design (dashboard taxonomy,.... Use this skill whenever the user asks to create, teach, or deepen training on applied, macro, modeling, building, analyst, system, macroeconomics and econometrics, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Fundamental Analyst course 01, section 13)
  version: 1.0.0
  category: professional-education
---

# Applied Macro Modeling: Building the Analyst's Own System — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **applied Macro Modeling: Building the Analyst's Own System** within The macroeconomic and econometric foundation of the futures fundamental analyst discipline — how interest rates, inflation, GDP, and central bank policy drive global capital flows, and how predictive statistical models quantify the correlations between these variables over time.

Subject scope: Covers the construction of a personal macro-monitoring and modeling system integrating every prior section into working infrastructure: the system architecture (the requirements definition where the analyst specifies what decisions the system must support, preventing dashboard-empire building disconnected from positions; the layered-design pattern with a data layer, an indicator layer, a model layer, and a decision layer whose separation enables maintenance; the minimum-viable-system philosophy where a working five-indicator regime board beats an unfinished fifty-variable model; the tool-stack selection across spreadsheets, Python, and databases with the automation gradient from manual to scheduled pipelines per the programming companion); the data layer construction (the source-registry documenting every series with its publisher, vintage policy, revision schedule, and known quirks; the automated-ingestion patterns pulling from public APIs including FRED and international equivalents with rate-limit and failure handling; the vintage-archive discipline storing first prints alongside revisions enabling the real-time backtesting of the forecasting section; the data-quality monitoring with break detection, outlier flagging, and stale-series alerts; the calendar-integration where release schedules drive refresh and analysis timing); the indicator layer design (the dashboard-taxonomy organizing indicators by cycle phase, policy channel, and asset class with the cross-reference to the cycle and transmission sections; the composite-index construction including financial-conditions indices combining spreads, rates, equity levels, and currency movements with the weighting and standardization decisions documented; the diffusion-and-breadth trackers counting improving versus deteriorating series per the cycle-reading discipline; the threshold-and-signal systems where indicator crossings trigger review rather than automatic action; the red-flag registry maintaining the analyst's current list of anomalies awaiting explanation); the model layer assembly (the nowcast-model implementation combining the mixed-frequency and factor approaches of the forecasting section into a running GDP tracker; the policy-path model translating central-bank reaction functions into expected rate paths for comparison against futures-implied paths; the relationship-monitor set tracking estimated pass-throughs, spreads, and elasticities with rolling-window stability charts exposing regime drift; the scenario-engine structure where alternative policy and shock assumptions propagate through the system's relationships); the decision layer practices (the view-documentation standard where every macro position records its thesis, supporting indicators, invalidation conditions, and horizon per the falsification discipline of the foundations; the confidence-scoring system quantifying view strength separately from expected payoff; the review-ritual cadence including weekly indicator sweeps, monthly model updates, and quarterly deep reviews with written outputs; the decision-journal habit logging predictions and outcomes building the calibration record from the forecasting section); the maintenance and evolution (the system-audit practice where unused components get retired per the zombie-detection disciplines common across this curriculum family; the dependency-awareness where upstream data changes propagate through documented relationships; the version-control adoption for models and code; the capability-roadmap where system sophistication grows with demonstrated need rather than technical temptation); and the workflow integration (the morning-process design where release days follow scripted review sequences; the research-time protection separating system maintenance from analysis; the output-generation pipeline feeding the written and verbal communication formats that carry views to decision makers) together with the section anti-patterns — the failure library: the dashboard-empire builder whose indicator collection grows without decision linkage until maintenance consumes the analysis time, remedied by the requirements-first design and audit retirement; the manual-vintage victim who cannot backtest because first prints were overwritten by revisions, remedied by the archive discipline; the composite-opacity trader who acts on financial-conditions indices without knowing the component movements driving them, remedied by the decomposition habits; the threshold-robot who treats indicator crossings as mechanical signals ignoring context and breadth, remedied by the review-trigger design; the undocumented-view keeper whose past calls cannot be audited against outcomes, remedied by the documentation standard and journal; and the rebuild-compulsive whose system never stabilizes long enough to accumulate evaluation history, remedied by the minimum-viable-system philosophy with detection methods as the diagnostic.

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
# Applied Macro Modeling: Building the Analyst's Own System [— audience/context subtitle]

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
- each absorbed capability (3 in this section) is covered by teaching content AND at least one exercise with evaluation criteria
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

The goal is not more content about macroeconomics and econometrics. The goal is that a practitioner could take this material and perform: Build a personal macro system through architecture (requirements definition, layered design, minimum-viable philosophy, tool-stack gradient), data layer construction (source registry, automated ingestion, vintage archives, quality monitoring, calendar integration), indicator layer design (dashboard taxonomy, financial-conditions composites, diffusion trackers, threshold signals, red-flag registry), review rituals, decision journals), maintenance and evolution (audits, dependency awareness, version control, capability roadmaps), and workflow integration (morning processes, research protection, output pipelines), avoiding dashboard empires, vintage loss, composite opacity, threshold robotics, undocumented views, and compulsive rebuilding failures — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
