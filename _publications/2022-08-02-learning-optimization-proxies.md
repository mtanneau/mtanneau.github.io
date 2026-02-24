---
title: "Learning optimization proxies for large-scale Security-Constrained Economic Dispatch"
collection: publications
category: articles
permalink: /publication/2022-08-02-learning-optimization-proxies
date: 2022-08-02
venue: "Electric Power Systems Research"
bibtexurl: "/files/bibtex/2022-08-02-learning-optimization-proxies.bib"
link: "https://www.sciencedirect.com/science/article/pii/S0378779622006629"
doi: "10.1016/j.epsr.2022.108566"
---

The Security-Constrained Economic Dispatch (SCED) is a fundamental optimization model for Transmission System Operators (TSO) to clear real-time energy markets while ensuring reliable operations of power grids. In a context of growing operational uncertainty, due to increased penetration of renewable generators and distributed energy resources, operators must continuously monitor risk in real-time, i.e., they must quickly assess the system’s behavior under various changes in load and renewable production. Unfortunately, systematically solving an optimization problem for each such scenario is not practical given the tight constraints of real-time operations. To overcome this limitation, this paper proposes to learn an optimization proxy for SCED, i.e., a Machine Learning (ML) model that can predict an optimal solution for SCED in milliseconds. Motivated by a principled analysis of the market-clearing optimizations of MISO, the paper proposes a novel just-in-time ML pipeline that addresses the main challenges of learning SCED solutions, i.e., the variability in load, renewable output and production costs, as well as the combinatorial structure of commitment decisions. A novel combined classification-plus-regression architecture is also proposed, to further capture the behavior of SCED solutions. Numerical experiments are reported on the French transmission system, and demonstrate the approach’s ability to produce, within a time frame that is compatible with real-time operations, accurate optimization proxies that produce relative errors below 1%.