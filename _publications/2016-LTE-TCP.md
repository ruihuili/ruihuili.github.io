---
title: "Transport Protocols Behaviour Study in Evolving Mobile Networks"
collection: publications
permalink: /publication/2016-LTE-TCP
excerpt: 'Study of interactions between 4G LTE systems and legacy transport protocols'
date: 2016-09-01
venue: 'International Symposium on Wireless Communication Systems (ISWCS)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/7600947'
citation: 'Rui Li, Mehrdad Shariat, and Maziar Nekovee (2016). &quot; 
Transport Protocols Behaviour Study in Evolving Mobile Networks.&quot; <i> International Symposium on Wireless Communication Systems (ISWCS), Poznan, Poland </i>. 456-460. DOI: 10.1109/ISWCS.2016.7600947'
---
Abstract: In this paper, we present the performance evaluation of two widely used transport protocols, i.e. TCP and UDP, operating on top of the LTE network structure. We investigate key metrics that influence directly the user experience, such as the end-to-end throughput, under various channel conditions and protocol settings. We identify a number of performance issues when the current LTE protocol stack is exposed to inferior channel quality. Specifically, when the user is located at the cell edge, the interference from neighbouring cell becomes intenser while the signal power reduces due to distance. The SINR will drop, and thus the throughput and delay degrade significantly for both UDP and TCP traffic. Although traffic running on top of UDP obtains marginally better throughput, it observes very high packet loss. Further, we discover that the transport protocols investigated are sensitive to control plane errors. Enabling RLC acknowledged mode can mitigate partially the PDU loss, and hence it improves the throughput of TCP remarkably at the cell edge. However, AM introduces additional overhead and therefore may slightly cost the throughput and delay in good link conditions. Moreover, when reaching the maximum retransmission window, AM will rely on upper layers to recover the loss. Finally, we conclude that in the existence of high control error rate, robust modulation and coding scheme is needed. Alternatively, RLC acknowledged mode can be utilised to combat the packet loss, when TCP is used as transport protocol. 


[PDF](http://ruihuili.github.io/files/li16lte.pdf)

[Code](https://github.com/ruihuili/DRL_UAV_CellularNet)
