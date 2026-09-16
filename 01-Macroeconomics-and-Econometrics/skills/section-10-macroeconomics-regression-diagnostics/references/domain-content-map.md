# Domain Content Map — Regression Diagnostics: When Assumptions Break

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Diagnose broken assumptions through heteroskedasticity (detection tests, robust errors, WLS), autocorrelation (DW and Breusch-Godfrey, HAC corrections, the spurious-regression bridge to unit roots), multicollinearity (VIF diagnostics, variance versus instability distinction, remedy hierarchy), non-normality (residual distribution checks, fat-tail reality, robust alternatives), specification failures (RESET, omitted-variable probing, Chow-CUSUM stability tests, break taxonomy and dating), endogeneity (reverse causality, simultaneous-equations bias, Hausman logic, 2SLS with weak-instrument diagnostics), the diagnostic workflow (residual-first, test batteries, remedy sequencing, documentation), and macro-specific traps (revision divergence, seasonal residue, aggregation heterogeneity, look-ahead bias), avoiding blind OLS, HAC washing, spurious publishing, VIF panic, Chow fishing, and real-time ignorance failures.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the diagnostic toolkit for detecting and correcting the assumption violations that plague macro data: heteroskedasticity (the non-constant-variance reality of cross-section and some macro series where OLS stays unbiased but standard errors fail; the White and Breusch-Pagan detection tests; the robust-standard-error corrections of the White and Huber lineage with the small-sample cautions; the weighted-least-squares alternative when the variance structure is known); autocorrelation (the serial-correlation ubiquity in macro time series where consecutive observations share trend and cycle components; the Durbin-Watson and Breusch-Godfrey detection with the lag-order selection; the consequences split where coefficient bias is absent under strict exogeneity but inference collapses; the Newey-West HAC corrections for autocorrelation-and-heteroskedasticity-robust inference; the spurious-regression danger where trending series produce significant relationships from common trends alone, the bridge to the unit-root theory of the next section); multicollinearity (the high-correlation reality of macro aggregates where inflation, rates, and activity variables move together; the variance-inflation diagnostics; the distinction between harmless collinearity inflating variance and pathological near-singularity destabilizing estimates; the remedy hierarchy where more data beats variable-dropping in most cases); non-normality and heavy tails (the residual-distribution checks with skew and kurtosis measures and the Jarque-Bera test; the fat-tail reality of financial and macro data where crisis observations dominate tail behavior; the normality-relevance clarification where inference depends on large-sample approximations rather than exact normality; the robust-regression alternatives for genuinely contaminated errors); specification failures (the RESET-style functional-form tests; the omitted-variable probing through residual correlation analysis; the parameter-stability tests including Chow tests for known breakpoints and the CUSUM monitoring for unknown drift; the structural-break taxonomy distinguishing abrupt regime shifts from gradual evolution, with the break-dating methods that connect to the regime framework of the cycle section); endogeneity and simultaneity (the reverse-causality detection through timing and economic logic; the simultaneous-equations bias where market-clearing data mixes supply and demand shifts, the identification problem in its classic commodity form; the Hausman-test logic for endogenous-regressor detection; the two-stage-least-squares remedy with the instrument-validity requirements and weak-instrument diagnostics); the diagnostic workflow (the residual-plot-first habit where visual inspection precedes formal tests; the test-battery discipline running the standard suite on every specification; the remedy-sequencing logic where data problems get fixed before model problems; the documentation requirement recording diagnostics and decisions in the specification log from the previous section); and the macro-data-specific traps (the preliminary-versus-revised data divergence where diagnostics on final vintages misrepresent real-time conditions; the seasonal-adjustment residue where adjustment artifacts create autocorrelation patterns; the aggregation-induced heterogeneity where national estimates mask regional variation; the look-ahead bias in real-time analysis where later information leaks into predictors through revisions and benchmark restatements) together with the section anti-patterns — the failure library: the blind-OLS runner who never plots residuals and ships invalid inference, remedied by the residual-first workflow; the HAC-washing practitioner who applies robust standard errors to fix a misspecified model, remedied by the remedy-sequencing logic; the spurious-regression publisher who celebrates R-squared of 0.9 between two trends, remedied by the unit-root literacy and detrending discipline; the VIF-panic dropper who removes collinear variables destroying the theoretical structure, remedied by the harmless-versus-pathological distinction; the Chow-test fisher who searches breakpoints until stability fails somewhere, remedied by the multiple-testing discipline; and the real-time ignoramus whose diagnostics run on vintages unavailable when trades were placed, remedied by the vintage-aware practice with detection methods as the diagnostic.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the diagnostic toolkit for detecting and correcting the assumption violations that plague macro data
- heteroskedasticity (the non-constant-variance reality of cross-section and some macro series where OLS stays unbiased but standard errors fail
- the White and Breusch-Pagan detection tests
- the robust-standard-error corrections of the White and Huber lineage with the small-sample cautions
- the weighted-least-squares alternative when the variance structure is known)
- autocorrelation (the serial-correlation ubiquity in macro time series where consecutive observations share trend and cycle components
- the Durbin-Watson and Breusch-Godfrey detection with the lag-order selection
- the consequences split where coefficient bias is absent under strict exogeneity but inference collapses
- the Newey-West HAC corrections for autocorrelation-and-heteroskedasticity-robust inference
- the spurious-regression danger where trending series produce significant relationships from common trends alone, the bridge to the unit-root theory of the next section)
- multicollinearity (the high-correlation reality of macro aggregates where inflation, rates, and activity variables move together
- the variance-inflation diagnostics
- the distinction between harmless collinearity inflating variance and pathological near-singularity destabilizing estimates
- the remedy hierarchy where more data beats variable-dropping in most cases)
- non-normality and heavy tails (the residual-distribution checks with skew and kurtosis measures and the Jarque-Bera test
- the fat-tail reality of financial and macro data where crisis observations dominate tail behavior
- the normality-relevance clarification where inference depends on large-sample approximations rather than exact normality
- the robust-regression alternatives for genuinely contaminated errors)
- specification failures (the RESET-style functional-form tests
- the omitted-variable probing through residual correlation analysis
- the parameter-stability tests including Chow tests for known breakpoints and the CUSUM monitoring for unknown drift
- the structural-break taxonomy distinguishing abrupt regime shifts from gradual evolution, with the break-dating methods that connect to the regime framework of the cycle section)
- endogeneity and simultaneity (the reverse-causality detection through timing and economic logic
- the simultaneous-equations bias where market-clearing data mixes supply and demand shifts, the identification problem in its classic commodity form
- the Hausman-test logic for endogenous-regressor detection
- the two-stage-least-squares remedy with the instrument-validity requirements and weak-instrument diagnostics)
- the diagnostic workflow (the residual-plot-first habit where visual inspection precedes formal tests
- the test-battery discipline running the standard suite on every specification
- the remedy-sequencing logic where data problems get fixed before model problems
- the documentation requirement recording diagnostics and decisions in the specification log from the previous section)
- and the macro-data-specific traps (the preliminary-versus-revised data divergence where diagnostics on final vintages misrepresent real-time conditions
- the seasonal-adjustment residue where adjustment artifacts create autocorrelation patterns
- the aggregation-induced heterogeneity where national estimates mask regional variation
- the look-ahead bias in real-time analysis where later information leaks into predictors through revisions and benchmark restatements) together with the section anti-patterns — the failure library: the blind-OLS runner who never plots residuals and ships invalid inference, remedied by the residual-first workflow
- the HAC-washing practitioner who applies robust standard errors to fix a misspecified model, remedied by the remedy-sequencing logic
- the spurious-regression publisher who celebrates R-squared of 0.9 between two trends, remedied by the unit-root literacy and detrending discipline
- the VIF-panic dropper who removes collinear variables destroying the theoretical structure, remedied by the harmless-versus-pathological distinction
- the Chow-test fisher who searches breakpoints until stability fails somewhere, remedied by the multiple-testing discipline
- and the real-time ignoramus whose diagnostics run on vintages unavailable when trades were placed, remedied by the vintage-aware practice with detection methods as the diagnostic

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in macroeconomics and econometrics practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in macroeconomics and econometrics through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
