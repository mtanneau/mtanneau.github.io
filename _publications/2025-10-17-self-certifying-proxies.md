---
title: "Self-Certifying Primal-Dual Optimization Proxies for Large-Scale Batch Economic Dispatch"
collection: publications
category: preprints
permalink: /publication/2025-10-17-self-certifying-proxies
date: 2025-10-17
venue: "arXiv"
bibtexurl: /files/bibtex/2025-10-17-self-certifying-proxies.bib
link: "https://arxiv.org/abs/2510.15850"
doi: "10.48550/arXiv.2510.15850"
---

**Abstract**
Recent research has shown that optimization proxies can be trained to high fidelity, achieving average optimality gaps under 1% for large-scale problems. However, worst-case analyses show that there exist in-distribution queries that result in orders of magnitude higher optimality gap, making it difficult to trust the predictions in practice. This paper aims at striking a balance between classical solvers and optimization proxies in order to enable trustworthy deployments with interpretable speed-optimality tradeoffs based on a user-defined optimality threshold. To this end, the paper proposes a hybrid solver that leverages duality theory to efficiently bound the optimality gap of predictions, falling back to a classical solver for queries where optimality cannot be certified. To improve the achieved speedup of the hybrid solver, the paper proposes an alternative training procedure that combines the primal and dual proxy training. Experiments on large-scale transmission systems show that the hybrid solver is highly scalable. The proposed hybrid solver achieves speedups of over 1000x compared to a parallelized simplex-based solver while guaranteeing a maximum optimality gap of 2%. 