---
title: "Dual Lagrangian Learning for Conic Optimization"
collection: publications
category: articles
permalink: /publication/2024-12-10-dual-lagrangian-learning
date: 2024-12-10
venue: "Advances in Neural Information Processing Systems"
bibtexurl: "/files/bibtex/2024-12-10-dual-lagrangian-learning.bib"
paperurl: "/files/papers/2024-12-10-dual-lagrangian-learning.pdf"
link: "https://proceedings.neurips.cc/paper_files/paper/2024/hash/646d2edf873df99d36aaeeaf058acdb8-Abstract-Conference.html"
doi: "10.52202/079017-1764"
---

![DLL](/images/DLL.svg)

This paper presents Dual Lagrangian Learning (DLL), a principled learning methodology for dual conic optimization proxies.DLL leverages conic duality and the representation power of ML models to provide high-duality, dual-feasible solutions, and therefore valid Lagrangian dual bounds, for linear and nonlinear conic optimization problems.The paper introduces a systematic dual completion procedure, differentiable conic projection layers, and a self-supervised learning framework based on Lagrangian duality.It also provides closed-form dual completion formulae for broad classes of conic problems, which eliminate the need for costly implicit layers.The effectiveness of DLL is demonstrated on linear and nonlinear conic optimization problems.The proposed methodology significantly outperforms a state-of-the-art learning-based method, and achieves 1000x speedups over commercial interior-point solvers with optimality gaps under 0.5% on average.