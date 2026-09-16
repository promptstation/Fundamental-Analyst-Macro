# Domain Content Map — Forward Pricing and Cost of Carry: The No-Arbitrage Baseline

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Master forward pricing through derivation (cash-and-carry replication, reverse arbitrage, cross-class formulas, futures-forward convexity), cost-of-carry anatomy (financing, storage, income, convenience yield as scarcity residual), arbitrage discipline (boundary bands, limits to arbitrage, commodity execution reality, index mechanisms), convergence (delivery and cash settlement theorems, basis path decomposition, failure cases), the covered-interest-parity system (FX derivation, basis as funding stress signal, quotation conventions, post-crisis enforcement), commodity curve interpretation (normal backwardation versus storage theory, term structure as information, seasonal patterns, event signatures), and the pricing web (put-call parity, synthetics, relationship monitoring), avoiding carry forgetting, convenience mysticism, frictionless assumption, convergence blindness, CIP literalism, and parity ignorance failures.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the pricing foundation from which all derivative valuation grows, where arbitrage logic links spot, forward, and futures prices through carrying economics: the forward-pricing derivation (the cash-and-carry replication where borrowing to buy spot and selling forward locks a riskless return unless the forward price equals spot plus carrying cost; the reverse-cash-and-carry completing the bound through short-sale proceeds investment; the forward-price formula across asset classes with dividend, coupon, and convenience-yield adjustments; the forward-versus-futures distinction where daily settlement correlates gains with rate movements creating the convexity adjustment that matters for rate contracts); the cost-of-carry anatomy (the financing component tied to benchmark rates whose SOFR-libra transition history shapes current conventions; the storage-cost component specific to commodities where facility, insurance, and quality-maintenance costs enter carry, connecting to the storage economics of the companion course; the income component spanning dividends, coupons, and lease rates that reduce carry; the convenience-yield component capturing the operational value of holding physical inventory, unobservable directly but inferable as the residual that explains commodity forward discounts below pure cost-of-carry); the arbitrage-discipline analysis (the arbitrage-boundary concept where transaction costs, financing spreads, and operational frictions create bands within which mispricing survives; the limits-to-arbitrage literature where capital constraints, margin dynamics, and horizon mismatches allow persistent deviations, the 2008 and 2020 episodes as evidence; the commodity-arbitrage reality where full-carry storage arbitrages execute only when spreads, warehousing, and quality logistics permit, making agricultural and energy curves partially rather than fully arbitrage-enforced; the index-and-ETF arbitrage mechanisms maintaining equity-product linkage); the futures-spot convergence (the delivery-convergence theorem where physical-delivery contracts force futures to cash at expiration through delivery economics; the cash-settlement convergence through fixing design; the basis-dynamics path where convergence operates through the whole contract life with the predictable roll-down component versus the stochastic basis component; the failed-convergence cases where delivery constraints, quality differentials, or squeezes break the mechanism, the 1970s-80s corner episodes and modern dislocation examples); the covered-interest-parity system (the FX forward derivation from rate differentials as the international carry instance; the cross-currency-basis deviation whose persistence signals dollar funding stress per the macro companion's parity conditions; the forward-points quotation conventions and their counterintuitive sign behavior in high-rate-differential pairs; the CIP-broken-era analysis where balance-sheet costs replaced pure arbitrage enforcement post-2008); the commodity-curve interpretation (the normal-backwardation tradition where Keynes read futures discount as hedger risk payment versus the storage-theory reading of scarcity signals, the century-old debate the curve-mechanics section resolves operationally; the term-structure-as-information discipline where curve shape aggregates global inventory knowledge no single analyst holds; the seasonal-curve patterns in agricultural and energy contracts reflecting harvest and demand calendars; the curve-event reading where supply shocks reprice near months first, creating the bull and bear spread signatures the companion course's balance analysis predicts); and the pricing-relationship web (the put-call parity linking option prices to forwards, the bridge to the options sections; the put-call-forward equivalence variants under different rate conventions; the synthetic-position construction where parity violations become tradeable structures; the relationship-monitoring practice where analysts track theoretical versus observed linkages as market-health diagnostics) together with the section anti-patterns — the failure library: the carry-cost-forgetter who compares futures prices across markets without financing and storage adjustments, seeing arbitrage where costs explain everything, remedied by the cost-of-carry anatomy; the convenience-yield-mystic who invokes unobservable yields to explain any deviation without inventory evidence, remedied by the storage-linked inference discipline; the frictionless-arbitrageur whose paper trades ignore bands, funding spreads, and operational reality, remedied by the limits-to-arbitrage literacy; the convergence-assumer holding basis positions into delivery mechanics they have not verified, remedied by the failed-convergence case library; the CIP-literalist who trades forward-point deviations without balance-sheet and funding constraints analysis, remedied by the broken-CIP framework; and the parity-ignorant option trader who cannot reconstruct forward prices from option quotes or verify option prices against forwards, remedied by the relationship-web fluency with detection methods as the diagnostic.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the pricing foundation from which all derivative valuation grows, where arbitrage logic links spot, forward, and futures prices through carrying economics
- the forward-pricing derivation (the cash-and-carry replication where borrowing to buy spot and selling forward locks a riskless return unless the forward price equals spot plus carrying cost
- the reverse-cash-and-carry completing the bound through short-sale proceeds investment
- the forward-price formula across asset classes with dividend, coupon, and convenience-yield adjustments
- the forward-versus-futures distinction where daily settlement correlates gains with rate movements creating the convexity adjustment that matters for rate contracts)
- the cost-of-carry anatomy (the financing component tied to benchmark rates whose SOFR-libra transition history shapes current conventions
- the storage-cost component specific to commodities where facility, insurance, and quality-maintenance costs enter carry, connecting to the storage economics of the companion course
- the income component spanning dividends, coupons, and lease rates that reduce carry
- the convenience-yield component capturing the operational value of holding physical inventory, unobservable directly but inferable as the residual that explains commodity forward discounts below pure cost-of-carry)
- the arbitrage-discipline analysis (the arbitrage-boundary concept where transaction costs, financing spreads, and operational frictions create bands within which mispricing survives
- the limits-to-arbitrage literature where capital constraints, margin dynamics, and horizon mismatches allow persistent deviations, the 2008 and 2020 episodes as evidence
- the commodity-arbitrage reality where full-carry storage arbitrages execute only when spreads, warehousing, and quality logistics permit, making agricultural and energy curves partially rather than fully arbitrage-enforced
- the index-and-ETF arbitrage mechanisms maintaining equity-product linkage)
- the futures-spot convergence (the delivery-convergence theorem where physical-delivery contracts force futures to cash at expiration through delivery economics
- the cash-settlement convergence through fixing design
- the basis-dynamics path where convergence operates through the whole contract life with the predictable roll-down component versus the stochastic basis component
- the failed-convergence cases where delivery constraints, quality differentials, or squeezes break the mechanism, the 1970s-80s corner episodes and modern dislocation examples)
- the covered-interest-parity system (the FX forward derivation from rate differentials as the international carry instance
- the cross-currency-basis deviation whose persistence signals dollar funding stress per the macro companion's parity conditions
- the forward-points quotation conventions and their counterintuitive sign behavior in high-rate-differential pairs
- the CIP-broken-era analysis where balance-sheet costs replaced pure arbitrage enforcement post-2008)
- the commodity-curve interpretation (the normal-backwardation tradition where Keynes read futures discount as hedger risk payment versus the storage-theory reading of scarcity signals, the century-old debate the curve-mechanics section resolves operationally
- the term-structure-as-information discipline where curve shape aggregates global inventory knowledge no single analyst holds
- the seasonal-curve patterns in agricultural and energy contracts reflecting harvest and demand calendars
- the curve-event reading where supply shocks reprice near months first, creating the bull and bear spread signatures the companion course's balance analysis predicts)
- and the pricing-relationship web (the put-call parity linking option prices to forwards, the bridge to the options sections
- the put-call-forward equivalence variants under different rate conventions
- the synthetic-position construction where parity violations become tradeable structures
- the relationship-monitoring practice where analysts track theoretical versus observed linkages as market-health diagnostics) together with the section anti-patterns — the failure library: the carry-cost-forgetter who compares futures prices across markets without financing and storage adjustments, seeing arbitrage where costs explain everything, remedied by the cost-of-carry anatomy
- the convenience-yield-mystic who invokes unobservable yields to explain any deviation without inventory evidence, remedied by the storage-linked inference discipline
- the frictionless-arbitrageur whose paper trades ignore bands, funding spreads, and operational reality, remedied by the limits-to-arbitrage literacy
- the convergence-assumer holding basis positions into delivery mechanics they have not verified, remedied by the failed-convergence case library
- the CIP-literalist who trades forward-point deviations without balance-sheet and funding constraints analysis, remedied by the broken-CIP framework
- and the parity-ignorant option trader who cannot reconstruct forward prices from option quotes or verify option prices against forwards, remedied by the relationship-web fluency with detection methods as the diagnostic

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in quantitative finance and derivatives pricing practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in quantitative finance and derivatives pricing through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
