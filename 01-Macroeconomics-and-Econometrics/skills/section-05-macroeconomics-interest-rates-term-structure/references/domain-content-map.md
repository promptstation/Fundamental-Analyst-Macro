# Domain Content Map — Interest Rates and the Term Structure: The Yield-Curve System

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Master the yield-curve system through time-value foundations (discounting conventions, Fisher real-nominal, risk-free proxies), term-structure theory (expectations hypothesis and its rejection, liquidity preference, segmentation and habitat, modern term-premium decomposition), curve-reading craft (level-slope-curvature components, benchmark spreads, inversion record with debates, flattener-steepener driver taxonomy), rate-market structure (government and swap curves, repo funding signals, futures-path mapping with convexity), discount-rate architecture (credit layering, covered-interest-parity linkage), policy-curve interaction (short-end anchoring, term-premium independence, curve control, fiscal supply), empirical tools (factor extraction, spread regressions, event studies), and trading literacy (curve positions, carry and roll, basis concepts), avoiding shape-only reading, hypothesis literalism, single-spread watching, static modeling, and cash-futures confusion failures.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the interest-rate theory and curve mechanics that form the analytical spine of every financial-futures market: the time-value foundations (the discounting arithmetic where present values convert future cash flows through compounding conventions including money-market versus bond-market day counts; the real-versus-nominal rate distinction with the Fisher equation and its ex-ante versus ex-post measurement problem; the risk-free concept and its practical proxies across Treasury bills, SOFR, and OIS rates); the term-structure theories (the expectations hypothesis where long rates average expected future short rates with the empirical rejection through the yield-risk-premium evidence; the liquidity-preference tradition where term premia compensate duration risk; the market-segmentation and preferred-habitat views where investor mandates shape specific maturities; the modern term-premium decomposition with the affine-model estimates from the ACM and Kim-Wright traditions whose movements inform curve positioning); the curve-reading craft (the shape vocabulary covering level, slope, spread, and curvature as the three principal components explaining nearly all curve movement; the benchmark spreads including two-ten, three-month-ten-year, and five-five-thirty conventions; the inversion-recession record where curve inversions preceded postwar recessions with the false-signal and lag debates; the bear-flattener versus bull-steepener taxonomy where the driver identification, not the shape change alone, carries the forecast content); the rate-market structure (the government-curve construction from bill and bond markets with the on-the-run versus off-the-run liquidity distinction; the swap curve and its spread to Treasuries as a bank-credit and collateral gauge; the repo and funding markets where general-collateral and special rates reveal scarcity and stress; the futures curve mapping where Treasury and SOFR futures price the expected path with convexity adjustments converting futures to forwards); the discount-rate architecture (the risk-free curve as the foundation of every valuation in the companion asset classes; the credit-spread system layering default, liquidity, and risk-premium components over the base curve; the cross-border rate linkage where covered-interest-parity connects domestic curves to FX forwards per the international section); the policy-curve interaction (the anchoring of the short end by the policy-rate path with the futures-implied expectations from the central-bank section; the term-premium independence where long rates can rise during easing through supply, inflation-risk, or fiscal concerns; the curve-control regimes where the central bank pins specific maturities, distorting the information content; the fiscal-supply channel where issuance composition shifts curve shape independent of policy); the empirical-analysis toolkit (the yield-factor extraction through principal components on curve history; the spread-forecasting regressions testing whether slope predicts future growth and rate changes with the in-sample versus out-of-sample disputes; the event-study method isolating curve reactions to data releases and policy surprises); and the trading-interface literacy (the curve-position vocabulary covering flatteners, steepeners, butterflies, and their risk profiles; the carry-and-roll mechanics where position returns decompose into yield carry, roll-down, and price change; the basis and cheapest-to-deliver concepts connecting cash bonds to futures per the derivatives course) together with the section anti-patterns — the failure library: the shape-only reader who trades inversions without identifying whether bear or bull forces drive them, remedied by the driver taxonomy; the expectations-hypothesis literalist who assumes long rates must fall when short rates are expected lower, ignoring term premia, remedied by the premium decomposition; the single-spread watcher who monitors one benchmark spread while the principal components move the portfolio, remedied by the level-slope-curvature framework; the static-curve modeler who applies historical spread-regression coefficients across policy regimes, remedied by the regime-conditional estimation; and the cash-futures confuser who quotes bond yields and futures prices interchangeably without convexity adjustment, remedied by the conversion mechanics with detection methods as the diagnostic.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the interest-rate theory and curve mechanics that form the analytical spine of every financial-futures market
- the time-value foundations (the discounting arithmetic where present values convert future cash flows through compounding conventions including money-market versus bond-market day counts
- the real-versus-nominal rate distinction with the Fisher equation and its ex-ante versus ex-post measurement problem
- the risk-free concept and its practical proxies across Treasury bills, SOFR, and OIS rates)
- the term-structure theories (the expectations hypothesis where long rates average expected future short rates with the empirical rejection through the yield-risk-premium evidence
- the liquidity-preference tradition where term premia compensate duration risk
- the market-segmentation and preferred-habitat views where investor mandates shape specific maturities
- the modern term-premium decomposition with the affine-model estimates from the ACM and Kim-Wright traditions whose movements inform curve positioning)
- the curve-reading craft (the shape vocabulary covering level, slope, spread, and curvature as the three principal components explaining nearly all curve movement
- the benchmark spreads including two-ten, three-month-ten-year, and five-five-thirty conventions
- the inversion-recession record where curve inversions preceded postwar recessions with the false-signal and lag debates
- the bear-flattener versus bull-steepener taxonomy where the driver identification, not the shape change alone, carries the forecast content)
- the rate-market structure (the government-curve construction from bill and bond markets with the on-the-run versus off-the-run liquidity distinction
- the swap curve and its spread to Treasuries as a bank-credit and collateral gauge
- the repo and funding markets where general-collateral and special rates reveal scarcity and stress
- the futures curve mapping where Treasury and SOFR futures price the expected path with convexity adjustments converting futures to forwards)
- the discount-rate architecture (the risk-free curve as the foundation of every valuation in the companion asset classes
- the credit-spread system layering default, liquidity, and risk-premium components over the base curve
- the cross-border rate linkage where covered-interest-parity connects domestic curves to FX forwards per the international section)
- the policy-curve interaction (the anchoring of the short end by the policy-rate path with the futures-implied expectations from the central-bank section
- the term-premium independence where long rates can rise during easing through supply, inflation-risk, or fiscal concerns
- the curve-control regimes where the central bank pins specific maturities, distorting the information content
- the fiscal-supply channel where issuance composition shifts curve shape independent of policy)
- the empirical-analysis toolkit (the yield-factor extraction through principal components on curve history
- the spread-forecasting regressions testing whether slope predicts future growth and rate changes with the in-sample versus out-of-sample disputes
- the event-study method isolating curve reactions to data releases and policy surprises)
- and the trading-interface literacy (the curve-position vocabulary covering flatteners, steepeners, butterflies, and their risk profiles
- the carry-and-roll mechanics where position returns decompose into yield carry, roll-down, and price change
- the basis and cheapest-to-deliver concepts connecting cash bonds to futures per the derivatives course) together with the section anti-patterns — the failure library: the shape-only reader who trades inversions without identifying whether bear or bull forces drive them, remedied by the driver taxonomy
- the expectations-hypothesis literalist who assumes long rates must fall when short rates are expected lower, ignoring term premia, remedied by the premium decomposition
- the single-spread watcher who monitors one benchmark spread while the principal components move the portfolio, remedied by the level-slope-curvature framework
- the static-curve modeler who applies historical spread-regression coefficients across policy regimes, remedied by the regime-conditional estimation
- and the cash-futures confuser who quotes bond yields and futures prices interchangeably without convexity adjustment, remedied by the conversion mechanics with detection methods as the diagnostic

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in macroeconomics and econometrics practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in macroeconomics and econometrics through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
