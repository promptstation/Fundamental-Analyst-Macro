# Domain Content Map — Volatility: Implied Surfaces, Term Structure, and the Volatility Complex

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Master the volatility complex through taxonomy (realized estimators, implied consensus, forecast specification, vol of vol), the term structure (slope and inversion signals, variance decomposition, calendar mechanics, forward-implied extraction, commodity seasonality), surfaces and skew (smile topology, equity-FX-commodity conventions, risk-reversal and butterfly coordinates, surface dynamics as regime indicator), the risk-premium literature (implied-realized gap evidence, interpretation debates, harvesting profiles, conditionality), the VIX complex (construction methodology, futures carry structure, product distortions, cross-asset family), modeling layers (GARCH baselines, stochastic and local volatility, SABR parametrization, selection pragmatism), and trading applications (event isolation, relative value, hedging overlays, information extraction), avoiding single-number quoting, carry victimhood, skew constancy, premium automation, convention confusion, and event holding failures.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the volatility system whose measurement, structure, and risk premia form the deepest information layer of derivatives markets: the volatility taxonomy (the realized-volatility measurement across close-to-close, Parkinson range-based, and high-frequency estimators with the window and weighting choices that make published figures differ; the implied-volatility definition as the BSM-consistent parameter extracted from market prices, a quoted consensus rather than a statistic; the forecast-volatility discipline where analyst predictions must specify estimator, horizon, and conditioning information to be comparable; the volatility-of-volatility concept where the surface itself moves, creating second-order risk for vega positions); the term-structure system (the implied-volatility term structure whose upward slope typically reflects uncertainty accumulation and whose inversions signal expected event resolution; the variance-term-structure decomposition separating expected path variance from event premia; the calendar-spread mechanics where term-structure views trade through straddle spreads per the Greeks section; the forward-implied-volatility extraction computing the volatility priced between two expirations, the term-structure analog of forward rates, essential for event isolation; the commodity term-structure seasonality where agricultural and energy vol curves embed weather-window and demand-cycle expectations per the companion course's calendars); the surface and skew system (the smile-and-skew topology where implied volatility varies systematically with moneyness, the empirical refutation of constant-volatility pricing; the equity-skew convention where downside puts price richer reflecting crash fear and demand asymmetry, versus the FX-smile convention pricing both tails; the commodity-skew behavior where weather and supply events create call-side richness in backwardated markets, the opposite of equity convention in some regimes; the risk-reversal and butterfly quotations summarizing skew slope and curvature as tradeable coordinates; the surface-dynamics observation where skew steepens in stress and flattens in calm, itself a regime indicator); the volatility-risk-premium literature (the implied-realized gap evidence where implied volatility systematically exceeds subsequent realized levels, the documented premium selling insurance earns; the premium-interpretation debates spanning risk compensation, jump fear, and variance-risk demand; the premium-harvesting strategies and their crash-tail exposure where steady income meets rare catastrophic loss, the short-volatility return profile; the regime-conditionality where premium size varies with market state, motivating conditional rather than unconditional harvesting); the VIX complex (the VIX construction methodology computing thirty-day expected variance from S&P option portfolios whose formula mechanics analysts must know to interpret levels; the VIX-futures curve and its contango-carry structure where long volatility positions bleed roll decay, the most misunderstood instrument among fundamental analysts; the VIX-term-premium dynamics and backwardation spikes during stress; the volatility-ETN and structured-product distortions whose rebalancing flows feedback into VIX futures, the 2018 collapse episode as case study; the cross-asset volatility family spanning OVX energy, GVZ gold, and commodity-specific indices); the volatility-modeling layer (the ARCH-GARCH conditional-variance tradition capturing clustering whose forecasts serve as realized-volatility baselines; the stochastic-volatility model family where volatility itself follows random processes, matching surface dynamics at calibration cost; the local-volatility construction reproducing the surface exactly through Dupire's formula with its known dynamics distortions; the SABR and parametrization families interpolating surfaces smoothly for trading use; the model-selection pragmatism where practitioners choose by instrument, horizon, and calibration stability rather than theoretical purity); the volatility-trading applications (the event-volatility trading where report days, elections, and weather windows get isolated through forward-implied analysis and expired post-event per the fundamental event calendar; the relative-value volatility trading across strikes, expirations, and related markets exploiting surface incoherence; the volatility-hedging use where fundamental positions carry vega overlays managing gap and catalyst risk; the volatility-information extraction where surface changes signal informed flow or regime shifts ahead of underlying moves) together with the section anti-patterns — the failure library: the single-number vol quoter who cites implied volatility without strike or expiry coordinates, comparing incommensurable figures, remedied by the surface-literacy discipline; the long-vol-carry victim who buys VIX futures as crash insurance without the contango bleed arithmetic, remedied by the term-structure carry analysis; the skew-constant modeler who applies historical smile shapes through regime changes in crash fear, remedied by the surface-dynamics monitoring; the premium-harvest automaton who shortens volatility unconditionally until the tail event collects years of premium at once, remedied by the regime-conditionality and sizing discipline; the realized-implied confuser whose arguments mix estimator conventions invisibly, remedied by the taxonomy specification habit; and the event-vol holder who pays up for report-day variance and holds the decay afterward, remedied by the event-isolation and expiry-timing craft with detection methods as the diagnostic.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the volatility system whose measurement, structure, and risk premia form the deepest information layer of derivatives markets
- the volatility taxonomy (the realized-volatility measurement across close-to-close, Parkinson range-based, and high-frequency estimators with the window and weighting choices that make published figures differ
- the implied-volatility definition as the BSM-consistent parameter extracted from market prices, a quoted consensus rather than a statistic
- the forecast-volatility discipline where analyst predictions must specify estimator, horizon, and conditioning information to be comparable
- the volatility-of-volatility concept where the surface itself moves, creating second-order risk for vega positions)
- the term-structure system (the implied-volatility term structure whose upward slope typically reflects uncertainty accumulation and whose inversions signal expected event resolution
- the variance-term-structure decomposition separating expected path variance from event premia
- the calendar-spread mechanics where term-structure views trade through straddle spreads per the Greeks section
- the forward-implied-volatility extraction computing the volatility priced between two expirations, the term-structure analog of forward rates, essential for event isolation
- the commodity term-structure seasonality where agricultural and energy vol curves embed weather-window and demand-cycle expectations per the companion course's calendars)
- the surface and skew system (the smile-and-skew topology where implied volatility varies systematically with moneyness, the empirical refutation of constant-volatility pricing
- the equity-skew convention where downside puts price richer reflecting crash fear and demand asymmetry, versus the FX-smile convention pricing both tails
- the commodity-skew behavior where weather and supply events create call-side richness in backwardated markets, the opposite of equity convention in some regimes
- the risk-reversal and butterfly quotations summarizing skew slope and curvature as tradeable coordinates
- the surface-dynamics observation where skew steepens in stress and flattens in calm, itself a regime indicator)
- the volatility-risk-premium literature (the implied-realized gap evidence where implied volatility systematically exceeds subsequent realized levels, the documented premium selling insurance earns
- the premium-interpretation debates spanning risk compensation, jump fear, and variance-risk demand
- the premium-harvesting strategies and their crash-tail exposure where steady income meets rare catastrophic loss, the short-volatility return profile
- the regime-conditionality where premium size varies with market state, motivating conditional rather than unconditional harvesting)
- the VIX complex (the VIX construction methodology computing thirty-day expected variance from S&P option portfolios whose formula mechanics analysts must know to interpret levels
- the VIX-futures curve and its contango-carry structure where long volatility positions bleed roll decay, the most misunderstood instrument among fundamental analysts
- the VIX-term-premium dynamics and backwardation spikes during stress
- the volatility-ETN and structured-product distortions whose rebalancing flows feedback into VIX futures, the 2018 collapse episode as case study
- the cross-asset volatility family spanning OVX energy, GVZ gold, and commodity-specific indices)
- the volatility-modeling layer (the ARCH-GARCH conditional-variance tradition capturing clustering whose forecasts serve as realized-volatility baselines
- the stochastic-volatility model family where volatility itself follows random processes, matching surface dynamics at calibration cost
- the local-volatility construction reproducing the surface exactly through Dupire's formula with its known dynamics distortions
- the SABR and parametrization families interpolating surfaces smoothly for trading use
- the model-selection pragmatism where practitioners choose by instrument, horizon, and calibration stability rather than theoretical purity)
- the volatility-trading applications (the event-volatility trading where report days, elections, and weather windows get isolated through forward-implied analysis and expired post-event per the fundamental event calendar
- the relative-value volatility trading across strikes, expirations, and related markets exploiting surface incoherence
- the volatility-hedging use where fundamental positions carry vega overlays managing gap and catalyst risk
- the volatility-information extraction where surface changes signal informed flow or regime shifts ahead of underlying moves) together with the section anti-patterns — the failure library: the single-number vol quoter who cites implied volatility without strike or expiry coordinates, comparing incommensurable figures, remedied by the surface-literacy discipline
- the long-vol-carry victim who buys VIX futures as crash insurance without the contango bleed arithmetic, remedied by the term-structure carry analysis
- the skew-constant modeler who applies historical smile shapes through regime changes in crash fear, remedied by the surface-dynamics monitoring
- the premium-harvest automaton who shortens volatility unconditionally until the tail event collects years of premium at once, remedied by the regime-conditionality and sizing discipline
- the realized-implied confuser whose arguments mix estimator conventions invisibly, remedied by the taxonomy specification habit
- and the event-vol holder who pays up for report-day variance and holds the decay afterward, remedied by the event-isolation and expiry-timing craft with detection methods as the diagnostic

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in quantitative finance and derivatives pricing practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in quantitative finance and derivatives pricing through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
