---
title: "Delmu: A Deep Learning Approach to Maximising the Utility of Virtualised Millimetre-Wave Backhauls"
collection: publications
permalink: /publication/2018-utility
excerpt: 'Network slicing utility optimisation via deep learning. [Best Paper], [Brendan Murphy Prize](http://coseners.net/history/brendan-murphy-prize/), and [Runner-up Poster at FB PhD TechTalk](http://ruihuili.github.io/files/fb_poster.pdf)'
date: 2018-11-01
venue: 'International Conference on Machine Learning for Networking'
paperurl: 'https://arxiv.org/abs/1810.00356'
citation: 'Rui Li, Chaoyun Zhang, Pan Cao, Paul Patras, and John S. Thompson. (2018). &quot; Delmu: A Deep Learning Approach to Maximising the Utility of Virtualised Millimetre-Wave Backhauls.&quot; <i>International Conference on Machine Learning for Networking</i>. 10.1007/978-3-030-19945-6'
---
Abstract: Advances in network programmability enable operators to 'slice' the physical infrastructure into independent logical networks. By this approach, each network slice aims to accommodate the demands of increasingly diverse services. However, precise allocation of resources to slices across future 5G millimetre-wave backhaul networks, to optimise the total network utility, is challenging. This is because the performance of different services often depends on conflicting requirements, including bandwidth, sensitivity to delay, or the monetary value of the traffic incurred. In this paper, we put forward a general rate utility framework for slicing mm-wave backhaul links, encompassing all known types of service utilities, i.e. logarithmic, sigmoid, polynomial, and linear. We then introduce DELMU, a deep learning solution that tackles the complexity of optimising non-convex objective functions built upon arbitrary combinations of such utilities. Specifically, by employing a stack of convolutional blocks, DELMU can learn correlations between traffic demands and achievable optimal rate assignments. We further regulate the inferences made by the neural network through a simple 'sanity check' routine, which guarantees both flow rate admissibility within the network's capacity region and minimum service levels. The proposed method can be trained within minutes, following which it computes rate allocations that match those obtained with state-of-the-art global optimisation algorithms, yet orders of magnitude faster. This confirms the applicability of DELMU to highly dynamic traffic regimes and we demonstrate up to 62% network utility gains over a baseline greedy approach.

[Paper](http://ruihuili.github.io/files/li18mln.pdf)  

[Poster](http://ruihuili.github.io/files/fb_poster.pdf)

[Code](https://github.com/ruihuili/DELMU)
