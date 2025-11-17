---
title: "FENSe: Feedback-Enabled Neighbor Selection for Collaborative Perception"
excerpt: |
  <p>Plug-and-play neighbor filtering module for V2X collaborative perception; stronger accuracy–efficiency tradeoff at equal bandwidth.</p>
  <p><img src='/images/FENSe.png' alt='Temporal-aware attention demo' style='width:60%;height:auto;'></p>
collection: portfolio
---

- DKU Undergraduate Signature Work; Supervisor: Prof. Peng Sun

- Abstract: Collaborative perception aims to enhance the ego vehicle’s detection capability by integrating valuable perception data from neighbor vehicles. A critical challenge in collaborative perception systems is managing the trade-off between communi- cation overhead and detection accuracy. To address this issue, tra- ditional methods optimize feature selection typically by selectively transmitting high-confidence features from neighboring vehicles to complement the ego vehicle. However, these mechanisms often overlook redundancy and inconsistency among shared data, resulting in increased communication costs and reduced overall efficiency and accuracy. To overcome this limitation, we propose FENSe (Feedback-Enabled Neighbor Selection), a lightweight module that turns single-vehicle perception into a feedback signal for who should communicate, and thus inform the final collaborative perception results. The novelty of FENSe lies in three aspects: (1) It performs density-aware clustering of neighboring vehicles using spatial proximity and scene context to group agents with overlapping fields of view. (2) It selects one representative per cluster by estimating each neighbor’s informativeness from single-vehicle detections, with decoupled criteria during training and inference. (3) It is plug-and-play with standard intermediate-fusion pipelines, requiring minimal modification. Extensive experiments demonstrate that FENSe substantially improves detection accuracy while decreasing com- munication volume and computation time required at the ego vehicle.

- Outcomes: IEEE ICPADS (International Conference on Parallel and Distributed Systems) 2025
