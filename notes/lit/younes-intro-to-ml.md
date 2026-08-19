---
type: lit
status: reading
tags: [lit, machine-learning]
---
# Younes — Introduction to Machine Learning

pdf:: [[IntroToMLYounes.pdf]]
author:: Laurent Younes
version:: May 15, 2025 (JHU Applied Math & Statistics lecture notes)
started:: 2026-08-19

> [!warning] Page offset
> Section numbers below are the book's **printed** pages. Obsidian's
> `[[IntroToMLYounes.pdf#page=N]]` uses the **PDF** page index. Check the
> offset once (open to printed p.15, note the PDF page), record it here,
> then apply it in every `source::` link.
>
> offset:: ?

## Notation
<!-- Fill in as collisions with prior coursework appear. This table is why
     notes written from this book will still make sense next year. -->

| Symbol | Younes uses it for | I learned it as |
| ------ | ------------------ | --------------- |
|        |                    |                 |

## Scope note
Author's own framing: mathematical/statistical bias, assumes linear algebra,
matrix analysis, multivariate calculus, probability and statistics. Measure
theory is used sparingly and localized. So the prerequisite load is real but
bounded — expect ch. 1 to name most of what it assumes.

---

## Chapters

Legend: `[ ]` unread · `[/]` read, atoms not extracted · `[x]` extracted
`⟲` = leans on prior coursework, candidate for a prerequisite-review pass

- [ ] **1 — General Notation and Background Material** · p.15 ⟲
      Linear algebra, topology (open/closed/compact, metric spaces), calculus
      (differentials, Taylor), probability incl. measure-theoretic conditioning.
      *This is the book's own prerequisite list. Read it as an audit of what to
      review, not as material to atomize.*
- [ ] **2 — A Few Results in Matrix Analysis** · p.31
      Trace inequality, matrix norms, low-rank approximation.
- [ ] **3 — Introduction to Optimization** · p.43
      Convexity, relative interior, descent directions, convergence, line search,
      SGD + ADAM, Lagrange multipliers, subgradients, proximal methods, duality/KKT,
      ADMM. *Largest single dependency in the book; most atoms per page.*
- [ ] **4 — Introduction: Bias and Variance** · p.105
      Sieves, kernel density estimation.
- [ ] **5 — Prediction: Basic Concepts** · p.115
      Bayes predictor, ERM, generalization error, cross-validation.
- [ ] **6 — Inner Products and Reproducing Kernels** · p.129
- [ ] **7 — Linear Regression** · p.145
      Least squares, Gauss–Markov, ridge, Lasso, LARS, Dantzig, SVM regression.
- [ ] **8 — Models for Linear Classification** · p.175
      Logistic regression, LDA, Fisher, optimal scoring, separating hyperplanes/SVM.
- [ ] **9 — Nearest-Neighbor Methods** · p.209
- [ ] **10 — Tree-based Algorithms** · p.221
      Recursive partitioning, random forests, Adaboost, gradient boosting.
- [ ] **11 — Neural Nets** · p.245
      Backprop as a differential, dropout, neural ODEs.
- [ ] **12 — Comparing Probability Distributions** · p.263
      Total variation, divergences, Monge–Kantorovich, dual distances.
- [ ] **13 — Monte-Carlo Sampling** · p.273
      Rejection, Markov chain sampling + convergence, Gibbs, Metropolis–Hastings,
      perfect sampling, Markovian stochastic approximation.
- [ ] **14 — Markov Random Fields** · p.313 ⟲
      Conditional independence, undirected models, Hammersley–Clifford.
- [ ] **15 — Probabilistic Inference for MRF** · p.349 ⟲
      Belief propagation, sum-prod/max-prod, factor graphs, junction trees,
      triangulated graphs, maximal cliques.
- [ ] **16 — Bayesian Networks** · p.391
      Moral graph, d-separation, Markov equivalence, interventions, SEMs.
- [ ] **17 — Latent Variables and Variational Methods** · p.411
      Variational principle, mean-field, EM, mixtures of Gaussians.
- [ ] **18 — Learning Graphical Models** · p.429
      Conjugate priors, structure scoring, max-entropy, iterative scaling,
      pseudolikelihood, score matching.
- [ ] **19 — Deep Generative Methods** · p.453
      Normalizing flows, VAEs, GANs/Wasserstein GANs, reversed Markov chains.
- [ ] **20 — Clustering** · p.473
      Hierarchical, K-medoids/K-means, spectral clustering, graph partitioning,
      cluster-count indices, Bayesian/nonparametric priors.
- [ ] **21 — Dimension Reduction and Factor Analysis** · p.521
      PCA (kernel/probabilistic/generalized), nuclear norm, robust PCA, ICA,
      NMF, Bayesian factor analysis, point processes.
- [ ] **22 — Data Visualization and Manifold Learning** · p.573
      MDS, Isomap, LLE, graph embedding, SNE, UMAP.
- [ ] **23 — Generalization Bounds** · p.597 ⟲
      AIC/BIC/MDL, concentration inequalities (Cramér, sub-Gaussian, Bennett,
      Hoeffding, McDiarmid, BLM), VC dimension, covering numbers and chaining,
      Rademacher complexity, algorithmic stability, PAC-Bayes.

---

## Bridge queue
<!-- CS/math correspondences visible from the TOC. Confirm from the text
     before promoting any of these to a note in concepts/. -->

- [ ] §15.2, §16.2.5 — sum-product on acyclic graphs ↔ dynamic programming
- [ ] §15.6 — junction trees / triangulated graphs ↔ chordal graphs and tree
      decomposition from algorithms
- [ ] §10.4.3 — Adaboost ↔ greedy gradient descent (author states this outright)
- [ ] §12.3 — Monge–Kantorovich distance ↔ transportation / min-cost flow
- [ ] §13.3.5 — Markov chain convergence rate ↔ spectral gap, conductance
- [ ] §20.4–20.5 — spectral clustering ↔ graph Laplacian, Cheeger inequality
- [ ] §3.6 — convex duality / KKT ↔ LP duality
- [ ] §6 — kernel trick ↔ Riesz representation

## Open questions

## Reading log

