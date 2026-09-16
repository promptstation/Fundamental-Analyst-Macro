# Domain Content Map — The Option Greeks: Risk Sensitivity Measurement and Management

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Manage option risk through first-order Greeks (delta with synthetic equivalence, gamma convexity engine, vega volatility dimension, theta decay cost with theta-gamma identity), higher-order sensitivities (vanna, charm, volga, rho-carry, cross-greek stress dominance), aggregation discipline (position computation, netting traps, scenario complement, expiry profiles), delta hedging (rebalancing tradeoffs, long-short gamma P-and-L identity, discrete error analysis, dealer-flow transmission), volatility trading (straddle conversions, implied-realized spreads, calendar expression, dispersion structures), commodity specifics (exercise conventions, event concentration, liquidity adjustment, seasonal overlay), and intuition-computation balance (validation paths, mental approximations, professional fluency), avoiding delta-only management, theta collection traps, frictionless simulation, vega-less vol views, pin-risk sleep, and jargon laundering failures.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the Greeks system that decomposes option risk into measurable components, the daily working language of option positioning and hedging: the first-order sensitivities (the delta measuring price sensitivity whose option-position interpretation ranges zero to one for calls, defining the synthetic-futures equivalence where delta times notional replicates directional exposure; the gamma measuring delta's rate of change, the convexity engine where long-gamma positions profit from realized movement and short-gamma positions bleed from it, the single most important concept for understanding market-maker flow effects; the vega measuring volatility sensitivity quoted per vol point, the dimension where option positions actually express volatility views; the theta measuring time decay whose negative sign for long options constitutes the carrying cost of convexity, with the theta-gamma tradeoff identity linking the two through the pricing equation); the higher-order and rate sensitivities (the vanna measuring delta's response to volatility changes, driving hedging flows when vol moves and underlying does not; the charm or delta-decay measuring delta's time evolution, material near expirations where roll and pin risk concentrate; the volga or vomma measuring vega's volatility sensitivity shaping convexity in vol space; the rho and carry-greeks where rate and cost-of-carry sensitivities matter for long-dated commodity and rate options; the cross-greeks awareness where second-order interactions dominate in large moves, the reason single-Greek risk views fail in stress); the Greek-aggregation discipline (the position-level computation where each holding's Greeks sum by component after notional normalization; the portfolio-netting insight where offsetting deltas can mask concentrated gamma or vega exposure, the netting-trap analysts audit; the scenario-stress complement where Greek linearity assumptions break beyond small moves, requiring the full-revaluation stress tests of the risk section; the expiry-profile tracking where theta and gamma concentrate by date, shaping the calendar of hedging workload and pin risk); the delta-hedging practice (the hedge-ratio mechanics where offsetting futures positions neutralize delta with the rebalancing-frequency decision trading transaction costs against tracking error; the long-versus-short-gamma hedging experience where long-gamma rebalancing buys low sells high monetizing volatility above implied levels while short-gamma does the reverse, the realized-versus-implied P-and-L identity; the discrete-hedging error analysis quantifying gap, timing, and cost slippage; the market-maker-flow transmission where aggregate dealer gamma positioning predicts hedging flows that amplify or damp underlying moves, the gamma-squeeze mechanics of documented episodes); the volatility-trading framework (the straddle-as-vol-position reading where at-the-money straddle prices approximate expected movement, the front-office volatility conversion; the implied-realized spread trade where positions earn the difference between implied vega pricing and subsequent realized volatility; the calendar-volatility expression where term-structure views trade through calendar spreads per the volatility section; the dispersion-and-relative-value structures across strikes and expirations using the surface coordinates); the commodity-Greek specifics (the futures-option delta conventions where exercise-into-futures mechanics alter post-exercise risk profiles; the event-gamma concentration where report days and weather catalysts cluster theta and gamma behavior; the liquidity-adjusted Greeks where thin-strike vega positions carry execution risk beyond model sensitivity; the seasonality-overlay where agricultural option management must respect the weather-market calendar of the companion course); and the Greek-intuition versus computation balance (the closed-form and lattice computation paths whose agreement validates implementation; the mental-arithmetic approximations including the at-the-money straddle rule and delta-as-probability heuristic with their error bounds known; the risk-conversation fluency where analysts describe positions in Greek terms to traders and risk officers, the professional-interface skill) together with the section anti-patterns — the failure library: the delta-only manager whose neutral-delta book carries lethal short-gamma or vega concentrations revealed by the first large move, remedied by the aggregation and netting-trap audit; the theta-collector who sells time decay without gamma accounting until a gap move costs multiples of collected premium, remedied by the theta-gamma identity literacy; the continuous-hedging simulator whose backtests ignore discrete rebalancing costs and gaps, remedied by the hedging-error analysis; the vol-view-without-vega trader who forecasts volatility but positions through direction, leaking the view through delta noise, remedied by the volatility-trading framework; the pin-risk sleeper holding short at-the-money positions into expiration Friday without assignment and gamma plans, remedied by the expiry-profile tracking; and the Greek-jargon launderer who cites sensitivities without understanding the replication logic generating them, remedied by the intuition-computation balance with detection methods as the diagnostic.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the Greeks system that decomposes option risk into measurable components, the daily working language of option positioning and hedging
- the first-order sensitivities (the delta measuring price sensitivity whose option-position interpretation ranges zero to one for calls, defining the synthetic-futures equivalence where delta times notional replicates directional exposure
- the gamma measuring delta's rate of change, the convexity engine where long-gamma positions profit from realized movement and short-gamma positions bleed from it, the single most important concept for understanding market-maker flow effects
- the vega measuring volatility sensitivity quoted per vol point, the dimension where option positions actually express volatility views
- the theta measuring time decay whose negative sign for long options constitutes the carrying cost of convexity, with the theta-gamma tradeoff identity linking the two through the pricing equation)
- the higher-order and rate sensitivities (the vanna measuring delta's response to volatility changes, driving hedging flows when vol moves and underlying does not
- the charm or delta-decay measuring delta's time evolution, material near expirations where roll and pin risk concentrate
- the volga or vomma measuring vega's volatility sensitivity shaping convexity in vol space
- the rho and carry-greeks where rate and cost-of-carry sensitivities matter for long-dated commodity and rate options
- the cross-greeks awareness where second-order interactions dominate in large moves, the reason single-Greek risk views fail in stress)
- the Greek-aggregation discipline (the position-level computation where each holding's Greeks sum by component after notional normalization
- the portfolio-netting insight where offsetting deltas can mask concentrated gamma or vega exposure, the netting-trap analysts audit
- the scenario-stress complement where Greek linearity assumptions break beyond small moves, requiring the full-revaluation stress tests of the risk section
- the expiry-profile tracking where theta and gamma concentrate by date, shaping the calendar of hedging workload and pin risk)
- the delta-hedging practice (the hedge-ratio mechanics where offsetting futures positions neutralize delta with the rebalancing-frequency decision trading transaction costs against tracking error
- the long-versus-short-gamma hedging experience where long-gamma rebalancing buys low sells high monetizing volatility above implied levels while short-gamma does the reverse, the realized-versus-implied P-and-L identity
- the discrete-hedging error analysis quantifying gap, timing, and cost slippage
- the market-maker-flow transmission where aggregate dealer gamma positioning predicts hedging flows that amplify or damp underlying moves, the gamma-squeeze mechanics of documented episodes)
- the volatility-trading framework (the straddle-as-vol-position reading where at-the-money straddle prices approximate expected movement, the front-office volatility conversion
- the implied-realized spread trade where positions earn the difference between implied vega pricing and subsequent realized volatility
- the calendar-volatility expression where term-structure views trade through calendar spreads per the volatility section
- the dispersion-and-relative-value structures across strikes and expirations using the surface coordinates)
- the commodity-Greek specifics (the futures-option delta conventions where exercise-into-futures mechanics alter post-exercise risk profiles
- the event-gamma concentration where report days and weather catalysts cluster theta and gamma behavior
- the liquidity-adjusted Greeks where thin-strike vega positions carry execution risk beyond model sensitivity
- the seasonality-overlay where agricultural option management must respect the weather-market calendar of the companion course)
- and the Greek-intuition versus computation balance (the closed-form and lattice computation paths whose agreement validates implementation
- the mental-arithmetic approximations including the at-the-money straddle rule and delta-as-probability heuristic with their error bounds known
- the risk-conversation fluency where analysts describe positions in Greek terms to traders and risk officers, the professional-interface skill) together with the section anti-patterns — the failure library: the delta-only manager whose neutral-delta book carries lethal short-gamma or vega concentrations revealed by the first large move, remedied by the aggregation and netting-trap audit
- the theta-collector who sells time decay without gamma accounting until a gap move costs multiples of collected premium, remedied by the theta-gamma identity literacy
- the continuous-hedging simulator whose backtests ignore discrete rebalancing costs and gaps, remedied by the hedging-error analysis
- the vol-view-without-vega trader who forecasts volatility but positions through direction, leaking the view through delta noise, remedied by the volatility-trading framework
- the pin-risk sleeper holding short at-the-money positions into expiration Friday without assignment and gamma plans, remedied by the expiry-profile tracking
- and the Greek-jargon launderer who cites sensitivities without understanding the replication logic generating them, remedied by the intuition-computation balance with detection methods as the diagnostic

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in quantitative finance and derivatives pricing practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in quantitative finance and derivatives pricing through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
