# awesome-causality-algorithms with stars

An index of algorithms in

* machine learning for causal inference: solves causal inference problems
* causal machine learning: solves ML problems

**Reproducibility is important!** We will remove those methods without open-source code unless it is a survey/review paper.

Please cite [our survey paper](https://arxiv.org/pdf/1809.09337) if this index is helpful.

```
@article{guo2020survey,
  title={A survey of learning causality with data: Problems and methods},
  author={Guo, Ruocheng and Cheng, Lu and Li, Jundong and Hahn, P Richard and Liu, Huan},
  journal={ACM Computing Surveys (CSUR)},
  volume={53},
  number={4},
  pages={1--37},
  year={2020},
  publisher={ACM New York, NY, USA}
}
```

## Table of Contents

* [Toolboxes](#toolboxes)
* [Causal Effect Estimation](#causal-effect-estimation)
* [Causal Machine Learning](#causal-machine-learning)
* [Causal Discovery](#causal-discovery-1)

Contributions are welcome, see [CONTRIBUTING.md](CONTRIBUTING.md).

## Toolboxes

### Comprehensive

| Name                                                           | Code                                                                                                  | Comment                                                                                                                       |
| -------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| [causal-learn](https://causal-learn.readthedocs.io/en/latest/) | [Python](https://github.com/py-why/causal-learn) ⭐ 1,708 \| 🐛 73 \| 🌐 Python \| 📅 2026-09-04       | Causal Discovery, Causal Representation Learning, Statistical Tests.                                                          |
| Trustworthy AI                                                 | [Python](https://github.com/huawei-noah/trustworthyAI) ⭐ 1,154 \| 🐛 24 \| 🌐 Python \| 📅 2026-09-21 | Causal Structure Learning, Causal Disentangled Representation Learning, gCastle (or pyCastle, pCastle).                       |
| [YLearn](https://ylearn.readthedocs.io/en/latest/)             | [Python](https://github.com/DataCanvasIO/YLearn) ⭐ 434 \| 🐛 12 \| 🌐 Python \| 📅 2025-06-28         | Python package for causal discovery, causal effect identification/estimation, counterfactual inference, policy learning, etc. |

### Treatment Effect Estimation / Uplift Modeling

| Name          | Paper/Documentation                                                                                                                                                         | Venue                     | Code                                                                                                 | Comment                                                                                                                                                   |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- | ---------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DoWhy         | [Tutorial on Causal Inference and Counterfactual Reasoning](https://causalinference.gitlab.io/kdd-tutorial/)                                                                | KDD 2018                  | [Python](https://github.com/py-why/dowhy) ⭐ 8,384 \| 🐛 206 \| 🌐 Python \| 📅 2026-10-31            | Python library for causal inference that supports explicit modeling and testing of causal assumptions.                                                    |
| EconML        | [Causal Inference and Machine Learning in Practice with EconML and CausalML](https://causal-machine-learning.github.io/kdd2021-tutorial/)                                   | KDD 2021                  | [Python](https://github.com/py-why/EconML) ⭐ 4,834 \| 🐛 429 \| 🌐 Jupyter Notebook \| 📅 2026-10-28 | Python package that applies the power of machine learning techniques to estimate individualized causal responses from observational or experimental data. |
| CausalML      | [Causalml: Python package for causal machine learning](https://arxiv.org/pdf/2002.11631.pdf)                                                                                | arXiv                     | [Python](https://github.com/uber/causalml) ⭐ 6,037 \| 🐛 14 \| 🌐 Python \| 📅 2026-10-12            | Uplift modeling and causal inference with machine learning algorithms                                                                                     |
| JustCause     | [Underlying thesis](https://justcause.readthedocs.io/en/latest/_downloads/e054f7a0fc9cf9e680173600cb4b4350/thesis-mfranz.pdf)                                               | NA                        | [Python](https://github.com/inovex/justcause) ⭐ 141 \| 🐛 8 \| 🌐 Jupyter Notebook \| 📅 2020-03-23  | For evaluation of heterogeneous treatment effect estimators on common reference as well as synthetic data.                                                |
| WhyNot        | [Documentation](https://whynot.readthedocs.io/en/latest/)                                                                                                                   | NA                        | [Python](https://github.com/socialfoundations/whynot) ⭐ 428 \| 🐛 6 \| 🌐 Python \| 📅 2026-08-11    | An experimental sandbox for causal inference and decision making in dynamics.                                                                             |
| scikit-uplift | [Documentation](https://www.uplift-modeling.com/en/latest/index.html) and [User guide for uplift modeling](https://www.uplift-modeling.com/en/latest/user_guide/index.html) | NA                        | [Python](https://github.com/maks-sh/scikit-uplift) ⭐ 819 \| 🐛 42 \| 🌐 Python \| 📅 2023-10-21      | Uplift modeling in scikit-learn style in python.                                                                                                          |
| DoubleML      | [Double/debiased machine learning for treatment and structural parameters](https://doi.org/10.1111/ectj.12097)                                                              | Econometrics Journal 2018 | [Python](https://github.com/DoubleML/doubleml-for-py) ⭐ 795 \| 🐛 21 \| 🌐 Python \| 📅 2026-10-30   | Double machine learning framework for causal parameters; also available in R.                                                                             |
| CausalPy      | NA                                                                                                                                                                          | NA                        | [Python](https://github.com/pymc-labs/CausalPy) ⭐ 1,210 \| 🐛 171 \| 🌐 Python \| 📅 2026-10-31      | Bayesian and quasi-experimental causal inference (synthetic control, DiD, RDD, IV) built on PyMC.                                                         |

### Causal Discovery

| Name                                                                                                        | Paper                                                                                                                                                               | Venue                            | Code                                                                                                                                                                    | Comment                                                                                                                                                                   |
| ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Bench Press](https://benchpressdocs.readthedocs.io/en/latest/)                                             | [Benchpress: a scalable and versatile workflow for benchmarking structure learning algorithms for graphical models](https://arxiv.org/abs/2107.03863) — Rios et al. | arXiv 2021                       | [Code](https://github.com/felixleopoldo/benchpress) ⭐ 86 \| 🐛 28 \| 🌐 Python \| 📅 2026-10-09                                                                         | Reproducible and scalable execution and benchmarks of **41** structure learning algorithms supporting multiple language                                                   |
| [causal-learn](https://causal-learn.readthedocs.io/en/latest/)                                              | [Causal-learn: Causal Discovery in Python](https://jmlr.org/papers/volume25/23-0970/23-0970.pdf) — Zheng et al.                                                     | JMLR 2024                        | [Python](https://github.com/py-why/causal-learn) ⭐ 1,708 \| 🐛 73 \| 🌐 Python \| 📅 2026-09-04                                                                         | Causal Discovery, Causal Representation Learning, Statistical Tests.                                                                                                      |
| [TETRAD R/Java](https://github.com/cmu-phil/tetrad) ⭐ 448 \| 🐛 4 \| 🌐 Java \| 📅 2026-10-31               | [TETRAD: A Toolbox for Causal Discovery](https://www.atmos.colostate.edu/~iebert/PAPERS/CI2018_paper_35.pdf) — Ramsey et al.                                        | CI 2018                          | [R](https://github.com/bd2kccd/r-causal) ⭐ 36 \| 🐛 31 \| 🌐 Java \| 📅 2024-09-05/[Java](https://github.com/cmu-phil/tetrad) ⭐ 448 \| 🐛 4 \| 🌐 Java \| 📅 2026-10-31 | Causal Discovery Toolbox from CMU                                                                                                                                         |
| Causaldag                                                                                                   | NA                                                                                                                                                                  | NA                               | [Code](https://github.com/uhlerlab/causaldag) ⭐ 164 \| 🐛 13 \| 🌐 JavaScript \| 📅 2023-04-12                                                                          | Python package for the creation, manipulation, and learning of Causal DAGs                                                                                                |
| CausalNex                                                                                                   | NA                                                                                                                                                                  | NA                               | [Python](https://github.com/mckinsey/causalnex) ⭐ 2,492 \| 🐛 35 \| 🌐 Python \| 📅 2026-08-31                                                                          | A toolkit for causal reasoning with Bayesian Networks.                                                                                                                    |
| CausalDiscoveryToolbox                                                                                      | [Causal Discovery Toolbox: Uncover causal relationships in Python](https://arxiv.org/pdf/1903.02278) — Kalainathan and Goudet                                       | arXiv 2019                       | [Python](https://github.com/diviyank/CausalDiscoveryToolbox) ⭐ 9 \| 🐛 0 \| 📅 2020-02-04                                                                               |                                                                                                                                                                           |
| pgmpy                                                                                                       | NA                                                                                                                                                                  | NA                               | [Python](https://github.com/pgmpy/pgmpy) ⭐ 3,365 \| 🐛 676 \| 🌐 Python \| 📅 2026-10-28                                                                                | Probabilistic graphical models, structure learning and causal inference.                                                                                                  |
| Tigramite                                                                                                   | NA                                                                                                                                                                  | NA                               | [Python](https://github.com/jakobrunge/tigramite) ⭐ 1,733 \| 🐛 20 \| 🌐 Jupyter Notebook \| 📅 2026-01-14                                                              | Causal discovery and inference for time series (PCMCI and variants).                                                                                                      |
| DoDiscover                                                                                                  | NA                                                                                                                                                                  | NA                               | [Python](https://github.com/py-why/dodiscover) ⭐ 116 \| 🐛 60 \| 🌐 Python \| 📅 2026-10-19                                                                             | PyWhy library for causal discovery, including with latent confounders.                                                                                                    |
| Causica                                                                                                     | NA                                                                                                                                                                  | NA                               | [Python](https://github.com/microsoft/causica) ⭐ 537 \| 🐛 89 \| 🌐 Python \| 📅 2026-10-30                                                                             | Deep end-to-end causal inference (DECI) and related models from Microsoft.                                                                                                |
| LiNGAM                                                                                                      | NA                                                                                                                                                                  | NA                               | [Python](https://github.com/cdt15/lingam) ⭐ 510 \| 🐛 30 \| 🌐 Python \| 📅 2026-10-27                                                                                  | Implementations of the LiNGAM family of non-Gaussian causal discovery methods.                                                                                            |
| [Causal Chambers](https://github.com/juangamella/causal-chamber) ⭐ 73 \| 🐛 1 \| 🌐 Python \| 📅 2026-10-03 | [Causal chambers as a real-world physical testbed for AI methodology](https://doi.org/10.1038/s42256-024-00964-x) — Gamella et al.                                  | Nature Machine Intelligence 2025 | [Python](https://github.com/juangamella/causal-chamber-package) ⭐ 16 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2026-10-29                                                    | Real-world datasets with interventions and validated ground-truth graphs from two physical devices; the Python package loads the data and graphs and includes simulators. |
| [causal-automata](https://causal-automata.readthedocs.io/en/latest/)                                        | NA                                                                                                                                                                  | NA                               | [Python](https://github.com/kazuyamagiwa/causal-automata) ⭐ 0 \| 🐛 1 \| 🌐 Python \| 📅 2026-10-31                                                                     | A relatively fast, GPU-native causal discovery and DAG structure learning package in JAX/NumPy via synchronous cellular automata and a 1D topological elevation field.    |

### Root Cause Analysis

| Name                                        | Paper | Venue | Code                                                                | Comments                                                                           |
| ------------------------------------------- | ----- | ----- | ------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| [Chaos Genius](https://www.chaosgenius.io/) | NA    | NA    | [Python](https://github.com/chaos-genius/chaos_genius/) ⚠️ Archived | ML powered analytics engine for outlier/anomaly detection and root cause analysis. |

## Causal Effect Estimation

### Survey Papers

| Name       | Paper                                                                         | Venue |
| ---------- | ----------------------------------------------------------------------------- | ----- |
| Yao et al. | [A survey on causal inference](https://arxiv.org/abs/2002.02770) — Yao et al. | TKDD  |

### With i.i.d Data

#### Individual Treatment Effect (ITE) / Conditional Average Treatment Effect (CATE)

##### Deep Learning based methods

| Name                              | Paper                                                                                                                                                                                                                 | Venue        | Code                                                                                            |
| --------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ----------------------------------------------------------------------------------------------- |
| TARNet, Counterfactual Regression | [Estimating individual treatment effect: generalization bounds and algorithms](https://arxiv.org/pdf/1606.03976) — Shalit et al.                                                                                      | ICML 2017    | [Python](https://github.com/oddrose/cfrnet) ⭐ 25 \| 🐛 0 \| 🌐 Python \| 📅 2016-07-12          |
| BNN, BLR                          | [Learning representations for counterfactual inference](https://proceedings.mlr.press/v48/johansson16.pdf) — Johansson et al.                                                                                         | ICML 2016    | [Python](https://github.com/oddrose/cfrnet) ⭐ 25 \| 🐛 0 \| 🌐 Python \| 📅 2016-07-12          |
| Causal Effect VAE                 | [Causal effect inference with deep latent-variable models](https://papers.nips.cc/paper/7223-causal-effect-inference-with-deep-latent-variable-models.pdf) — Louizos et al.                                           | NeurIPS 2017 | [Python](https://github.com/AMLab-Amsterdam/CEVAE) ⚠️ Archived                                  |
| Dragonnet                         | [Adapting neural networks for the estimation of treatment effects](https://arxiv.org/abs/1906.02120) — Shi et al.                                                                                                     | NeurIPS 2019 | [Python](https://github.com/claudiashi57/dragonnet) ⭐ 299 \| 🐛 3 \| 🌐 Python \| 📅 2022-04-03 |
| SITE                              | [Representation Learning for Treatment Effect Estimation from Observational Data](https://papers.nips.cc/paper/7529-representation-learning-for-treatment-effect-estimation-from-observational-data.pdf) — Yao et al. | NeurIPS 2018 | [Python](https://github.com/Osier-Yi/SITE) ⭐ 59 \| 🐛 4 \| 🌐 Python \| 📅 2022-03-24           |
| GANITE                            | [GANITE: Estimation of Individualized Treatment Effects using Generative Adversarial Nets](https://openreview.net/forum?id=ByKWUeWA-) — Yoon et al.                                                                   | ICLR 2018    | [Python](https://github.com/jsyoon0823/GANITE) ⭐ 72 \| 🐛 0 \| 🌐 Python \| 📅 2020-04-25       |
| Perfect Match                     | [Perfect match: A simple method for learning representations for counterfactual inference with neural networks](https://arxiv.org/pdf/1810.00656) — Schwab et al.                                                     | arXiv 2018   | [Python](https://github.com/d909b/perfect_match) ⭐ 133 \| 🐛 1 \| 🌐 Python \| 📅 2023-03-24    |
| Intact-VAE                        | [Intact-VAE: Estimating treatment effects under unobserved confounding](https://openreview.net/forum?id=q7n2RngwOM) — Wu and Fukumizu                                                                                 | ICLR 2022    | NA                                                                                              |
| CausalEGM                         | [CausalEGM: a general causal inference framework by encoding generative modeling](https://arxiv.org/abs/2212.05925) — Liu et al.                                                                                      | arXiv 2022   | [Python](https://github.com/SUwonglab/CausalEGM) ⭐ 74 \| 🐛 1 \| 🌐 Python \| 📅 2024-06-01     |

##### Classic Methods

| Name | Paper | Venue | Code |
| ---- | ----- | ----- | ---- |

##### Tree based Methods

| Name                                                                 | Paper                                                                                                                                                                   | Venue      | Code                                                                                                                                                                         |
| -------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Causal Forest                                                        | [Estimation and inference of heterogeneous treatment effects using random forests](https://www.tandfonline.com/doi/pdf/10.1080/01621459.2017.1319839) — Wager and Athey | JASA 2017  | [R](https://github.com/grf-labs/grf) ⭐ 1,118 \| 🐛 69 \| 🌐 C++ \| 📅 2026-04-30, [Python](https://github.com/kjung/scikit-learn) ⭐ 21 \| 🐛 3 \| 🌐 Python \| 📅 2016-11-09 |
| Causal MARS, Causal Boosting, Pollinated Transformed Outcome Forests | [Some methods for heterogeneous treatment effect estimation in high-dimensions](https://arxiv.org/pdf/1707.00102.pdf) — Powers et al.                                   | arXiv 2017 | [R](https://github.com/grf-labs/grf) ⭐ 1,118 \| 🐛 69 \| 🌐 C++ \| 📅 2026-04-30, [R](https://github.com/saberpowers/causalLearning) ⭐ 25 \| 🐛 3 \| 🌐 R \| 📅 2022-03-14   |
| Bayesian Additive Regression Trees (BART)                            | [Bayesian nonparametric modeling for causal inference](https://www.tandfonline.com/doi/pdf/10.1198/jcgs.2010.08162) — Hill                                              | JCGS 2011  | [Python](https://github.com/JakeColtman/bartpy) ⭐ 232 \| 🐛 32 \| 🌐 Python \| 📅 2023-12-22                                                                                 |

##### Meta Learner

| Name      | Paper                                                                                                                                                                        | Venue           | Code                                                                                                                                                  |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| X-learner | [Metalearners for estimating heterogeneous treatment effects using machine learning](https://www.pnas.org/content/pnas/early/2019/02/14/1804597116.full.pdf) — Künzel et al. | PNAS 2019       | [R](https://github.com/soerenkuenzel/hte) ⭐ 35 \| 🐛 5 \| 📅 2022-06-18, [R](https://github.com/xnie/rlearner) ⭐ 127 \| 🐛 2 \| 🌐 R \| 📅 2021-04-10 |
| R-learner | [Quasi-oracle estimation of heterogeneous treatment effects](https://arxiv.org/abs/1712.04912) — Nie and Wager                                                               | Biometrika 2021 | [R](https://github.com/xnie/rlearner) ⭐ 127 \| 🐛 2 \| 🌐 R \| 📅 2021-04-10                                                                          |

#### Average Treatment Effect (including ATT and ATC)

| Name                                               | Paper                                                                                                                                                                                       | Venue                   | Code                                                                                                                           |
| -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Propensity Score Matching                          | [The central role of the propensity score in observational studies for causal effects](https://academic.oup.com/biomet/article-pdf/70/1/41/662954/70-1-41.pdf) — Rosenbaum and Rubin        | Biometrika 1983         | [Python](https://github.com/akelleh/causality/tree/master/causality/estimation) ⭐ 1,082 \| 🐛 13 \| 🌐 Python \| 📅 2025-03-11 |
| Inverse Probability Reweighting                    | [The central role of the propensity score in observational studies for causal effects](https://academic.oup.com/biomet/article-pdf/70/1/41/662954/70-1-41.pdf) — Rosenbaum and Rubin        | Biometrika 1983         | [R](https://github.com/cran/ipw) ⭐ 0 \| 🐛 1 \| 🌐 R \| 📅 2026-10-30                                                          |
| Doubly Robust Estimation                           | [Doubly robust estimation in missing data and causal inference models](https://onlinelibrary.wiley.com/doi/full/10.1111/j.1541-0420.2005.00377.x) — Bang and Robins                         | Biometrics 2005         | [R](https://github.com/gregridgeway/fastDR) ⭐ 7 \| 🐛 0 \| 🌐 R \| 📅 2026-05-15                                               |
| Doubly Robust Estimation for High Dimensional Data | [Doubly robust matching estimators for high dimensional confounding adjustment](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6347556/) — Antonelli et al.                                   | Biometrics 2016         | [R](https://github.com/jantonelli111/DoublyRobustHD) ⭐ 27 \| 🐛 0 \| 🌐 R \| 📅 2024-11-21                                     |
| TMLE                                               | [tmle: An R package for targeted maximum likelihood estimation](https://www.jstatsoft.org/article/view/v051i13) — Gruber and van der Laan                                                   | JSS 2011                | [R](https://cran.r-project.org/web/packages/tmle/index.html)                                                                   |
| Entropy Balancing                                  | [Entropy balancing for causal effects: A multivariate reweighting method to produce balanced samples in observational studies](https://www.jstor.org/stable/pdf/41403737.pdf) — Hainmueller | Political Analysis 2012 | [R](https://github.com/cran/ebal) ⭐ 2 \| 🐛 0 \| 🌐 R \| 📅 2026-04-29                                                         |
| CBPS(Covariate Balancing Propensity Score)         | [Covariate balancing propensity score](https://rss.onlinelibrary.wiley.com/doi/full/10.1111/rssb.12027) — Imai and Ratkovic                                                                 | JRSS-B 2014             | [R](https://github.com/kosukeimai/CBPS) ⭐ 30 \| 🐛 0 \| 🌐 R \| 📅 2026-09-27                                                  |
| Approximate Residual Balancing                     | [Approximate residual balancing: debiased inference of average treatment effects in high dimensions](https://rss.onlinelibrary.wiley.com/doi/pdf/10.1111/rssb.12268) — Athey et al.         | JRSS-B 2018             | [R](https://github.com/swager/balanceHD) ⭐ 35 \| 🐛 1 \| 🌐 R \| 📅 2021-07-29                                                 |
| Causal Bootstrapping                               | Causal bootstrapping — Little and Badawy                                                                                                                                                    | arXiv 2019              | [Matlab](https://www.maxlittle.net/software/cblib.zip)                                                                         |

#### Instrumental Variable (IV)

| Name     | Paper                                                                                                                                                                     | Venue     | Code                                                                                      |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------------------------------- |
| DeepIV   | [Deep iv: A flexible approach for counterfactual prediction](https://proceedings.mlr.press/v70/hartford17a/hartford17a.pdf) — Hartford et al.                             | ICML 2017 | [Python](https://github.com/jhartford/DeepIV) ⭐ 160 \| 🐛 6 \| 🌐 Python \| 📅 2021-06-17 |
| PDSLasso | [PDSLASSO: Stata module for post-selection and post-regularization OLS or IV estimation and inference](https://ideas.repec.org/c/boc/bocode/s458459.html) — Ahrens et al. | SSC 2018  | [STATA](https://statalasso.github.io/)                                                    |

#### Dose-Response Curve (Continuous Treatment)

| Name                                        | Paper                                                                                                                                          | Venue      | Code                                                                                               |
| ------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | -------------------------------------------------------------------------------------------------- |
| Causal Dose-Response Curves / Causal Curves | [causal-curve: A Python Causal Inference Package to Estimate Causal Dose-Response Curves](https://doi.org/10.21105/joss.02523) — Kobrosly      | JOSS 2020  | [Python](https://github.com/ronikobrosly/causal-curve) ⭐ 285 \| 🐛 4 \| 🌐 Python \| 📅 2026-01-05 |
| Dose response networks (DRNets)             | [Learning Counterfactual Representations for Estimating Individual Dose-Response Curves](https://arxiv.org/pdf/1902.00981.pdf) — Schwab et al. | arXiv 2019 | [Python](https://github.com/d909b/drnet) ⭐ 96 \| 🐛 3 \| 🌐 Python \| 📅 2023-03-24                |

#### Vectorized Treatments

| Name                                              | Paper                                                                                                      | Venue        | Code                                                                                    |
| ------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ------------ | --------------------------------------------------------------------------------------- |
| Causal Effect Inference for Structured Treatments | [Causal Effect Inference for Structured Treatments](https://arxiv.org/pdf/2106.01939.pdf) — Kaddour et al. | NeurIPS 2021 | [Python](https://github.com/JeanKaddour/SIN) ⭐ 42 \| 🐛 1 \| 🌐 Python \| 📅 2022-04-26 |

#### Multiple Causes

| Name         | Paper                                                                                | Venue      | Code                                                                                                             |
| ------------ | ------------------------------------------------------------------------------------ | ---------- | ---------------------------------------------------------------------------------------------------------------- |
| Deconfounder | [The blessings of multiple causes](https://arxiv.org/abs/1805.06826) — Wang and Blei | arXiv 2018 | [Python](https://github.com/blei-lab/deconfounder_tutorial) ⭐ 87 \| 🐛 2 \| 🌐 Jupyter Notebook \| 📅 2020-04-03 |

#### Multiple Outcomes

| Name                                | Paper                                                                                                                                                                                    | Venue | Code                                                      |
| ----------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- | --------------------------------------------------------- |
| Multiple Responses in Uplift Models | [Estimating and Visualizing Business Tradeoffs in Uplift Models](https://medium.com/building-ibotta/estimating-and-visualizing-business-tradeoffs-in-uplift-models-80ff845a5698) — Weiss | Blog  | [Python](https://github.com/Ibotta/mr_uplift) ⚠️ Archived |

#### Difference-in-Differences / Regression Discontinuity

| Name                                | Paper                                                                                                                                 | Venue                | Code                                                                                           |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | -------------------- | ---------------------------------------------------------------------------------------------- |
| Staggered Difference-in-Differences | [Difference-in-differences with multiple time periods](https://doi.org/10.1016/j.jeconom.2020.12.001) — Callaway and Sant'Anna        | J. Econometrics 2021 | [R](https://github.com/bcallaway11/did) ⭐ 424 \| 🐛 6 \| 🌐 R \| 📅 2026-10-30                 |
| Regression Discontinuity (rdrobust) | [Robust nonparametric confidence intervals for regression-discontinuity designs](https://doi.org/10.3982/ECTA11757) — Calonico et al. | Econometrica 2014    | [R/Python/Stata](https://github.com/rdpackages/rdrobust) ⭐ 99 \| 🐛 0 \| 🌐 R \| 📅 2026-10-30 |

#### Mediation Analysis

| Name      | Paper                                                                                             | Venue                      | Code                                                                                |
| --------- | ------------------------------------------------------------------------------------------------- | -------------------------- | ----------------------------------------------------------------------------------- |
| mediation | [A general approach to causal mediation analysis](https://doi.org/10.1037/a0020761) — Imai et al. | Psychological Methods 2010 | [R](https://github.com/kosukeimai/mediation) ⭐ 75 \| 🐛 52 \| 🌐 R \| 📅 2026-10-05 |

#### Sensitivity Analysis

| Name      | Paper                                                                                                                    | Venue       | Code                                                                                    |
| --------- | ------------------------------------------------------------------------------------------------------------------------ | ----------- | --------------------------------------------------------------------------------------- |
| sensemakr | [Making sense of sensitivity: extending omitted variable bias](https://doi.org/10.1111/rssb.12348) — Cinelli and Hazlett | JRSS-B 2020 | [R](https://github.com/carloscinelli/sensemakr) ⭐ 100 \| 🐛 10 \| 🌐 R \| 📅 2026-08-13 |

### Non-i.i.d Data

#### Panel Data / Time Series

| Name                                                | Paper                                                                                                                                                                                                                                                                    | Venue                    | Code                                                                                                                                                                                                |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Synthetic Control Method                            | [Using synthetic controls: Feasibility, data requirements, and methodological aspects](https://www.aeaweb.org/articles?id=10.1257/jel.20191450) — Abadie                                                                                                                 | JEL 2021                 | [R](https://cran.r-project.org/web/packages/Synth/Synth.pdf)                                                                                                                                        |
| Synthetic Difference in Differences                 | [Synthetic difference in differences](https://www.nber.org/system/files/working_papers/w25532/w25532.pdf) — Arkhangelsky et al.                                                                                                                                          | NBER 2019                | [R](https://github.com/synth-inference/synthdid) ⭐ 316 \| 🐛 60 \| 🌐 R \| 📅 2024-01-15<br>[Python](https://github.com/MasaAsami/pysynthdid) ⭐ 89 \| 🐛 10 \| 🌐 Jupyter Notebook \| 📅 2024-04-04 |
| Causal Impact                                       | [Inferring causal impact using Bayesian structural time-series models](https://projecteuclid.org/journals/annals-of-applied-statistics/volume-9/issue-1/Inferring-causal-impact-using-Bayesian-structural-time-series-models/10.1214/14-AOAS788.full) — Brodersen et al. | AoAS 2015                | [R](https://github.com/cran/bsts) ⭐ 34 \| 🐛 0 \| 🌐 R \| 📅 2025-09-05<br>[Python](https://github.com/WillianFuks/tfcausalimpact) ⭐ 679 \| 🐛 46 \| 🌐 Python \| 📅 2026-09-20                     |
| Time Series Deconfounder                            | [Time Series Deconfounder: Estimating Treatment Effects over Time in the Presence of Hidden Confounders](https://arxiv.org/pdf/1902.00450.pdf) — Bica et al.                                                                                                             | ICML 2020                | [Code](https://github.com/ioanabica/Time-Series-Deconfounder) ⭐ 52 \| 🐛 0 \| 🌐 Python \| 📅 2021-01-07                                                                                            |
| Recurrent Marginal Structural Networks              | [Forecasting Treatment Responses Over Time Using Recurrent Marginal Structural Networks](https://github.com/sjblim/rmsn_nips_2018) ⭐ 40 \| 🐛 2 \| 🌐 Python \| 📅 2018-12-11 — Lim                                                                                      | NeurIPS 2018             | [Python](https://github.com/sjblim/rmsn_nips_2018) ⭐ 40 \| 🐛 2 \| 🌐 Python \| 📅 2018-12-11                                                                                                       |
| Longitudinal Targeted Maximum Likelihood Estimation | [Targeted maximum likelihood estimation for dynamic and static longitudinal marginal structural working models](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4405134/) — Petersen et al.                                                                                 | J. Causal Inference 2014 | [R](https://github.com/joshuaschwab/ltmle) ⭐ 30 \| 🐛 11 \| 🌐 R \| 📅 2026-10-22                                                                                                                   |
| Causal Transformer                                  | [Causal Transformer for Estimating Counterfactual Outcomes](https://arxiv.org/abs/2204.07258) — Melnychuk et al.                                                                                                                                                         | arXiv 2022               | [Python](https://github.com/Valentyn1997/CausalTransformer) ⭐ 197 \| 🐛 2 \| 🌐 Python \| 📅 2024-08-13                                                                                             |

#### Network Data (with or without Interference)

| Name                                         | Paper                                                                                                                                         | Venue      | Code                                                                                                       |
| -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------------------------------------------------------------------------------------------------------- |
| Network Deconfounder                         | [Learning Individual Causal Effects from Networked Observational Data](https://arxiv.org/abs/1906.03485) — Guo et al.                         | WSDM 2020  | [Python](https://github.com/rguo12/network-deconfounder-wsdm20) ⭐ 78 \| 🐛 0 \| 🌐 Python \| 📅 2021-07-08 |
| Causal Inference with Network Embeddings     | [Using embeddings to correct for unobserved confounding](https://arxiv.org/pdf/1902.04114) — Veitch et al.                                    | arXiv 2019 | [Python](https://github.com/vveitch/causal-network-embeddings) ⭐ 56 \| 🐛 0 \| 🌐 Python \| 📅 2023-02-24  |
| Linked Causal Variational Autoencoder (LCVA) | [Linked Causal Variational Autoencoder for Inferring Paired Spillover Effects](https://www.public.asu.edu/~rguo12/CIKM18.pdf) — Rakesh et al. | CIKM 2018  | [Python](https://github.com/rguo12/CIKM18-LCVA) ⭐ 15 \| 🐛 2 \| 🌐 Python \| 📅 2023-01-15                 |
| Method-of-moments Estimators                 | [Causal Inference under Network Interference with Noise](https://arxiv.org/abs/2105.04518) — Li et al.                                        | arXiv 2021 | [Code](https://github.com/KolaczykResearch/CausInfNoisyNet) ⭐ 0 \| 🐛 0 \| 🌐 R \| 📅 2024-07-30           |

## Causal Machine Learning

### Surveys

| Name             | Paper                                                                                                    | Venue      | Code |
| ---------------- | -------------------------------------------------------------------------------------------------------- | ---------- | ---- |
| Causal ML Survey | [Causal Machine Learning: A Survey and Open Problems](https://arxiv.org/abs/2206.15475) — Kaddour et al. | arXiv 2022 | NA   |

### OoD Generalization

| Name       | Paper                                                                                                            | Venue      | Code                                                                                         |
| ---------- | ---------------------------------------------------------------------------------------------------------------- | ---------- | -------------------------------------------------------------------------------------------- |
| DomainBed  | In Search of Lost Domain Generalization — Gulrajani and Lopez-Paz                                                | ICLR 2020  | [Code](https://github.com/facebookresearch/DomainBed) ⚠️ Archived                            |
| WILDS      | Wilds: A benchmark of in-the-wild distribution shifts — Koh et al.                                               | ICML 2021  | [Code](https://github.com/p-lambda/wilds) ⭐ 605 \| 🐛 19 \| 🌐 Python \| 📅 2024-01-26       |
| IBM OoD    | Repository for theory and methods for Out-of-Distribution (OoD) generalization by IBM Research                   | NA         | [Code](https://github.com/IBM/OoD) ⚠️ Archived                                               |
| OoD Bench  | Ood-bench: Benchmarking and understanding out-of-distribution generalization datasets and algorithms — Ye et al. | arXiv 2021 | [Code](https://github.com/m-Just/OoD-Bench) ⭐ 45 \| 🐛 3 \| 🌐 Python \| 📅 2025-10-30       |
| BEDS-Bench | BEDS-Bench: Behavior of EHR-models under Distributional Shift--A Benchmark — Avati et al.                        | arXiv 2021 | [Code](https://github.com/Google-Health/records-research/tree/master/beds-bench) ⚠️ Archived |
| Survey THU | Towards out-of-distribution generalization: A survey — Shen et al.                                               | arXiv 2021 | NA                                                                                           |

#### Graph OoD Generalization

| Name       | Paper                                                                                                      | Venue        | Code                                                                               |
| ---------- | ---------------------------------------------------------------------------------------------------------- | ------------ | ---------------------------------------------------------------------------------- |
| CIGA       | Learning Causally Invariant Representations for Out-of-Distribution Generalization on Graphs — Chen et al. | NeurIPS 2022 | [Code](https://github.com/LFhase/CIGA) ⭐ 123 \| 🐛 1 \| 🌐 Python \| 📅 2023-08-28 |
| Survey THU | Out-of-distribution generalization on graphs: A survey — Li et al.                                         | arXiv 2022   | NA                                                                                 |

### Recommendation Systems

#### Inverse Propensity Scoring / Doubly Robust

| Name                                    | Paper                                                                                                                                           | Venue       | Code                                                                                                                              |
| --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | --------------------------------------------------------------------------------------------------------------------------------- |
| Top-K Off-policy Correction             | [Top-k off-policy correction for a REINFORCE recommender system](https://arxiv.org/abs/1812.02353) — Chen et al.                                | WSDM 2019   | [Python](https://github.com/awarebayes/RecNN) ⭐ 588 \| 🐛 1 \| 🌐 Python \| 📅 2020-12-08                                         |
| Unbiased Offline Recommender Learning   | [Unbiased Recommender Learning from Missing-Not-At-Random Implicit Feedback](https://dl.acm.org/doi/abs/10.1145/3336191.3371783) — Saito et al. | WSDM 2020   | [Python](https://github.com/usaito/unbiased-implicit-rec-real) ⭐ 30 \| 🐛 6 \| 🌐 Python \| 📅 2022-11-21                         |
| Unbiased Offline Recommender Evaluation | [Unbiased offline recommender evaluation for missing-not-at-random implicit feedback](https://dl.acm.org/citation.cfm?id=3240355) — Yang et al. | RecSys 2018 | [Python](https://github.com/ylongqi/unbiased-offline-recommender-evaluation) ⭐ 35 \| 🐛 2 \| 🌐 Jupyter Notebook \| 📅 2018-10-01 |
| IPS Estimator                           | [Recommendations as treatments: Debiasing learning and evaluation](https://proceedings.mlr.press/v48/schnabel16.pdf) — Schnabel et al.          | ICML 2016   | [Python](https://www.cs.cornell.edu/~schnabts/mnar/index.html)                                                                    |

#### Hidden Confounding

| Name                | Paper                                                                                                    | Venue       | Code                                                                                                   |
| ------------------- | -------------------------------------------------------------------------------------------------------- | ----------- | ------------------------------------------------------------------------------------------------------ |
| Deconfounded Recsys | [Causal Inference for Recommender Systems](https://dl.acm.org/doi/10.1145/3383313.3412225) — Wang et al. | RecSys 2020 | [Python](https://github.com/yixinwang/causal-recsys-public) ⭐ 47 \| 🐛 0 \| 🌐 Python \| 📅 2022-04-08 |

#### Domain Adaptation

| Name                                    | Paper                                                                                                                                                                                         | Venue       | Code                                                                                                 |
| --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | ---------------------------------------------------------------------------------------------------- |
| Causal Embedding for Recommendation     | [Causal embeddings for recommendation](https://arxiv.org/pdf/1706.07639) — Bonner and Vasile                                                                                                  | RecSys 2018 | [Python](https://github.com/criteo-research/CausE) ⭐ 249 \| 🐛 4 \| 🌐 Python \| 📅 2018-10-24       |
| Domain Adversarial Matrix Factorization | [Towards Resolving Propensity Contradiction in Offline Recommender Learning](https://github.com/usaito/ijcai2022-adversarial-mf) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2022-04-21 — Saito and Nomura | IJCAI 2022  | [Code](https://github.com/usaito/ijcai2022-adversarial-mf) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2022-04-21 |

#### Disentanglement

| Name                                              | Paper                                                                                                                                  | Venue    | Code                                                                                           |
| ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- | -------- | ---------------------------------------------------------------------------------------------- |
| Causal Embedding for User Interest and Conformity | [Disentangling User Interest and Conformity for Recommendation with Causal Embedding](https://arxiv.org/abs/2006.11011) — Zheng et al. | WWW 2021 | [Python](https://github.com/tsinghua-fib-lab/DICE) ⭐ 158 \| 🐛 0 \| 🌐 Python \| 📅 2024-06-04 |

### Learning to Rank

| Name                                      | Paper                                                                                                                       | Venue      | Code                                                                                                                                            |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Policy-aware Estimator                    | [Policy-aware unbiased learning to rank for top-k rankings](https://arxiv.org/pdf/2005.09035.pdf) — Oosterhuis and de Rijke | SIGIR 2020 | [Python](https://github.com/HarrieO/2020topkunbiasedltr) ⭐ 5 \| 🐛 0 \| 🌐 Python \| 📅 2021-04-09                                              |
| Heckman^{rank}                            | [Correcting for Selection Bias in Learning-to-rank Systems](https://arxiv.org/abs/2001.11358) — Ovaisi et al.               | arXiv 2020 | [Code](https://github.com/edgeslab/heckman_rank) ⭐ 1 \| 🐛 1 \| 🌐 C \| 📅 2020-04-20                                                           |
| Unbiased LambdaMart                       | [Unbiased LambdaMART: An Unbiased Pairwise Learning-to-Rank Algorithm](https://acbull.github.io/pdf/unbias.pdf) — Hu et al. | WWW 2019   | [Code](https://github.com/acbull/Unbiased_LambdaMart) ⭐ 225 \| 🐛 6 \| 🌐 C++ \| 📅 2019-10-30                                                  |
| IPW\_rank and the Dual Learning Algorithm | [Unbiased Learning to Rank with Unbiased Propensity Estimation](https://arxiv.org/abs/1804.05938) — Ai et al.               | SIGIR 2018 | [Python](https://github.com/QingyaoAi/Unbiased-Learning-to-Rank-with-Unbiased-Propensity-Estimation) ⭐ 88 \| 🐛 4 \| 🌐 Python \| 📅 2023-02-01 |
| Propensity SVM-rank                       | [Unbiased learning-to-rank with biased feedback](https://dl.acm.org/ft_gateway.cfm?id=3018699\&type=pdf) — Joachims et al.  | WSDM 2017  | [Python](https://www.cs.cornell.edu/people/tj/svm_light/svm_proprank.html)                                                                      |

### Off-line Policy Evaluation/Optimization (for Contextual Bandit or RL)

| Name                                    | Paper                                                                                                                                                                                   | Venue        | Code                                                                                                      |
| --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------------------------------------------------------------------------------------------------- |
| Optimal Kernel Balancing                | [Policy Evaluation with Latent Confounders via Optimal Balance](https://arxiv.org/abs/1908.01920) — Bennett and Kallus                                                                  | arXiv 2019   | [Python](https://github.com/CausalML/LatentConfounderBalancing) ⭐ 3 \| 🐛 1 \| 🌐 Python \| 📅 2019-10-25 |
| BanditNet                               | [Deep learning with logged bandit feedback](https://openreview.net/pdf?id=SJaP_-xAb) — Joachims et al.                                                                                  | ICLR 2018    | [Python](https://www.cs.cornell.edu/people/tj/banditnet/index.html)                                       |
| Counterfactual Risk Minimization (POEM) | [Counterfactual risk minimization: Learning from logged bandit feedback](https://proceedings.mlr.press/v37/swaminathan15.pdf) — Swaminathan and Joachims                                | ICML 2015    | [Python](https://www.cs.cornell.edu/~adith/POEM/index.html)                                               |
| Self Normalized Estimator               | [The self-normalized estimator for counterfactual learning](https://papers.nips.cc/paper/5748-the-self-normalized-estimator-for-counterfactual-learning.pdf) — Swaminathan and Joachims | NeurIPS 2015 | [Python](https://www.cs.cornell.edu/~adith/POEM/index.html)                                               |
| Open Bandit Pipeline                    | [Open Bandit Dataset and Pipeline: Towards Realistic and Reproducible Off-Policy Evaluation](https://arxiv.org/abs/2008.07146) — Saito et al.                                           | NeurIPS 2021 | [Python](https://github.com/st-tech/zr-obp) ⭐ 714 \| 🐛 34 \| 🌐 Python \| 📅 2024-06-03                  |

### Natural Language Processing

| Name                                                               | Paper                                                                                                                                                          | Venue      | Code                                                                                                            |
| ------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------------------------------------------------------------------------------------------------------- |
| A Review of Using Text to Remove Confounding from Causal Estimates | [Text and Causal Inference: A Review of Using Text to Remove Confounding from Causal Estimates](https://aclanthology.org/2020.acl-main.474.pdf) — Keith et al. | ACL 2020   | NA                                                                                                              |
| Causal Analysis with Lexicons                                      | [Deconfounded lexicon induction for interpretable social science](https://aclanthology.org/N18-1146.pdf) — Pryzant et al.                                      | NAACL 2018 | [Python](https://github.com/rpryzant/deconfounded-lexicon-induction) ⭐ 60 \| 🐛 2 \| 🌐 Python \| 📅 2024-07-25 |
| Causal Text Embeddings                                             | [Using Text Embeddings for Causal Inference](https://arxiv.org/pdf/1905.12741.pdf) — Veitch et al.                                                             | arXiv 2019 | [Python](https://github.com/blei-lab/causal-text-embeddings) ⭐ 125 \| 🐛 3 \| 🌐 Python \| 📅 2020-09-23        |
| Handling Missing/Noisy Treatment                                   | [Challenges of Using Text Classifiers for Causal Inference](https://aclanthology.org/D18-1488/) — Wood-Doughty et al.                                          | EMNLP 2018 | [Python](https://github.com/zachwooddoughty/emnlp2018-causal) ⭐ 23 \| 🐛 0 \| 🌐 Python \| 📅 2020-09-23        |
| Causal Inferences Using Texts                                      | [How to make causal inferences using texts](https://arxiv.org/pdf/1802.02163.pdf) — Egami et al.                                                               | arXiv 2018 | NA                                                                                                              |

### Counterfactual Explanations

| Paper                                                                                                                                                                                                  | Venue              | Code                                                                        |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------ | --------------------------------------------------------------------------- |
| [Explaining machine learning classifiers through diverse counterfactual explanations](https://arxiv.org/pdf/1905.07697.pdf) — Mothilal et al.                                                          | arXiv 2019         | [Python](https://github.com/microsoft/DiCE) ⭐ 4 \| 🐛 4 \| 📅 2025-09-12    |
| [Efficient search for diverse coherent explanations](https://dl.acm.org/doi/pdf/10.1145/3287560.3287569) — Russell                                                                                     | FAccT 2019         | [Python](https://bitbucket.org/ChrisRussell/diverse-coherent-explanations/) |
| [Counterfactual explanations without opening the black box: Automated decisions and the GDPR](https://heinonline.org/hol-cgi-bin/get_pdf.cgi?handle=hein.journals/hjlt31\&section=29) — Wachter et al. | Harvard JL\&T 2017 |                                                                             |

### Counterfactual Fairness

| Paper                                                                                                                                                                            | Venue        | Code                                                                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Counterfactual fairness](https://papers.nips.cc/paper/6995-counterfactual-fairness.pdf) — Kusner et al.                                                                         | NeurIPS 2017 | [Python](https://github.com/mkusner/counterfactual-fairness) ⭐ 56 \| 🐛 2 \| 🌐 R \| 📅 2018-07-18                                                          |
| [Pc-fairness: A unified framework for measuring causality-based fairness](https://proceedings.neurips.cc/paper/2019/file/44a2e0804995faf8d2e3b084a1e2db1d-Paper.pdf) — Wu et al. | NeurIPS 2019 | [Code](https://github.com/yongkaiwu/Path-specific-Counterfactual-Fairness) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2020-09-17                                        |
| [Path-specific counterfactual fairness](https://www.aaai.org/ojs/index.php/AAAI/article/download/4777/4655) — Chiappa                                                            | AAAI 2019    | [Code](https://github.com/google-deepmind/deepmind-research/tree/master/counterfactual_fairness) ⭐ 15,261 \| 🐛 358 \| 🌐 Jupyter Notebook \| 📅 2026-06-17 |
| [Counterfactual fairness in text classification through robustness](https://dl.acm.org/doi/pdf/10.1145/3306618.3317950) — Garg et al.                                            | AIES 2019    | [Code](https://github.com/SaiSakethAluru/Counterfactual-fairness) ⭐ 2 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2020-07-12                                       |

### Reinforcement Learning

| Name                                         | Paper                                                                                                                                      | Venue                    | Code                                                                                 |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------ | ------------------------------------------------------------------------------------ |
| Deconfounded RL                              | [Deconfounding reinforcement learning in observational settings](https://arxiv.org/pdf/1812.10576) — Lu et al.                             | arXiv 2018               | [Python](https://github.com/CausalRL/DRL) ⭐ 52 \| 🐛 2 \| 🌐 Python \| 📅 2019-04-13 |
| Structural Nested Models / G-estimation      | [Structural nested models and G-estimation: the partially realized promise](https://arxiv.org/pdf/1503.01589.pdf) — Vansteelandt and Joffe | Statistical Science 2014 | NA                                                                                   |
| Counterfactual-Guided Policy Search (CF-GPS) | Woulda, Coulda, Shoulda: Counterfactually-Guided Policy Search — Buesing et al.                                                            | arXiv 2018               | NA                                                                                   |

### Multi-Armed Bandit/Causal Bandit

| Name              | Paper                                                                                                                                             | Venue        | Code |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ---- |
| Causal Bandits    | [Causal bandits: Learning good interventions via causal inference](https://arxiv.org/abs/1606.03203) — Lattimore et al.                           | NeurIPS 2016 | NA   |
| Offline+MAB       | [Combining Offline Causal Inference and Online Bandit Learning for Data Driven Decisions](https://arxiv.org/pdf/2001.05699v1.pdf) — Ye et al.     | arXiv 2020   | NA   |
| B-kl-UCB, B-TS    | [Transfer learning in multi-armed bandit: a causal approach](https://www.ifaamas.org/Proceedings/aamas2017/pdfs/p1778.pdf) — Zhang and Bareinboim | AAMAS 2017   | NA   |
| Incremental Model | [Contextual Multi-Armed Bandits for Causal Marketing](https://arxiv.org/pdf/1810.01859) — Sawant et al.                                           | arXiv 2018   | NA   |

### Large Language Models

| Name      | Paper                                                                                                                                 | Venue      | Code                                                                                       |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------------------------------------------ |
| PyWhy-LLM | [Causal reasoning and large language models: Opening a new frontier for causality](https://arxiv.org/abs/2305.00050) — Kıcıman et al. | arXiv 2023 | [Python](https://github.com/py-why/pywhy-llm) ⭐ 316 \| 🐛 15 \| 🌐 Python \| 📅 2026-09-03 |

## Causal Discovery

### for i.i.d. Data

#### Classic Methods

| Name          | Paper                                              | Venue     | Code                                                                                                                                                                                                                                                                    |
| ------------- | -------------------------------------------------- | --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| IC algorithm  | A theory of inferred causation — Pearl and Verma   | KR 1991   | [Python](https://github.com/akelleh/causality) ⭐ 1,082 \| 🐛 13 \| 🌐 Python \| 📅 2025-03-11                                                                                                                                                                           |
| PC algorithm  | Causation, Prediction, and Search — Spirtes et al. | Book 2000 | [Python](https://github.com/keiichishima/pcalg) ⭐ 97 \| 🐛 4 \| 🌐 Python \| 📅 2022-04-18 [R](https://github.com/cran/pcalg) ⭐ 35 \| 🐛 4 \| 🌐 R \| 📅 2024-09-13 [Julia](https://github.com/mschauer/CausalInference.jl) ⭐ 213 \| 🐛 19 \| 🌐 Julia \| 📅 2026-08-14 |
| FCI algorithm | Causation, Prediction, and Search — Spirtes et al. | Book 2000 | [R](https://github.com/cran/pcalg) ⭐ 35 \| 🐛 4 \| 🌐 R \| 📅 2024-09-13 [Julia](https://github.com/mschauer/CausalInference.jl) ⭐ 213 \| 🐛 19 \| 🌐 Julia \| 📅 2026-08-14                                                                                            |

#### Continuous Optimization

| Paper                                                                                                                                                                                    | Venue        | Code                                                                                         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | -------------------------------------------------------------------------------------------- |
| [DAGs with NO TEARS: Continuous optimization for structure learning](https://papers.nips.cc/paper/8157-dags-with-no-tears-continuous-optimization-for-structure-learning) — Zheng et al. | NeurIPS 2018 | [Code](https://github.com/xunzheng/notears) ⭐ 693 \| 🐛 8 \| 🌐 Python \| 📅 2026-05-26      |
| [DAG-GNN: DAG Structure Learning with Graph Neural Networks](https://arxiv.org/abs/1904.10098) — Yu et al.                                                                               | ICML 2019    | [Code](https://github.com/fishmoon1234/DAG-GNN) ⭐ 330 \| 🐛 24 \| 🌐 Python \| 📅 2021-12-20 |
| [Learning Sparse Nonparametric DAGs](https://proceedings.mlr.press/v108/zheng20a/zheng20a.pdf) — Zheng et al.                                                                            | AISTATS 2020 | [Code](https://github.com/xunzheng/notears) ⭐ 693 \| 🐛 8 \| 🌐 Python \| 📅 2026-05-26      |
| [Amortized Inference for Causal Structure Learning](https://proceedings.neurips.cc/paper_files/paper/2022/file/54f7125dee9b8b3dc798bb9a082b09e2-Paper-Conference.pdf) — Lorch et al.     | NeurIPS 2022 | [Code](https://github.com/larslorch/avici) ⭐ 83 \| 🐛 0 \| 🌐 Python \| 📅 2025-02-11        |
| [DAGMA: Learning DAGs via M-matrices and a Log-Determinant Acyclicity Characterization](https://arxiv.org/abs/2209.08037) — Bello et al.                                                 | NeurIPS 2022 | [Code](https://github.com/kevinsbello/dagma) ⭐ 146 \| 🐛 1 \| 🌐 Python \| 📅 2024-01-14     |
| [Deep End-to-end Causal Inference (DECI)](https://arxiv.org/abs/2202.02195) — Geffner et al.                                                                                             | arXiv 2022   | [Code](https://github.com/microsoft/causica) ⭐ 537 \| 🐛 89 \| 🌐 Python \| 📅 2026-10-30    |

#### Learning IV

| Name        | Paper                                                                                                                                                         | Venue     | Code                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------- |
| Learning IV | [Learning instrumental variables with structural and non-gaussianity assumptions](https://www.jmlr.org/papers/volume18/17-014/17-014.pdf) — Silva and Shimizu | JMLR 2017 | [Code](https://www.homepages.ucl.ac.uk/~ucgtrbd/code/iv_discovery/) |

#### Distinguishing Cause from Effect (Bivariate)

| Name     | Paper                                                                                                                                                                           | Venue         | Code                                                                                                         |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------------------------------------------------------------------------------------------------------------ |
| BMLiNGAM | Bayesian estimation of causal direction in acyclic structural equation models with individual-specific confounder variables and non-Gaussian distributions — Shimizu and Bollen | JMLR 2014     | [Python](https://github.com/taku-y/bmlingam) ⭐ 16 \| 🐛 4 \| 🌐 Python \| 📅 2017-02-16                      |
| Sloppy   | Identifiability of Cause and Effect using Regularized Regression — Marx and Vreeken                                                                                             | KDD 2019      | [R](https://eda.rg.cispa.io/)                                                                                |
| RECI     | Cause-effect inference by comparing regression errors — Blöbaum et al.                                                                                                          | AISTATS 2018  | in [CausalDiscoveryToolbox](https://github.com/diviyank/CausalDiscoveryToolbox) ⭐ 9 \| 🐛 0 \| 📅 2020-02-04 |
| bQCD     | Distinguishing cause from effect using quantiles: Bivariate quantile causal discovery — Tagasovska et al.                                                                       | ICML 2020     | [Code](https://github.com/tagas/bQCD) ⭐ 5 \| 🐛 0 \| 🌐 R \| 📅 2020-06-29                                   |
| CGNN     | Learning functional causal models with generative neural networks — Goudet et al.                                                                                               | Springer 2018 | [Code](https://github.com/GoudetOlivier/CGNN) ⭐ 100 \| 🐛 2 \| 🌐 Python \| 📅 2019-07-03                    |

#### Conditional Independence Tests (for Constraint-based Algorithms)

| Name | Paper                                                                                                                                                | Venue                    | Code                                                                          |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ | ----------------------------------------------------------------------------- |
| RCIT | [Approximate kernel-based conditional independence tests for fast non-parametric causal discovery](https://arxiv.org/abs/1702.03877) — Strobl et al. | J. Causal Inference 2019 | [R](https://github.com/ericstrobl/RCIT) ⭐ 32 \| 🐛 3 \| 🌐 R \| 📅 2019-05-23 |

#### Causal Discovery with Probabilistic Logic Programming

| Name       | Paper                                                              | Venue      | Code                                        |
| ---------- | ------------------------------------------------------------------ | ---------- | ------------------------------------------- |
| Causal PSL | Scalable Probabilistic Causal Structure Discovery — Sridhar et al. | IJCAI 2018 | [Java](https://bitbucket.org/linqs/causpsl) |

#### Scalable Ensemble Causal Discovery

| Name                                                   | Paper                                                                                                               | Venue     | Code                                                                                                                  |
| ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------- | --------- | --------------------------------------------------------------------------------------------------------------------- |
| Scalable and Hybrid Ensemble-Based Causality Discovery | [Scalable and Hybrid Ensemble-Based Causality Discovery](https://ieeexplore.ieee.org/document/9288491) — Guo et al. | SMDS 2020 | [Python](https://github.com/big-data-lab-umbc/ensemble_causality_learning) ⭐ 10 \| 🐛 0 \| 🌐 Python \| 📅 2020-07-27 |

### with Temporal Data

| Name                                      | Paper                                                                                                                                          | Venue                 | Code                                                                                                       |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- | ---------------------------------------------------------------------------------------------------------- |
| TCDF: Temporal Causal Discovery Framework | [Causal discovery with attention-based convolutional neural networks](https://www.mdpi.com/2504-4990/1/1/19) — Nauta et al.                    | MAKE 2019             | [Pytorch](https://github.com/M-Nauta/TCDF) ⭐ 541 \| 🐛 2 \| 🌐 Jupyter Notebook \| 📅 2021-10-01           |
| PCMCI                                     | [Detecting and quantifying causal associations in large nonlinear time series datasets](https://doi.org/10.1126/sciadv.aau4996) — Runge et al. | Science Advances 2019 | [Python](https://github.com/jakobrunge/tigramite) ⭐ 1,733 \| 🐛 20 \| 🌐 Jupyter Notebook \| 📅 2026-01-14 |

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-31._
