# Domain Content Map — Econometric Foundations: Regression and the OLS Machine

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Operate the OLS machine through the regression framework (population-sample distinction, conditional expectation.
2. Model taxonomy), estimation mechanics (Gauss-Markov conditions, coefficient interpretation across log-linear specifications, residual decomposition), inference (sampling distributions, correct confidence-interval and p-value interpretation, multiple testing, F-tests), the causality question (identification, potential outcomes, macro challenges, instrument traditions), specification craft (theory-first form selection, dummy and interaction toolkits, regime shifts), data foundations (measurement error with revised statistics, aggregation, missing data, influential observations), and software practice (Python-R workflow, specification logs, reporting standards), avoiding R-squared chasing, significance hunting, causal smuggling, log abuse, revision blindness, and outlier deletion failures.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the statistical engine with which the fundamental analyst quantifies macro relationships and builds predictive models: the regression framework (the population-versus-sample distinction where the true relationship is never observed and every estimate carries sampling uncertainty; the conditional-expectation interpretation where regression estimates average outcomes given predictors rather than deterministic laws; the linear-model construction with intercept, slopes, and error term whose properties define what estimation can achieve; the econometric-model taxonomy spanning cross-section, time-series, and panel structures with their distinct assumptions); the OLS machinery (the least-squares criterion minimizing squared residuals with its geometric projection interpretation; the Gauss-Markov conditions under which OLS is the best linear unbiased estimator, stated precisely because each assumption gets violated in practice; the coefficient-interpretation skill covering units, marginal effects, and the log-linear specification families including level-level, log-log elasticity, and log-level semi-elasticity forms that dominate applied macro work; the fitted-values and residual decomposition where R-squared measures explained variation without implying causation or out-of-sample power); inference and hypothesis testing (the sampling-distribution logic where coefficient estimates vary across hypothetical samples; standard errors, t-statistics, and confidence intervals with the correct probabilistic interpretation that practitioners routinely botch; p-values and their abuse where significance testing becomes a search procedure; the multiple-testing and specification-search problem where trying enough regressions guarantees false discoveries, the formal version of the data-mining pitfall; the joint-hypothesis F-test for excluded variables); the causality question (the identification problem where correlation estimates confound causal effects with reverse causality, omitted variables, and selection; the potential-outcomes framework giving precise meaning to causal claims; the macro-specific identification challenge where every aggregate variable responds to every other through policy and expectations, motivating the structural approaches of later sections; the natural-experiment and instrument traditions with their macro applications and limits); specification craft (the functional-form selection connecting economic theory to equation form, where the theory-first discipline prevents specification fishing; the included-variable decision balancing omitted-variable bias against irrelevant-variable variance; the dummy-variable toolkit for intercept and slope shifts, seasonality, and regime breaks; the interaction-term construction for conditional effects such as pass-through elasticities that vary with inflation regimes); the data foundations (the measurement-error problem where errors-in-variables attenuates coefficients, acute with revised macro statistics from the national-accounts section; the aggregation issues where grouped data distorts relationships; the missing-data patterns and their non-random mechanisms; the outlier and influential-observation detection whose macro instances are often genuine structural events rather than errors to delete); the software practice (the Python and R workflow with pandas or data-frame handling, estimation libraries, and reproducible scripts per the programming companion; the specification-log discipline documenting every variant tried, the data-mining antidote; the output-reporting standards covering coefficients, standard errors, fit statistics, and sample definition) together with the section anti-patterns — the failure library: the R-squared-chaser who equates high in-sample fit with predictive validity, remedied by the out-of-sample evaluation discipline of the forecasting section; the significance-hunter who adds regressors until stars appear, remedied by the specification log and multiple-testing awareness; the causal-claim smugler who presents regression coefficients as policy effects without identification argument, remedied by the potential-outcomes literacy; the log-transform abuser who applies logs to zero-containing or negative series breaking the mathematics, remedied by the functional-form diagnostics; the revision-blind estimator who regresses final-vintage data while trading first-vintage reality, remedied by the real-time-data practice; and the outlier-deleter who silently drops crisis observations that carry the most information, remedied by the influence-analysis and structural-break literacy with detection methods as the diagnostic.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the statistical engine with which the fundamental analyst quantifies macro relationships and builds predictive models
- the regression framework (the population-versus-sample distinction where the true relationship is never observed and every estimate carries sampling uncertainty
- the conditional-expectation interpretation where regression estimates average outcomes given predictors rather than deterministic laws
- the linear-model construction with intercept, slopes, and error term whose properties define what estimation can achieve
- the econometric-model taxonomy spanning cross-section, time-series, and panel structures with their distinct assumptions)
- the OLS machinery (the least-squares criterion minimizing squared residuals with its geometric projection interpretation
- the Gauss-Markov conditions under which OLS is the best linear unbiased estimator, stated precisely because each assumption gets violated in practice
- the coefficient-interpretation skill covering units, marginal effects, and the log-linear specification families including level-level, log-log elasticity, and log-level semi-elasticity forms that dominate applied macro work
- the fitted-values and residual decomposition where R-squared measures explained variation without implying causation or out-of-sample power)
- inference and hypothesis testing (the sampling-distribution logic where coefficient estimates vary across hypothetical samples
- standard errors, t-statistics, and confidence intervals with the correct probabilistic interpretation that practitioners routinely botch
- p-values and their abuse where significance testing becomes a search procedure
- the multiple-testing and specification-search problem where trying enough regressions guarantees false discoveries, the formal version of the data-mining pitfall
- the joint-hypothesis F-test for excluded variables)
- the causality question (the identification problem where correlation estimates confound causal effects with reverse causality, omitted variables, and selection
- the potential-outcomes framework giving precise meaning to causal claims
- the macro-specific identification challenge where every aggregate variable responds to every other through policy and expectations, motivating the structural approaches of later sections
- the natural-experiment and instrument traditions with their macro applications and limits)
- specification craft (the functional-form selection connecting economic theory to equation form, where the theory-first discipline prevents specification fishing
- the included-variable decision balancing omitted-variable bias against irrelevant-variable variance
- the dummy-variable toolkit for intercept and slope shifts, seasonality, and regime breaks
- the interaction-term construction for conditional effects such as pass-through elasticities that vary with inflation regimes)
- the data foundations (the measurement-error problem where errors-in-variables attenuates coefficients, acute with revised macro statistics from the national-accounts section
- the aggregation issues where grouped data distorts relationships
- the missing-data patterns and their non-random mechanisms
- the outlier and influential-observation detection whose macro instances are often genuine structural events rather than errors to delete)
- the software practice (the Python and R workflow with pandas or data-frame handling, estimation libraries, and reproducible scripts per the programming companion
- the specification-log discipline documenting every variant tried, the data-mining antidote
- the output-reporting standards covering coefficients, standard errors, fit statistics, and sample definition) together with the section anti-patterns — the failure library: the R-squared-chaser who equates high in-sample fit with predictive validity, remedied by the out-of-sample evaluation discipline of the forecasting section
- the significance-hunter who adds regressors until stars appear, remedied by the specification log and multiple-testing awareness
- the causal-claim smugler who presents regression coefficients as policy effects without identification argument, remedied by the potential-outcomes literacy
- the log-transform abuser who applies logs to zero-containing or negative series breaking the mathematics, remedied by the functional-form diagnostics
- the revision-blind estimator who regresses final-vintage data while trading first-vintage reality, remedied by the real-time-data practice
- and the outlier-deleter who silently drops crisis observations that carry the most information, remedied by the influence-analysis and structural-break literacy with detection methods as the diagnostic

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in macroeconomics and econometrics practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in macroeconomics and econometrics through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
