# PokerMath Open Science Research Archive

[![License: CC-BY-4.0](https://img.shields.io/badge/License-CC--BY--4.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Preprint: API-PM-2026-01](https://img.shields.io/badge/Preprint-API--PM--2026--01-purple.svg)](https://pokermath.org/research/)
[![Reproducibility: Verified](https://img.shields.io/badge/Reproducibility-Verified%20(Seed%2042)-brightgreen.svg)](https://github.com/pokermath-research/research-papers)
[![Portal](https://img.shields.io/badge/Portal-pokermath.org-0d6b3d.svg)](https://pokermath.org)

Open-access scientific repository hosting preprints, technical whitepapers, empirical datasets, and deterministic reproducibility scripts published by the **PokerMath Research Group** at [pokermath.org](https://pokermath.org).

---

## Papers in this Repository

### [Paper API-PM-2026-01](./papers/poker-equity-empirical-study-2026.md)
**"Empirical Distribution of Preflop Equities and Multi-Street Variance in No-Limit Texas Hold'em: A 1,326-Combination Monte Carlo Study"**
- *Authors*: PM Game Theory Division & Stochastic Risk Lab
- *Files*: Markdown preprint in `papers/`, full 1,326-combination 21-variable CSV dataset in `datasets/`
- *Live Paper with KaTeX Math*: [pokermath.org/research/poker-equity-distribution-study/](https://pokermath.org/en/research/poker-equity-distribution-study/)

---

## Deterministic Reproducibility

To audit the dataset schema and verify empirical convergence of key theoretical anchor matchups ($AA$ vs $KK$, $AKo$ vs $QQ$, $AK$ vs $AQ$):

```bash
python reproduce.py --trials 20000 --seed 42
```

---

## Citation

```bibtex
@article{pokermath2026empirical,
  title={Empirical Distribution of Preflop Equities and Multi-Street Variance in No-Limit Texas Hold'em: A 1,326-Combination Monte Carlo Study},
  author={{PokerMath Research Group}},
  journal={Applied Probability Institute Research Hub},
  year={2026},
  url={https://pokermath.org/research/poker-equity-distribution-study/}
}
```
