---
title: "Optimal Statistical Oblivious RAM and Search Tree in the External-Memory Model"
collection: publications
category: preprints
permalink: /publication/optimal-statistical-oblivious-ram
excerpt: ''
date: October 2026
authors: 'Elaine Shi'
eprinturl: 'https://eprint.iacr.org/2026/2419'
---
Oblivious RAM (ORAM) allows a trusted client to access (encrypted) data stored in untrusted memory, such that the access patterns reveal nothing about the data or the queries. It is well-known that any ORAM scheme must suffer from a logarithmic overhead. More precisely stated, each request must incur $$\Omega(\log_B N)$$ block transfers on average, where $$N$$ is the size of the logical memory and $$B$$ is the block size of the oblivious implementation. Moreover, the same lower bound extends to oblivious Search Trees (ST).

For upper bounds, however, we have been long stuck with a $$(\log_B N)^2$$ curse on two fronts:

1. Log-squared curse for statistically secure ORAMs: although optimality is known for computationally secure ORAMs for $$B = \Theta(1)$$ or $$B \geq \log^{1+\epsilon} N$$ (where $$\epsilon > 0$$ is an arbitrarily small constant), progress has been stagnant when it comes to statistical security.
2. Log-squared curse for oblivious search trees: for search trees, we do not know how to overcome the log-squared curse even when allowing computational assumptions.

In this paper, we break this long-standing log-squared curse for both oblivious search trees and statistically secure ORAM on broad parameter regimes:

1. Our first result gives an optimal, statistically secure ORAM with $$O(\log_B N)$$ cost as long as $$B \geq \log^{1+\epsilon} N$$.
2. Our second result gives an optimal, statistically secure oblivious search tree with $$O(\log_B N)$$ cost when $$B \geq \log^{2+\epsilon} N$$, matching the performance of the best known non-oblivious search trees in this parameter region. Notably, this means that for search trees, we can get obliviousness for free!

The assumptions on $$B$$ required to achieve optimality are standard and mild. They not only coincide with the standard wide cache-line assumption prevalent in the classical algorithms literature, but also align well with the hardware-enclave architectures that employ oblivious algorithms in practice, such as the implementations of Signal and Meta.
