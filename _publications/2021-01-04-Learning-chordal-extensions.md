---
title: "Learning chordal extensions"
collection: publications
category: articles
permalink: /publication/2021-01-04-Learning-chordal-extensions
date: 2021-01-04
venue: "Journal of Global Optimization"
bibtexurl: "/files/bibtex/2021-01-04-Learning-chordal-extensions.bib"
link: "https://doi.org/10.1007/s10898-020-00973-1"
doi: "10.1007/s10898-020-00973-1"
---


A highly influential ingredient of many techniques designed to exploit sparsity in numerical optimization is the so-called chordal extension of a graph representation of the optimization problem. The definitive relation between chordal extension and the performance of the optimization algorithm that uses the extension is not a mathematically understood task. For this reason, we follow the current research trend of looking at Combinatorial Optimization tasks by using a Machine Learning lens, and we devise a framework for learning elimination rules yielding high-quality chordal extensions. As a first building block of the learning framework, we propose an imitation learning scheme that mimics the elimination ordering provided by an expert rule. Results show that our imitation learning approach is effective in learning two classical elimination rules: the minimum degree and minimum fill-in heuristics, using simple Graph Neural Network models with only a handful of parameters. Moreover, the learned policies display remarkable generalization performance, across both graphs of larger size, and graphs from a different distribution.