---
title: "Real-time risk analysis with optimization proxies"
collection: publications
category: articles
permalink: /publication/2024-07-02-real-time-risk-analysis
date: 2024-07-02
venue: "Electric Power Systems Research"
bibtexurl: "/files/bibtex/2024-07-02-real-time-risk-analysis.bib"
link: "https://www.sciencedirect.com/science/article/pii/S0378779624007089"
doi: "10.1016/j.epsr.2024.110822"
---

The increasing penetration of renewable generation and distributed energy resources requires new operating practices for power systems, wherein risk is explicitly quantified and managed. However, traditional risk-assessment frameworks are not fast enough for real-time operations, because they require numerous simulations, each of which requires solving multiple economic dispatch problems sequentially. The paper addresses this computational challenge by proposing proxy-based risk assessment, wherein optimization proxies are trained to learn the input-to-output mapping of an economic dispatch optimization solver. Once trained, the proxies make predictions in milliseconds, thereby enabling real-time risk assessment. The paper leverages self-supervised learning and end-to-end-feasible architecture to achieve high-quality sequential predictions. Numerical experiments on large systems demonstrate the scalability and accuracy of the proposed approach.