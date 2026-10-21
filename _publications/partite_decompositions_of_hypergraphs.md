---
title: "Optimal and Efficient Partite Decompositions of Hypergraphs"
collection: publications
category: conferences
permalink: /publication/partite-decompositions-of-hypergraphs
excerpt: ''
date: June 2026
venue: 'STOC 2026'
authors: 'Benjamin Przybocki, Nicolás Sanhueza-Matamala, and Bernardo Subercaseaux'
conferenceurl: 'https://doi.org/10.1145/3798129.3800921'
arxivurl: 'https://arxiv.org/abs/2511.11855'
---
We study the problem of partitioning the edges of a $$d$$-uniform hypergraph $$H$$ into a family $$F$$ of complete $$d$$-partite hypergraphs ($$d$$-cliques). We show that there is a partition $$F$$ in which every vertex $$v \in V(H)$$ belongs to at most $$(\frac{1}{d!} + o_d(1))n^{d-1}/\lg n$$ members of $$F$$. This settles the central question of a line of research initiated by Erdős and Pyber (1997) for graphs, and more recently by Csirmaz, Ligeti, and Tardos (2014) for hypergraphs. The $$d=2$$ case of this theorem answers a 40-year-old question of Chung, Erdős, and Spencer (1983). An immediate corollary of our result is an improved upper bound for the maximum share size for binary secret sharing schemes on uniform hypergraphs.

Building on results of Nechiporuk (1969), we prove that every graph with fixed edge density $$\gamma \in (0,1)$$ has a biclique partition of total weight at most $$(\tfrac{1}{2}+o(1))\cdot h_2(\gamma) \frac{n^2}{\lg n}$$, where $$h_2$$ is the binary entropy function. Our construction implies that such biclique partitions can be constructed in time $$O(m)$$, which answers a question of Feder and Motwani (1995) and also improves upon results of Mubayi and Turán (2010) as well as Chavan, Rabinia, Grosu, and Brocanelli (2025). Using similar techniques, we also give an $$n^{1+o(1)}$$ algorithm for finding a subgraph $$K_{t,t}$$ with $$t = (1-o(1)) \frac{\gamma}{h_2(\gamma)} \lg n$$.

Our results show that biclique partitions are information-theoretically optimal representations for graphs at every fixed density. We show that with this succinct representation one can answer independent set queries and cut queries in time $$O(n^2/ \lg n)$$, and if we increase the space usage by a constant factor, we can compute a $$2\alpha$$-approximation for the densest subgraph problem in time $$O(n^2/\lg \alpha)$$ for any $$\alpha > 1$$.
