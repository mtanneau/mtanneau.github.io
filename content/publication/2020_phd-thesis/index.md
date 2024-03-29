---
title: Exploiting Structure in Mixed-Integer Linear and Nonlinear Programming
publication_types:
  - "7"
authors:
  - admin
abstract: "The past 70 years have witnessed tremendous performance improvements
  of algorithms and software for mixed-integer programming. These developments
  have been met by a likewise increase in the size and complexity of the models
  that practitioners aim to solve: there is no shortage of challenging problems.
  In that context, this thesis investigates the use of structure-exploiting
  techniques within generic optimization paradigms, to tackle large-scale or
  otherwise intractable instances. In particular, we build on the observation
  that structure-exploiting techniques can often be viewed as specialized
  implementations of one or several individual components of generic MIP
  algorithms. First, we consider the coordination of Distributed Energy
  Resources in power systems. This problem is first formulated as a centralized
  –but intractable– mixed-integer linear program, then reformulated using
  Dantzig-Wolfe decomposition and solved by a column-generation algorithm. The
  proposed framework is generic, i.e., it can handle resources of arbitrary
  nature, and computationally efficient: problems with thousands or resources
  are solved to proven optimality in less than an hour. Finally, besides
  scalability, the decomposition scheme naturally addresses some privacy
  concerns regarding the operation of individual resources. Second, we focus on
  structure-exploiting interior-point methods for linear programming. To that
  end, we develop an open-source interior-point solver, Tulip, whose algorithmic
  framework is disentangled from linear algebra implementations. This flexible
  design allows to easily integrate specialized, user-provided linear algebra
  routines. Through various numerical experiments, we demonstrate the
  flexibility, efficiency and robustness of the code. Finally, we investigate
  the separation of disjunctive cutting planes in mixed-integer conic
  programming, and demonstrate the benefits of exploiting a problem’s conic
  structure. Leveraging conic duality, the separation of disjunctive cuts is
  formulated in a single cut-generating conic problem (CGCP); this dual
  perspective offers a number of insights that were unavailable to previous
  approaches. In particular, we study the theoretical and computational merits
  of several normalization conditions, including the loss of strong conic
  duality in the separation problem, and the separation of conic-infeasible
  points in the context of outer-approximation algorithms. Computational
  experiments demonstrate the efficiency of the proposed approach on several
  classes of instances."
draft: false
featured: false
image:
  filename: ""
  focal_point: ""
  preview_only: false
date: 2020-10-01T21:38:31.575Z
---
