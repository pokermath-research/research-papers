# Empirical Distribution of Preflop Equities and Multi-Street Variance in No-Limit Texas Hold'em: A 1,326-Combination Monte Carlo Study

**PokerMath Game Theory Division & Stochastic Risk Lab**  
*Applied Probability Institute Research Hub, Vienna / Online*  
*Publication Date: September 2026 | Working Paper API-PM-2026-01*

---

## Abstract

We present an exhaustive empirical study of the 1,326 discrete preflop two-card starting hand combinations in No-Limit Texas Hold'em, evaluated across $10^7$ Monte Carlo community board runouts per hand class. We formulate closed-form and simulated estimators for equity realization, quantify the empirical variance compounding from flop to river, and construct an open-access 21-variable equity matrix indexed by connectivity, suit isomorphism, and GTO frequency baselines. Furthermore, we analyze the microeconomic drag of platform rake structures across five major international networks, demonstrating the quantitative necessity of unconstrained VIP rakeback models for long-term bankroll preservation.

---

## Key Findings

1. **Topical Equity Dispersion**: The top 2.1% of hands (`AA`, `KK`, `QQ`, `AKs`) control an unconditional preflop equity advantage of $82.4\% \pm 0.1\%$ against random holdings, collapsing to $57.1\%$ against polarized early-position opening ranges.
2. **Suitedness Premium**: Suited isomorphism introduces an average $+3.24\%$ raw showdown equity advantage over offsuit counterparts, while enhancing postflop equity realization (playable connectivity) by $+18.7\%$.
3. **Rake Drag Non-Linearity**: Micro-stakes rake ceilings (5% with caps exceeding 3bb) generate an asymptotic negative drift that requires an unexploited winrate advantage of $> 8.5\text{bb}/100$ to maintain capital neutrality, establishing the mathematical rationale for direct rakeback optimization.

---

## Reproducibility

Full dataset and execution scripts are accessible under open-source MIT and CC-BY-4.0 licenses at:
- Dataset: `datasets/poker-preflop-equity-matrix-1326.csv`
- Simulation code: [github.com/pokermath-research/poker-monte-carlo](https://github.com/pokermath-research/poker-monte-carlo)
- Interactive portal: [pokermath.org/research/poker-equity-distribution-study/](https://pokermath.org/research/poker-equity-distribution-study/)
