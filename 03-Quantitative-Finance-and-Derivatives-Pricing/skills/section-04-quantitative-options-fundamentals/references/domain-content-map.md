# Domain Content Map — Options Fundamentals: Payoffs, Strategies, and Asymmetric Expression

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Deploy options through anatomy (call-put definitions with exercise styles, moneyness and value decomposition, expiration mechanics, settlement varieties), payoff discipline (terminal construction, aggregation, profit diagrams with breakevens, path awareness), strategy taxonomy (directional expressions, covered combinations, vertical and calendar spreads, straddle-strangle volatility bets), commodity specifics (futures options, liquidity reality, event structuring, barrier literacy), expression decisions (convexity tradeoffs, timing matching, volatility valuation question, hybrid construction), microstructure (market-maker delta flows, spread and depth assessment, volume-open-interest reading, volatility quotation), and analysis craft (scenario tables, probability-weighted rewards, adjustment planning, sizing integration), avoiding lottery tickets, naked selling, volatility blindness, expiry mismatch, liquidity assumption, and assignment surprise failures.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the option instrument whose asymmetric payoffs let fundamental analysts express views on direction, magnitude, timing, and volatility separately: the option anatomy (the call-put definitions with European and American exercise styles whose early-exercise rights matter for commodity and dividend-paying contexts; the strike-moneyness vocabulary of in, at, and out of the money with the intrinsic-versus-time-value decomposition; the expiration and exercise mechanics including automatic exercise rules and assignment risk on short positions; the settlement varieties across physical delivery of futures positions, cash settlement, and the fixing-linked financial options); the payoff-diagram discipline (the terminal-payoff construction for single options whose kinked asymmetry defines the instrument's character; the position-payoff aggregation where combined holdings sum linearly at expiration; the profit-diagram distinction incorporating premium paid and received, the breakeven arithmetic analysts must run before entry; the payoff-versus-P-and-L-path awareness where mark-to-market evolution before expiration differs from terminal value through the Greeks of the next-next section); the basic strategy taxonomy (the directional expressions of long calls and puts whose defined risk suits event positioning, and short premium whose income compensates tail risk; the covered-call and protective-put combinations synthesizing yield enhancement and insurance respectively; the spread structures of vertical bull and bear spreads trading cost against capped payoff, and the calendar spreads expressing time and volatility views through the curve; the volatility expressions of straddles and strangles betting on magnitude without direction, whose cost the implied-volatility sections analyze); the commodity-option specifics (the futures-option dominance where options on futures inherit margin offsets and delivery-linked exercise into futures positions; the agricultural-option liquidity reality where depth concentrates in front months and round strikes, shaping achievable structures; the event-structuring patterns where report days, weather windows, and policy decisions get expressed through expiry-aligned straddles and spreads per the companion course's event discipline; the exotic-adjacent literacy including barrier features in OTC commodity structures whose knock-out mechanics surprise unwary hedgers); the option-versus-futures expression decision (the convexity tradeoff where options limit loss but pay premium decay while futures carry full linear exposure without carry cost; the timing-tolerance matching where options suit dated catalysts and futures suit open-horizon theses; the implied-versus-forecast-volatility comparison as the core valuation question determining whether options are cheap or expensive relative to the analyst's view; the hybrid-construction practice combining futures cores with option wings to shape risk profiles precisely); the market-microstructure layer (the option-market-maker system quoting two-sided prices managing inventory through delta hedging whose flows feed back into futures markets, the gamma-dynamics preview; the bid-ask and liquidity assessment across strikes and expirations where quoted width and depth determine realistic execution; the volume-versus-open-interest reading distinguishing new positioning from churning; the implied-volatility quotation reality where option prices are quoted and negotiated in volatility terms rather than dollars, the coordinate-system insight the pricing sections formalize); and the strategy-analysis craft (the scenario-table discipline evaluating positions across price paths and time points rather than expiration alone; the risk-reward-ratio and probability-weighting combination where payoff size meets likelihood assessment from the fundamental view; the adjustment-planning where positions carry pre-committed responses to adverse and favorable moves rather than improvisation; the position-sizing integration where option premium risk and futures margin risk combine into total portfolio exposure per the risk sections) together with the section anti-patterns — the failure library: the lottery-ticket buyer who purchases deep out-of-the-money options as cheap direction ignoring the probability-weighted negative expectancy of premium decay, remedied by the probability-payoff discipline; the naked-premium-seller who collects income without tail-risk capital or adjustment plans until one event erases years of premium, remedied by the defined-risk construction; the volatility-blind directionalist who buys options into elevated implied volatility before events and loses even when direction works, remedied by the implied-versus-forecast comparison; the expiry-mismatch structurer whose option expires before the catalyst window opens, remedied by the event-timing alignment; the liquidity-assumer who paper-trades structures whose real execution crosses wide spreads in thin strikes, remedied by the microstructure assessment; and the assignment-surprised short holder who ignores early-exercise and dividend-triggered assignment mechanics, remedied by the exercise-rules literacy with detection methods as the diagnostic.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the option instrument whose asymmetric payoffs let fundamental analysts express views on direction, magnitude, timing, and volatility separately
- the option anatomy (the call-put definitions with European and American exercise styles whose early-exercise rights matter for commodity and dividend-paying contexts
- the strike-moneyness vocabulary of in, at, and out of the money with the intrinsic-versus-time-value decomposition
- the expiration and exercise mechanics including automatic exercise rules and assignment risk on short positions
- the settlement varieties across physical delivery of futures positions, cash settlement, and the fixing-linked financial options)
- the payoff-diagram discipline (the terminal-payoff construction for single options whose kinked asymmetry defines the instrument's character
- the position-payoff aggregation where combined holdings sum linearly at expiration
- the profit-diagram distinction incorporating premium paid and received, the breakeven arithmetic analysts must run before entry
- the payoff-versus-P-and-L-path awareness where mark-to-market evolution before expiration differs from terminal value through the Greeks of the next-next section)
- the basic strategy taxonomy (the directional expressions of long calls and puts whose defined risk suits event positioning, and short premium whose income compensates tail risk
- the covered-call and protective-put combinations synthesizing yield enhancement and insurance respectively
- the spread structures of vertical bull and bear spreads trading cost against capped payoff, and the calendar spreads expressing time and volatility views through the curve
- the volatility expressions of straddles and strangles betting on magnitude without direction, whose cost the implied-volatility sections analyze)
- the commodity-option specifics (the futures-option dominance where options on futures inherit margin offsets and delivery-linked exercise into futures positions
- the agricultural-option liquidity reality where depth concentrates in front months and round strikes, shaping achievable structures
- the event-structuring patterns where report days, weather windows, and policy decisions get expressed through expiry-aligned straddles and spreads per the companion course's event discipline
- the exotic-adjacent literacy including barrier features in OTC commodity structures whose knock-out mechanics surprise unwary hedgers)
- the option-versus-futures expression decision (the convexity tradeoff where options limit loss but pay premium decay while futures carry full linear exposure without carry cost
- the timing-tolerance matching where options suit dated catalysts and futures suit open-horizon theses
- the implied-versus-forecast-volatility comparison as the core valuation question determining whether options are cheap or expensive relative to the analyst's view
- the hybrid-construction practice combining futures cores with option wings to shape risk profiles precisely)
- the market-microstructure layer (the option-market-maker system quoting two-sided prices managing inventory through delta hedging whose flows feed back into futures markets, the gamma-dynamics preview
- the bid-ask and liquidity assessment across strikes and expirations where quoted width and depth determine realistic execution
- the volume-versus-open-interest reading distinguishing new positioning from churning
- the implied-volatility quotation reality where option prices are quoted and negotiated in volatility terms rather than dollars, the coordinate-system insight the pricing sections formalize)
- and the strategy-analysis craft (the scenario-table discipline evaluating positions across price paths and time points rather than expiration alone
- the risk-reward-ratio and probability-weighting combination where payoff size meets likelihood assessment from the fundamental view
- the adjustment-planning where positions carry pre-committed responses to adverse and favorable moves rather than improvisation
- the position-sizing integration where option premium risk and futures margin risk combine into total portfolio exposure per the risk sections) together with the section anti-patterns — the failure library: the lottery-ticket buyer who purchases deep out-of-the-money options as cheap direction ignoring the probability-weighted negative expectancy of premium decay, remedied by the probability-payoff discipline
- the naked-premium-seller who collects income without tail-risk capital or adjustment plans until one event erases years of premium, remedied by the defined-risk construction
- the volatility-blind directionalist who buys options into elevated implied volatility before events and loses even when direction works, remedied by the implied-versus-forecast comparison
- the expiry-mismatch structurer whose option expires before the catalyst window opens, remedied by the event-timing alignment
- the liquidity-assumer who paper-trades structures whose real execution crosses wide spreads in thin strikes, remedied by the microstructure assessment
- and the assignment-surprised short holder who ignores early-exercise and dividend-triggered assignment mechanics, remedied by the exercise-rules literacy with detection methods as the diagnostic

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in quantitative finance and derivatives pricing practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in quantitative finance and derivatives pricing through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
