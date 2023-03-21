---
layout: page
permalink: /projects/
title: Research
nav: true
---

#### 1. In-network aggregation for multi-hop federated learning ([TWC'22](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9763436))

Multi-hop wireless networking provides a cost-effective solution to enhance service coverage and spectrum efficiency at the edge, which could facilitate large-scale and efficient federated learning (FL) model aggregation. Nevertheless, FL over multi-hop wireless networks has rarely been investigated. Our recent study exactly fills this void. Based on the critical observation that an FL server is only interested in the aggregated form of client-side models, we optimize the model
transmissions over multi-hop wireless networks by enabling each intermediate router to perform model aggregation to reduce the outgoing data traffic, which is called "in-network aggregation." In so doing, the large volume of model traffic can be progressively shrunk over the intermediate routers on the routing path, thereby boosting the FL training performance over resource-limited edge networks.

#### 2. End-to-end service auction for edge computing ([ToN'22](https://ieeexplore.ieee.org/document/9790890), [WCM'22](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9773059)）

Auction mechanism design has gained tremendous attention from the networking community over the past decades due to its ability to enable efficient network resource sharing over different parties. However, auction implementation for wireless networks has rarely been seen in reality. A major reason is that traditional auction schemes generally ask buyers to select and bid for specific resources (e.g., spectrum bands), which incurs excessive complexity on the user side. Moreover, this "resource-oriented" trading is not effective in providing end-to-end (E2E) quality-of-service (QoS) guarantees for buyers. In response to this demand, we propose an E2E service auction framework for edge computing systems, where the auction commodities are E2E edge computing services to ensure QoS guarantees for winning users.
