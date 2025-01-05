---
title: "Distributed Bilevel Optimization via Adaptive Penalization with Time-Scale Separation"
collection: publications
permalink: /publications/2024_arxiv
label: 2024_arxiv
excerpt: 'Youcheng Niu, Jinming Xu, Ying Sun, Li Chai, Jiming Chen'
date: 2024-12-15
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/pdf/2412.11218'
authors: 'Youcheng Niu, Jinming Xu, Ying Sun, Li Chai, Jiming Chen'
---

Abstract: This paper studies a class of distributed bilevel optimization (DBO) problems with a coupled inner-level subproblem. Existing approaches typically rely on hypergradient estimations involving computationally expensive Hessian information. 
To address this, we propose an equivalent constrained reformulation by treating the inner-level subproblem as an inequality constraint, 
and introduce an adaptive penalty function to properly penalize both inequality and consensus constraints based on subproblem properties. 
Moreover, we propose a loopless distributed algorithm, \ALGNAME, that employs multiple-timescale updates to solve each subproblem asymptotically without 
requiring Hessian information. Theoretically, we establish convergence rates of $\mathcal{O}(\frac{\kapper^4}{(1-\rho)^2K^{1/3}})$ for nonconvex-strongly-convex cases and $\mathcal{O}(\frac{\kapper^2}{(1-\rho)^2K^{2/3}})$  for distributed min-max problems. Our analysis shows the clear dependence of convergence performance on bilevel heterogeneity, the adaptive penalty parameter, and network connectivity, with a weaker assumption on heterogeneity requiring only bounded first-order heterogeneity at the optimum. Numerical experiments validate our theoretical findings.
