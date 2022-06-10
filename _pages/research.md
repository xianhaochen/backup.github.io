---
layout: page
permalink: /projects/
title: Research
nav: true
---

### Representative works

#### End-to-end service auction for edge computing ([ToN'22](https://ieeexplore.ieee.org/document/9790890/authors#authors), [WCM'22](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9773059)）

Auction mechanism design has gained tremendous attention from the networking community over the past decades due to its ability to enable efficient network resource sharing over different parties. However, auction implementation for wireless networks has rarely been seen in reality. A major reason is that traditional auction schemes generally ask buyers to select and bid for resources (e.g., spectrum bands), thus incurring excessive complexity on the user side. Moreover, this "resource-oriented" trading may not be effective in providing end-to-end (E2E) quality-of-service (QoS) guarantees for buyers.

Indeed, what buyers (end users) care about the most is whether their services with the desired E2E QoS can be provided, and they do not really care what and how much resources they are allocated. In response to this demand, we propose the E2E service auction framework for edge computing systems, where the auction commodities are E2E services rather than specific resources. There are two benefits of this architecture. First, it significantly lowers the barrier to participating in the auction because buyers simply bid for services with E2E QoS requirements without having to know the inner workings. Second, it provides E2E QoS guarantees for edge computing services by taking both communication and computing resource optimization into account, unlike existing auction schemes trading either communications or computing resource alone.

#### In-network aggregation for multi-hop federated learning ([TWC'22](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9763436))

Multi-hop wireless networking provides a cost-effective solution to enhance service coverage and spectrum efficiency at the edge, which could facilitate large-scale and efficient federated learning (FL) model aggregation. Nevertheless, FL over multi-hop wireless networks has rarely been investigated. Our recent study exactly filled this void. Based on the key observation that an FL server is only interested in the aggregated form of client-side models, we optimized the model
transmissions over multi-hop wireless networks by enabling each intermediate router to perform in-network model aggregation to reduce the outgoing data traffic. Through the proposed in-network aggregation process, the model traffic is progressively shrinked on the path to gateway, thereby boosting the training performance under limited communication resources.
