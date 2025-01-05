---
title: "Distributed Stochastic Bilevel Optimization: Improved Complexity and Heterogeneity Analysis"
collection: publications
category: manuscripts
permalink: /publication/2023_LoPA_arxiv
excerpt: 'Youcheng Niu, Jinming Xu, Ying Sun, Yan Huang, and Li Chai'
date: 2023-12-22
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/pdf/2312.14690'
citation: 'Youcheng Niu, Jinming Xu, Ying Sun, Yan Huang, and Li Chai'
---

Abstract: This paper consider solving a class of nonconvex-strongly-convex distributed stochastic bilevel optimization (DSBO) problems with personalized inner-level objectives. Most existing algorithms require computational loops for hypergradient estimation, leading to computational inefficiency. Moreover, the impact of data heterogeneity on convergence in bilevel problems is not explicitly characterized yet. To address these issues, we propose LoPA, a loopless personalized distributed algorithm that leverages a tracking mechanism for iterative approximation of inner-level solutions and Hessian-inverse matrices without relying on extra computation loops. Our theoretical analysis explicitly characterizes the heterogeneity across nodes (denoted by $b$), and establishes a sublinear rate of 
$\mathcal{O}( {\frac{1}{{{{\left( {1 - \rho } \right)}}K}} + \frac{{(\frac{b}{\sqrt{m}})^{\frac{2}{3}}  }}{{\left( {1 - \rho } \right)^{\frac{2}{3}} K^{\frac{2}{3}} }} + \frac{1}{\sqrt{ K }}( {\sigma _{\rm p}}  + \frac{1}{\sqrt{m}}{\sigma _{\rm c }}  ) } )$   without the boundedness of local hypergradients, where $\sigma _{\rm p }$ and $\sigma _{\rm c}$ represent the gradient sampling variances  associated with the inner- and  outer-level variables, respectively.  We also integrate LoPA with a gradient tracking scheme to eliminate the impact of data heterogeneity, yielding an improved rate of
${\mathcal{O}}(\frac{{1}}{{ (1-\rho)^2K }} + \frac{1}{\sqrt{K}}( \sigma_{\rm p}  + \frac{1}{\sqrt{m}}\sigma_{\rm c} ) )$. The computational complexity of  LoPA is of ${{\mathcal{O}}}({\epsilon^{-2}})$ to an $\epsilon$-stationary point, matching the communication complexity due to the loopless structure, which outperforms existing counterparts for DSBO. 
 Numerical experiments validate the effectiveness of the proposed algorithm. 
