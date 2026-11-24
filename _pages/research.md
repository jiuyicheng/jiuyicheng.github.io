---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

---

## Working Paper

&ensp; [1] **Jiuyi Cheng**, [Alexis Akira Toda](https://alexisakira.github.io/). (2026). Does Calibration Pick the Right Model? Likelihood Evidence from Income Risk. [arXiv:2611.02029](https://arxiv.org/abs/2611.02029).
[[Draft](./draft/likelihood_calibration.pdf)] [[Slides](./draft/likelihood_calibration_slides.pdf)]

<details>
  <summary>Abstract</summary>

Quantitative macroeconomics typically disciplines models by matching selected moments. We show how finite-state hidden Markov approximations make likelihood estimation and model selection feasible for nonlinear, non-Gaussian latent processes on short panels, without simulation. We illustrate the method with PSID earnings data. The calibrations that best match moments of earnings dynamics fit complete histories worse than a likelihood-estimated process with a Gaussian persistent component. In a standard saving model, calibrations of one process that fit the targets about equally well imply mean assets that differ by a factor of three. Close agreement with selected moments can leave economic predictions largely undetermined.
</details>

&ensp; [2] **Jiuyi Cheng**. (2023). Principal-Agent Problem: Incentive Contract of Public-Private Partnership (PPP) Construction under Adverse Selection. [*Young Scholar Academic Journal*](https://user.yuanpeiyoungscholars.com/pdf/YoungScholarsAcademicJournal_final4), *4*, 80–108. [[Draft](./draft/incentive_contract.pdf)]

<details>
  <summary>Abstract</summary>

This study presents an economic-profit-based cost-sharing contract mechanism under asymmetric information to eliminate the agent's opportunistic behavior and reduce the principal's information rent in public-private partnership (PPP) projects. According to principal-agent theory (PAT), the government's set of contract options screens the ability of the private contractor, minimizing wasted effort and maximizing welfare in the economy. This paper analyzes the effort level, transfer payment, and cost-sharing ratio in response to the objectives of the government and the enterprise, specifically in terms of benefits and costs. The conclusions of this research may serve as a theoretical foundation and provide practical guidance for designing incentive mechanisms and making decisions in PPP build-operate-transfer construction projects.
</details>

---

## Work in Progress

&ensp; [3] **Jiuyi Cheng**. (2026). Orthogonal and Doubly Robust Estimation of Incremental Causal Effects Using Negative Control. Honors Thesis. *ACIC Under Review*.

<details>
  <summary>Abstract</summary>

Unmeasured selection biases continuous-treatment effects after covariate adjustment. Negative-control rank transport identifies distributions but lacks nuisance-robust policy estimation, and standard doubly robust scores leave latent selection untreated. We extend Sofer et al. (2016) to fixed dose-shift policies: a reference quantile map converts a continuous negative control in different units to the outcome scale, and under a dose-invariant location model, subtraction yields a regression whose shift contrast is causal. A Riesz-representer residual correction gives a cross-fitted estimator consistent if either the adjusted regression or representer is correct, conditional on valid exclusion, rank equiconfounding, calibration, and dose support, while direct Riesz learning avoids treatment-density estimation.
</details>

&emsp; *Co-advisors*: [Florian Gunsilius](https://www.floriangunsilius.com/), [Pedro H.C. Sant'Anna](https://psantanna.com/). 

&emsp; *Committee Members*: [Alexis Akira Toda](https://alexisakira.github.io/), [Ruoxuan Xiong](https://www.ruoxuanxiong.com/), [Esfandiar (Essie) Maasoumi](https://sites.google.com/view/esfandiarmaasoumi).

&ensp; [4] **Jiuyi Cheng**, [Ruoxuan Xiong](https://www.ruoxuanxiong.com/). (2026). Federated R-Learner with Mixture-of-Experts for Heterogeneous Treatment Effects. *ACIC Under Review*. [[Draft](./draft/federated_learner.pdf)] [[GitHub](https://github.com/jiuyicheng/federated-hte)]

<details>
  <summary>Abstract</summary>

When an institution has few records, learning which individuals benefit from treatment is difficult, and other institutions can help only if their treatment effects do not differ too much. We estimate the conditional average treatment effect (CATE) at a prespecified target site when patient records cannot be pooled. Each site cross-fits outcome and propensity models and forms R-learning residuals; federated parameter averaging then learns a shared mixture-of-experts feature map, while a target-specific ridge head partially pools with a global head. Independent target validation R-risk selects this adapted Fed-MoE or a target-only causal forest, and we prove the R-risk identity, bound selection error, and derive when partial pooling improves a fixed-feature head. Across 30 replications in each of four known-truth settings, the selected method lowered target-test CATE MSE by 7%–26%. MIMIC-IV-covariate results favored a pooled causal forest, and a four-hospital eICU analysis showed comparable held-out R-risk without observed CATE truth.
</details>

<!-- [GitHub] [Proposal] [Draft] -->

&ensp; [5] **Jiuyi Cheng**, [Alexis Akira Toda](https://alexisakira.github.io/). (2026). Solving Nonlinear Functional Equations Using High-Dimensional Adaptive Grids.

<!-- [GitHub] [Draft] -->

&ensp; [6] **Jiuyi Cheng**. (2026). Identification and Estimation of Non-Compensatory Preferences in Adaptive Conjoint Experiments. Supervised by Prof. [Stephen O'Connell](https://www.stephenoconnell.org). 

<!-- [GitHub] [Draft] -->

---

## Presentations

&ensp; [7] (Scheduled) **Jiuyi Cheng**. Multi-Estimator Synthetic Control for Policy Evaluation: Oregon SB 608 and Rent Growth. *National Conference on Undergraduate Research (NCUR)*. Grand Rapids, MI, 2027. [Poster]

&ensp; [8] **Jiuyi Cheng**. Trust Under Threat: Statistical Screening with Betrayal-Averse Receivers. *Gulf Coast Undergraduate Research Symposium (GCURS)–Computational Applied Math & Operations Research*, Rice University. Houston, TX, 2026. [[Slides](./poster/trust_screening.pdf)]

&ensp; [9] **Jiuyi Cheng**. Adaptive Conjoint Analysis on Threshold Effects in Refugee Return Intentions: Methodology & Experimental Design. *Economics Scholars Program (ESP), Federal Reserve of Cleveland*, 2026. [[Slides](./poster/conjoint.pdf)] [[Proposal](./poster/esp_proposal.pdf)]

&emsp; This research is also presented at *Emory Undergraduate Research Symposium*, Emory University, Atlanta, GA, 2026. 

&ensp; [10] **Jiuyi Cheng**. Volatility Spillover Across U.S. Production Networks: GJR‑GARCH with BEA Input‑Output Linkages. *National Conference on Undergraduate Research (NCUR)*. Richmond, VA, 2026. [[Poster](./poster/network_vol.pdf)] 

&ensp; [11] **Jiuyi Cheng**. Student Trilemma: Contract Theory Model for Optimal Time Allocation of Academic, Leisure, and Sleep. *Georgia Undergraduate Research Conference (GURC)*. Oxford, GA, 2025. [[Poster](./poster/trilemma.pdf)]

&ensp; [12] **Jiuyi Cheng**, Daniel Nickas, Riyan Shah, Will Liu. Algorithm-based LIHTC Site Optimization for Georgia's Qualified Allocation Plan on Housing Equity. *AI.Xperience Summer Research Showcase*, Emory University. Atlanta, GA, 2025. [[Poster](./poster/lihtc.pdf)]

---

## Research Assistant

- Network Formation and Interference via Density and Sparsity Assumptions.  Supervised by Prof. [Abhishek Ananth](https://abhiananthecon.github.io/). 

<!-- [GitHub] [Draft] -->

- Web-Scraping Pipeline for Demographic Identity of Economics Faculties. Supervised by Prof. [Alexis Akira Toda](https://alexisakira.github.io/). 

<!-- [GitHub] -->

---

## Editorials

- **Jiuyi Cheng.** (2026). Algorithmic Invisible Hand Beyond Bertrand: Evidence in Ride-hailing Markets. [*Emory Economic Review*](https://static1.squarespace.com/static/5bc683ebe8ba4466f592674d/t/69e98ab8d49cfe289d29b7ed/1776913086542/EER+Print+Publication+2026.pdf), *7*(1), 17-20. 

<!-- [Draft] --->

- **Jiuyi Cheng.** (2025). Causal Identification vs. Epistemic Justification: Counterfactuals and the Philosophy of Causal Inference. [*Suddenly Press*](https://static1.squarespace.com/static/67be0e03ecdaec3ee0657b9d/t/6968162c6560883cf75299e0/1768429100223/Suddenly+Issue+2.0.pdf), *2*, 10-16. 

<!-- [Draft] --->

---

## Directed Readings & Course Projects

- **Double/Debiased Machine Learning** (Fall 2026). Matrix Analysis. 
- **High-Dimensional Probability** (Fall 2026). Department of Mathematics. 
- **Low-Rank Matrix Factorization (LRMF)** (Spring 2026). Non-linear Optimization. [[GitHub](https://github.com/niccChen/math347)] [[Slides](./drp/lrmf_slide.pdf)] [[Report](./drp/lrmf_report.pdf)]
- **Tax Policy Over Business Cycle**, Paper replication (Spring 2026). [[Draft](./drp/paper_rep.pdf)]
- **Equilibrium in the Tradable Permits Market** (Spring 2025). Department of Economics. Supervised by Prof. Samiran (Shomu) Banerjee. [[Notes](./drp/permits.pdf)]
- **German Hartz vs. French Macron Labor Market Reforms** (Spring 2024). Department of Economics. Supervised by Prof. Teresa F. Romano. [[Annotated Bib](./drp/lm_reform.pdf)]
