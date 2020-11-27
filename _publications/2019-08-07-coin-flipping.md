---
title: "Coin-Flipping, Ball-Dropping, and Grass-Hopping for Generating Random Graphs from Matrices of Edge Probabilities"
collection: publications
permalink: /publication/2019-08-07-coin-flipping
excerpt: 'Fast methods for generating random Kronecker networks from stochastic adjacency matrices.'
date: 2019-08-07
venue: 'Society for Industrial and Applied Mathematics (SIAM) Review'
paperurl: 'https://epubs.siam.org/doi/pdf/10.1137/17M1127132'
citation: 'Ramani, A. S., Eikmeier, N., & Gleich, D. F. (2019). Coin-flipping, ball-dropping, and grass-hopping for generating random graphs from matrices of edge probabilities. <i>SIAM Review</i>, 61(3), 549-595.'
---
Abstract: Common models for random graphs, such as Erdo ̋s–R ́enyi and Kronecker graphs, correspond to generating random adjacency matrices where each entry is nonzero based on a large matrix of probabilities. Generating an instance of a random graph based on these models is easy, although inefficient, by flipping biased coins (i.e., sampling binomial random variables) for each possible edge. This process is inefficient because most large graph models correspond to sparse graphs where the vast majority of coin flips will result in no edges. We describe some not entirely well-known, but not entirely unknown, techniques that will enable us to sample a graph by finding only the coin flips that will produce edges. Our analogies for these procedures are ball-dropping, which is easier to implement, but may need extra work due to duplicate edges, and grass-hopping, which results in no duplicated work or extra edges. Grass-hopping does this using geometric random variables. In order to use this idea for complex probability matrices such as those in Kronecker graphs, we decompose the problem into three steps, each of which is an independently useful computational primitive: (i) enumerating nondecreasing sequences; (ii) unranking multiset permutations; and (iii) decoding and encoding z-curve and Morton codes and permutations. The third step is the result of a new connection between repeated Kronecker product operations and Morton codes. Throughout, we draw connections to ideas underlying applied math and computer science, including coupon collector problems.

[Download paper here](http://arjunramani3.github.io/files/2019-08-07-coin-flipping.pdf)

