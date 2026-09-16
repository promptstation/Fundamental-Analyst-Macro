# Domain Content Map — Commodity Price Modeling and Forecasting: The Quantitative Layer

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Model commodity prices through problem structure (simultaneity, horizon decomposition, expectation-embedded prices), econometric classes (partial-equilibrium simulation, Nerlovian supply response, pass-through linkages, cointegration and error correction), statistical learning (ML yield prediction, satellite skill evidence, caution set, hybrid discipline), futures-curve extraction (curve-as-forecast evidence, spread signals, option distributions, cross-market consistency), scenario construction (probability-weighted trees, balance propagation, historical stress calibration.
2. Position translation), operations (seasonal calendars, forecast records, revision analysis, nowcast integration).
3. Model-risk management (break exposure, vintage discipline, ensembles, humility documentation), avoiding single-equation modeling, black-box yields, curve copying, unweighted scenarios, unlogged forecasts, and break-blind estimation failures.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the modeling toolkit that converts balance-sheet, cycle, and policy analysis into quantitative price assessment for commodity complexes: the commodity-forecast problem structure (the simultaneous-equation reality where price affects supply and demand while both affect price, motivating the system approaches rather than single-equation regression; the horizon decomposition where within-season forecasting is balance-and-weather driven, cross-season forecasting is acreage-and-cycle driven, and long-run forecasting is cost-curve and demand-trend driven, each requiring different models; the expectation-embedded-prices challenge where futures already contain the market's forecast, making analyst value-add a differential-view problem per the forecasting discipline of the macro companion); the econometric model classes (the partial-equilibrium simulation tradition where supply, demand, and trade equations clear markets under policy scenarios, the academic and institutional workhorse for agricultural outlook; the Nerlovian supply-response framework where acreage adjusts to expected prices with lagged dynamics; the price-linkage models estimating pass-through between crude and biofuel feedstocks, feed and livestock margins, and dollar and commodity prices; the cointegration applications where long-run parity relationships from the storage and trade theories get estimated and traded through error-correction systems per the time-series methods of the macro course); the statistical-learning entrants (the gradient-boosting and random-forest applications to yield prediction from weather and remote-sensing features where nonlinear interactions beat linear agronomy; the satellite-yield-model literature whose corn and wheat forecasts improve through the season with documented skill against official estimates; the machine-learning caution set covering small-sample overfitting, regime breaks, and feature leakage acute in agricultural data; the hybrid discipline where ML components feed structured balance sheets rather than replacing economic logic); the futures-curve information extraction (the curve-as-forecast evidence where deferred prices contain weak but real information about future spots, with the risk-premium contamination debated across eras; the spread-structure signals where calendar-spread levels encode the market's storage and scarcity assessment per the theory-of-storage linkages; the option-implied distributions whose volatility surfaces and skew reveal market-assessed tail probabilities for weather and policy events; the cross-market consistency checks where related curves including crush, feed, and energy products must reconcile with the analyst's view); the price-scenario construction (the scenario-tree architecture combining weather, policy, and demand branches with probability weights into price-path distributions; the balance-sheet-propagation engine where scenario assumptions flow through stocks-to-use into price mapping functions per the balance discipline; the stress-case calibration against historical episodes including 1970s grain booms, 2008 and 2012 spikes, and 2020 negative-oil episodes whose mechanisms inform tail design; the scenario-to-position translation with the asymmetric-payoff logic of the macro companion's event analysis); the forecasting-operations discipline (the seasonal-forecast-calendar where model runs align with report schedules, weather windows, and planting cycles; the forecast-record systems logging price views against outcomes for calibration review; the revision-behavior analysis studying how own and consensus estimates evolve through seasons revealing systematic biases; the nowcast-integration blending high-frequency export-pace, crush, and weather data into current-state assessment per the nowcasting methods of the macro course); the model-risk management (the structural-break exposure where support regimes, biotech adoption, shale revolution, and trade wars broke estimated relationships, motivating rolling re-estimation and regime conditioning; the data-vintage discipline running models on information available at decision time; the ensemble practice averaging model classes for robustness per the combination findings; the humility-documentation stating confidence intervals and failure modes alongside every price view) together with the section anti-patterns — the failure library: the single-equation price modeler who regresses price on stocks without simultaneity treatment and calls it forecasting, remedied by the system and scenario approaches; the ML-black-box yield caller whose satellite model has no agronomic logic and fails in anomaly years, remedied by the hybrid discipline; the curve-copyist who adopts futures prices as forecast without assessing the risk premium or forming a differential view, remedied by the information-extraction literacy; the scenario-without-weights builder whose trees list futures but assign no probabilities, remedied by the weighted-distribution requirement; the unlogged forecaster whose past views conveniently vanish from memory, remedied by the record systems; and the break-blind estimator whose decade-old pass-through coefficients survive three regime changes, remedied by the rolling re-estimation and regime conditioning with detection methods as the diagnostic.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the modeling toolkit that converts balance-sheet, cycle, and policy analysis into quantitative price assessment for commodity complexes
- the commodity-forecast problem structure (the simultaneous-equation reality where price affects supply and demand while both affect price, motivating the system approaches rather than single-equation regression
- the horizon decomposition where within-season forecasting is balance-and-weather driven, cross-season forecasting is acreage-and-cycle driven, and long-run forecasting is cost-curve and demand-trend driven, each requiring different models
- the expectation-embedded-prices challenge where futures already contain the market's forecast, making analyst value-add a differential-view problem per the forecasting discipline of the macro companion)
- the econometric model classes (the partial-equilibrium simulation tradition where supply, demand, and trade equations clear markets under policy scenarios, the academic and institutional workhorse for agricultural outlook
- the Nerlovian supply-response framework where acreage adjusts to expected prices with lagged dynamics
- the price-linkage models estimating pass-through between crude and biofuel feedstocks, feed and livestock margins, and dollar and commodity prices
- the cointegration applications where long-run parity relationships from the storage and trade theories get estimated and traded through error-correction systems per the time-series methods of the macro course)
- the statistical-learning entrants (the gradient-boosting and random-forest applications to yield prediction from weather and remote-sensing features where nonlinear interactions beat linear agronomy
- the satellite-yield-model literature whose corn and wheat forecasts improve through the season with documented skill against official estimates
- the machine-learning caution set covering small-sample overfitting, regime breaks, and feature leakage acute in agricultural data
- the hybrid discipline where ML components feed structured balance sheets rather than replacing economic logic)
- the futures-curve information extraction (the curve-as-forecast evidence where deferred prices contain weak but real information about future spots, with the risk-premium contamination debated across eras
- the spread-structure signals where calendar-spread levels encode the market's storage and scarcity assessment per the theory-of-storage linkages
- the option-implied distributions whose volatility surfaces and skew reveal market-assessed tail probabilities for weather and policy events
- the cross-market consistency checks where related curves including crush, feed, and energy products must reconcile with the analyst's view)
- the price-scenario construction (the scenario-tree architecture combining weather, policy, and demand branches with probability weights into price-path distributions
- the balance-sheet-propagation engine where scenario assumptions flow through stocks-to-use into price mapping functions per the balance discipline
- the stress-case calibration against historical episodes including 1970s grain booms, 2008 and 2012 spikes, and 2020 negative-oil episodes whose mechanisms inform tail design
- the scenario-to-position translation with the asymmetric-payoff logic of the macro companion's event analysis)
- the forecasting-operations discipline (the seasonal-forecast-calendar where model runs align with report schedules, weather windows, and planting cycles
- the forecast-record systems logging price views against outcomes for calibration review
- the revision-behavior analysis studying how own and consensus estimates evolve through seasons revealing systematic biases
- the nowcast-integration blending high-frequency export-pace, crush, and weather data into current-state assessment per the nowcasting methods of the macro course)
- the model-risk management (the structural-break exposure where support regimes, biotech adoption, shale revolution, and trade wars broke estimated relationships, motivating rolling re-estimation and regime conditioning
- the data-vintage discipline running models on information available at decision time
- the ensemble practice averaging model classes for robustness per the combination findings
- the humility-documentation stating confidence intervals and failure modes alongside every price view) together with the section anti-patterns — the failure library: the single-equation price modeler who regresses price on stocks without simultaneity treatment and calls it forecasting, remedied by the system and scenario approaches
- the ML-black-box yield caller whose satellite model has no agronomic logic and fails in anomaly years, remedied by the hybrid discipline
- the curve-copyist who adopts futures prices as forecast without assessing the risk premium or forming a differential view, remedied by the information-extraction literacy
- the scenario-without-weights builder whose trees list futures but assign no probabilities, remedied by the weighted-distribution requirement
- the unlogged forecaster whose past views conveniently vanish from memory, remedied by the record systems
- and the break-blind estimator whose decade-old pass-through coefficients survive three regime changes, remedied by the rolling re-estimation and regime conditioning with detection methods as the diagnostic

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in agricultural and industrial economics practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in agricultural and industrial economics through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
