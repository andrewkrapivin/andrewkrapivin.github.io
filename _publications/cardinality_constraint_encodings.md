---
title: "Near-Optimal Encodings of Cardinality Constraints"
collection: publications
category: conferences
permalink: /publication/near-optimal-encodings-of-cardinality-constraints
excerpt: ''
date: July 2026
venue: 'SAT 2026'
authors: 'Benjamin Przybocki and Bernardo Subercaseaux'
conferenceurl: 'https://doi.org/10.4230/LIPIcs.SAT.2026.23'
arxivurl: 'https://arxiv.org/abs/2603.28954'
---
We present several novel encodings for cardinality constraints, which use fewer clauses than previous encodings and, more importantly, introduce new generally applicable techniques for constructing compact encodings. First, we present a CNF encoding for the $$\text{AtMostOne}(x_1,\dots,x_n)$$ constraint using $$2n + 2 \sqrt{2n} + O(\sqrt[3]{n})$$ clauses, thus refuting the conjectured optimality of Chen's product encoding. Our construction also yields a smaller monotone circuit for the threshold-2 function, improving on a 50-year-old construction of Adleman and incidentally solving a long-standing open problem in circuit complexity. On the other hand, we show that any encoding for this constraint requires at least $$2n + \sqrt{n+1} - 2$$ clauses, which is the first nontrivial unconditional lower bound for this constraint and answers a question of Kučera, Savický, and Vorel. We then turn our attention to encodings of $$\text{AtMost}_k(x_1,\dots,x_n)$$, where we introduce "grid compression", a technique inspired by hash tables, to give encodings using $$2n + o(n)$$ clauses as long as $$k = o(\sqrt[3]{n})$$ and $$4n + o(n)$$ clauses as long as $$k = o(n)$$. Previously, the smallest known encodings were of size $$(k+1)n + o(n)$$ for $$k \le 5$$ and $$7n - o(n)$$ for $$k \ge 6$$.
