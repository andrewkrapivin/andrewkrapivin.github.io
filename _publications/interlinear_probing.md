---
title: "Linear Probing with Non-Greedy Insertions"
collection: publications
category: preprints
permalink: /publication/interlinear-probing
excerpt: ''
date: July 2026
authors: 'William Kuszmaul and Yixuan Wang'
arxivurl: 'https://arxiv.org/abs/2607.17494'
---
Linear probing hash tables classically use a *greedy* insertion strategy, placing a key $$u$$ in the first available position out of $$h(u), h(u) + 1, h(u) + 2, \ldots$$. If the hash table is filled to $$1 - 1/x$$ full, this results in $$\Theta(x^{2})$$ worst-case expected insertion time. In this paper, we introduce interlinear probing, a simple *non-greedy* insertion strategy that does better without requiring elements to be reordered within the table over time. Given $$x$$ in advance, the algorithm brings the worst-case expected insertion time (and therefore also the worst-case expected positive query time) down to $$O(x \log x)$$. We also extend the algorithm to support *negative* queries in worst-case expected time $$O(x (\log x)^2)$$. Moreover, our construction achieves $$O(x)$$ amortized insertion time, matching that of standard linear probing. Finally, we prove a lower bound showing that any stable insertion strategy for linear probing must incur $$\Omega(x \sqrt{\log x})$$ worst-case expected time. Combined, our results establish that the optimal worst-case expected insertion time among stable insertion strategies is $$x (\log x)^{\Theta(1)}$$.
