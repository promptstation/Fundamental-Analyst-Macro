# Domain Content Map — Time-Series Econometrics: Stationarity, Dynamics, and Cointegration

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Command macro time-series econometrics through the stationarity framework (definitions, trend versus difference stationarity, unit-root persistence, ACF-PACF reading), testing toolkit (ADF-Perron-KPSS confirm pairs, break-aware tests, panel methods), the ARMA-ARIMA family (components and conditions, Box-Jenkins cycle, seasonal extension, parsimony comparison), VAR systems (structure and estimation, impulse responses with identification honesty, variance decomposition, structural traditions), cointegration (concept and equilibrium modeling, Engle-Granger and Johansen methods, error-correction representation with adjustment speeds, spurious-resolution testing), volatility and regimes (GARCH clustering, Markov switching, local projections), fractional persistence, and the practical workflow (preparation sequence, unit-root-first protocol, theory-prior cointegration search, forecast-oriented selection, real-time vintages), avoiding levels regression, differencing overkill, unidentified VAR reading, cointegration fishing, ECM ignorance, GARCH misuse, and switching overfitting failures.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the specialized econometrics of macro time series where trends, persistence, and long-run relationships demand purpose-built methods: the stationarity framework (the strict-versus-covariance-stationarity definitions where mean, variance, and autocovariances must be time-invariant for standard inference; the trend-stationary versus difference-stationary distinction whose confusion generates spurious results; the unit-root concept where shocks persist permanently, the defining feature of most macro series; the autocorrelation-function and partial-autocorrelation reading for dependence structure); the unit-root testing toolkit (the Dickey-Fuller and augmented-DF tests with their lag-selection and deterministic-term decisions; the Phillips-Perron alternative handling serial correlation non-parametrically; the KPSS test reversing the null to stationarity with the confirm-pair practice of running both directions; the structural-break-aware tests where ignoring breaks biases toward finding unit roots; the panel unit-root methods for cross-country macro analysis); the ARMA and ARIMA family (the autoregressive and moving-average components with their stationarity and invertibility conditions; the Box-Jenkins identification-estimation-diagnosis cycle; the ARIMA differencing integration for unit-root series; the seasonal-ARIMA extension for monthly macro data; the model-comparison discipline where parsimony beats fit through information criteria); the VAR revolution (the vector-autoregression structure treating every variable as endogenous, answering the simultaneous-equations critique through atheoretical reduced form; the VAR estimation and lag-order selection; the impulse-response analysis tracing shock propagation with the identification problem requiring ordering assumptions, sign restrictions, or narrative approaches; the forecast-error-variance decomposition quantifying shock contributions; the structural-VAR traditions identifying policy shocks central to macro-finance research); the cointegration system (the cointegration concept where non-stationary series share stochastic trends leaving stationary long-run combinations, the formal basis for equilibrium-relationship modeling such as parity conditions and pass-through systems; the Engle-Granger two-step approach with its single-cointegrating-vector limitation; the Johansen multivariate methodology estimating cointegrating rank and vectors; the error-correction-model representation where short-run dynamics adjust toward long-run equilibrium with the speed-of-adjustment coefficient as a directly interpretable trading parameter; the spurious-versus-cointegrated regression distinction resolved through residual stationarity testing); the volatility and regime dynamics (the ARCH and GARCH conditional-variance models capturing volatility clustering relevant to macro-surprise impact analysis; the Markov-switching models formalizing the regime framework of the cycle section with estimated transition probabilities; the local-projection method estimating impulse responses robustly under misspecification); the long-memory and fractional concepts (the fractional-integration continuum between stationarity and unit roots; the persistence-measurement refinements for series like inflation whose memory exceeds ARMA capacity); the practical modeling workflow (the data-preparation sequence covering logs, differencing, seasonality, and outlier treatment; the unit-root-first protocol testing every series before regression; the cointegration-search discipline when theory predicts long-run relationships; the forecast-oriented model selection where in-sample diagnostics yield to out-of-sample comparison per the next section; the real-time-vintage construction for genuine backtesting of macro models) together with the section anti-patterns — the failure library: the levels-regressor who regresses non-stationary series in levels and reports significant nonsense, remedied by the unit-root-first protocol; the differencing-overkiller who differences stationary series destroying long-run information and inducing MA-unit artifacts, remedied by the confirm-pair testing; the VAR-interpreter who reads impulse responses from unidentified reduced forms as causal effects, remedied by the identification-transparency discipline; the cointegration-fisherman who searches variable combinations until some vector cointegrates, remedied by the theory-prior requirement; the ECM-ignorer who models long-run equilibrium without the adjustment dynamics that make it tradable, remedied by the error-correction representation; the GARCH-forcaster who extrapolates volatility models beyond their conditional-variance purpose into mean prediction, remedied by the purpose-boundary literacy; and the switching-model overfitter who estimates regime models with more states than data supports, remedied by the parsimony and out-of-sample discipline with detection methods as the diagnostic.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the specialized econometrics of macro time series where trends, persistence, and long-run relationships demand purpose-built methods
- the stationarity framework (the strict-versus-covariance-stationarity definitions where mean, variance, and autocovariances must be time-invariant for standard inference
- the trend-stationary versus difference-stationary distinction whose confusion generates spurious results
- the unit-root concept where shocks persist permanently, the defining feature of most macro series
- the autocorrelation-function and partial-autocorrelation reading for dependence structure)
- the unit-root testing toolkit (the Dickey-Fuller and augmented-DF tests with their lag-selection and deterministic-term decisions
- the Phillips-Perron alternative handling serial correlation non-parametrically
- the KPSS test reversing the null to stationarity with the confirm-pair practice of running both directions
- the structural-break-aware tests where ignoring breaks biases toward finding unit roots
- the panel unit-root methods for cross-country macro analysis)
- the ARMA and ARIMA family (the autoregressive and moving-average components with their stationarity and invertibility conditions
- the Box-Jenkins identification-estimation-diagnosis cycle
- the ARIMA differencing integration for unit-root series
- the seasonal-ARIMA extension for monthly macro data
- the model-comparison discipline where parsimony beats fit through information criteria)
- the VAR revolution (the vector-autoregression structure treating every variable as endogenous, answering the simultaneous-equations critique through atheoretical reduced form
- the VAR estimation and lag-order selection
- the impulse-response analysis tracing shock propagation with the identification problem requiring ordering assumptions, sign restrictions, or narrative approaches
- the forecast-error-variance decomposition quantifying shock contributions
- the structural-VAR traditions identifying policy shocks central to macro-finance research)
- the cointegration system (the cointegration concept where non-stationary series share stochastic trends leaving stationary long-run combinations, the formal basis for equilibrium-relationship modeling such as parity conditions and pass-through systems
- the Engle-Granger two-step approach with its single-cointegrating-vector limitation
- the Johansen multivariate methodology estimating cointegrating rank and vectors
- the error-correction-model representation where short-run dynamics adjust toward long-run equilibrium with the speed-of-adjustment coefficient as a directly interpretable trading parameter
- the spurious-versus-cointegrated regression distinction resolved through residual stationarity testing)
- the volatility and regime dynamics (the ARCH and GARCH conditional-variance models capturing volatility clustering relevant to macro-surprise impact analysis
- the Markov-switching models formalizing the regime framework of the cycle section with estimated transition probabilities
- the local-projection method estimating impulse responses robustly under misspecification)
- the long-memory and fractional concepts (the fractional-integration continuum between stationarity and unit roots
- the persistence-measurement refinements for series like inflation whose memory exceeds ARMA capacity)
- the practical modeling workflow (the data-preparation sequence covering logs, differencing, seasonality, and outlier treatment
- the unit-root-first protocol testing every series before regression
- the cointegration-search discipline when theory predicts long-run relationships
- the forecast-oriented model selection where in-sample diagnostics yield to out-of-sample comparison per the next section
- the real-time-vintage construction for genuine backtesting of macro models) together with the section anti-patterns — the failure library: the levels-regressor who regresses non-stationary series in levels and reports significant nonsense, remedied by the unit-root-first protocol
- the differencing-overkiller who differences stationary series destroying long-run information and inducing MA-unit artifacts, remedied by the confirm-pair testing
- the VAR-interpreter who reads impulse responses from unidentified reduced forms as causal effects, remedied by the identification-transparency discipline
- the cointegration-fisherman who searches variable combinations until some vector cointegrates, remedied by the theory-prior requirement
- the ECM-ignorer who models long-run equilibrium without the adjustment dynamics that make it tradable, remedied by the error-correction representation
- the GARCH-forcaster who extrapolates volatility models beyond their conditional-variance purpose into mean prediction, remedied by the purpose-boundary literacy
- and the switching-model overfitter who estimates regime models with more states than data supports, remedied by the parsimony and out-of-sample discipline with detection methods as the diagnostic

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in macroeconomics and econometrics practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in macroeconomics and econometrics through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
