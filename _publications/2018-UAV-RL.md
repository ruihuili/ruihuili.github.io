---
title: "Learning Driven Mobility Control of Airborne Base Stations in Emergency Networks"
collection: publications
permalink: /publication/2018-UAV-RL
excerpt: 'This paper investigates DRL methods in mobility control of cellular base stations mounted on drones in emergency scenarios.'
date: 2018-12-01
venue: 'ACM SIGMETRICS Performance Evaluation Review'
paperurl: 'https://dl.acm.org/citation.cfm?id=3308964'

citation: 'Rui Li, Chaoyun Zhang, Paul Patras, Razvan Stanica, and Fabrice Valois. (2019). &quot; Learning Driven Mobility Control of Airborne Base Stations in Emergency Networks.&quot; <i> SIGMETRICS Perform. Eval. Rev. 46, 3 (January 2019), 163-166. </i>. DOI: https://doi.org/10.1145/3308897.3308964.'


---

Abstract: Mobile base stations mounted on unmanned aerial vehicles (UAVs) provide viable wireless coverage solutions in challenging landscapes and conditions, where cellular/WiFi infrastructure is unavailable. Operating multiple such airborne base stations, to ensure reliable user connectivity, demands intelligent control of UAV movements, as poor signal strength and user outage can be catastrophic to mission critical scenarios. In this paper, we propose a deep reinforcement learning based solution to tackle the challenges of base stations mobility control. We design an Asynchronous Advantage Actor-Critic (A3C) algorithm that employs a custom reward function, which incorporates SINR and outage events information, and seeks to provide mobile user coverage with the highest possible signal quality. Preliminary results reveal that our solution converges after 4×105 steps of training, after which it outperforms a benchmark gradientbased alternative, as we attain 5dB higher median SINR during an entire test mission of 10,000 steps.

[PDF](http://ruihuili.github.io/files/li18wain.pdf)

[Code](https://github.com/ruihuili/DRL_UAV_CellularNet)


