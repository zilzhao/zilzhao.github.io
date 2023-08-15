---
layout: archive
title: "Research Framework"
permalink: /Research/
author_profile: true
redirect_from:
  - /Research
---

{% include base_path %}


❓ **Motivation 1:** How to characterize massive, **high-dimensional** geographic big data? <br>

❓ **Motivation 2:** How to capture the **intrinsic nonlinear** characteristics of geographic big data? <br>

❓ **Motivation 3:** How to characterize the **high-dynamic** activity flow of geographic big data? <br>

  To address these issues, my research includes:

✔️ **High-dimensional**: We combine *GIScience methods* with *Tensor Theory* to deal with high-dimensional spatio-temporal field data.

✔️ **Non-linear**: We combine *GIScience methods* with *Deep Learning* (e.g., Transformer) to re-veal the intrinsic structure of complex spatio-temporal data.

✔️ **High-dynamic**: We break through the two-point form (origin-destination) for flow characterization and innovatively propose *Path Flow*.


GeoAI | GIScience & Tensor Theory
------
  A high-dimensional tensor is a desirable representation of spatiotemporal field data with multi-dimensionality, such as traffic speed data.<br>
  - Incorporating *tensor models* into *geospatial analysis* provides a better way to deal with spatiotemporal field data, reveal the intrinsic structure of complex spatio-temporal data, and capture interdependencies in multiple dimensions.
  - The incorporation of *geographic thinking* endows *tensor models* with explicit representations of spatiotemporal patterns, thereby facilitating the practical application of high-dimensional analytical methods in real scenarios, such as urban perception and pattern analysis.

  🏕️ **Urban Traffic Data Imputation:** Adopt a manifold embedding approach to depict the local geometric structure of spatio-temporal domains, and propose a novel Spatio-Temporal constrained Low-Rank Tensor Completion (ST-LRTC) method.<br>
  - ***Zilong Zhao***, Luliang Tang, Mengyuan Fang, Xue Yang, Chaokui Li, Qingquan Li (2023). Toward urban traffic scenarios and more: a spatio-temporal analysis empowered low-rank tensor completion method for data imputation. *International Journal of Geographical Information Science*, 1-34.<br>
  ![image](/images/Imputation.png)

  🏕️ **Urban Traffic Anomaly Diagnosis:** A novel Spatio-Temporal constrained Low-Rank Sparse Tensor (ST-LRST) method is proposed to decompose urban traffic data into normal and anomalous components.<br>
  - ***Zilong Zhao***,Luliang Tang, Chang Ren, Xue Yang, Zihan Kan, Qingquan Li. Diagnosing Urban Traffic Anomalies by Integrating Geographic Information and Tensor Theory. *GIScience & Remote Sensing*. (Under Review)<br>
  ![image](/images/Anomaly.png)


GeoAI | GIScience & Deep Learning
------
  Fine-grained traffic forecasting is crucial for the planning and management of urban transportation systems.<br>
  
  🗺️ **Complex Urban Traffic Forecasting:** Most current approaches concentrate on point-based and grid-based forecasts, ignoring the real bidirectional-road-based network structure.
  - Guangyue Li, ***Zilong Zhao\****, Yang Chen, Luliang Tang, Jinghan Wang, Xu Chu, Chaokui Li. Towards Complex Urban Traffic Forecasting: A Fully Attentional Approach Enhanced by Graph Representation. *IEEE Transactions on Intelligent Transportation Systems*. (**Corresponding author**, Under review)

  🗺️ **Integrated and Fine-grained Traffic Forecasting:** Road segments and intersection turns, as vital elements of road networks, exhibit diverse spatial structures, yet their traffic states are interconnected due to spatial proximity.
  - Guangyue Li, ***Zilong Zhao\****, Xiaogang Guo, Luliang Tang, Huazu Zhang, Jinghan Wang. Towards integrated and fine-grained traffic forecasting: A spatio-temporal heterogeneous graph transformer approach. *Information Fusion*. (**Corresponding author**, Under review, 2nd round)<br>
  ![image](/images/Prediction.png)


Path flow
------
  The original OD flow's representation of trip's start and end points lacks the portrayal of trajectories/individual travel behaviors, and does not fully exploit the trajectory/travel information.<br>
  
  🚶 **Modeling:** Path flow is a high-dimensional flow structure based on all the road segments passed by the user's travel trajectory in the road network space.
  - ***Zilong Zhao***, Hongyu Shi, Luliang Tang, Zihan Kan, Mei-Po Kwan. From OD flow to Path flow: Flow Representation and Pattern Mining for Trajectory Big Data. To be submitted to *International Journal of Geographical Information Science*.

  🚶 **Sustainability:** Massive personal short-distance trips impose certain travel costs on travelers, cause considerable stress on road traffic, and degrade the surrounding environment. Constructing shuttle services and encouraging residents to shift travel patterns from private modes to shuttle services may reduce traffic pressure and further provide cost-effective and eco-friendly transportation for citizens.
  - ***Zilong Zhao***, Mengyuan Fang, Luliang Tang, Xue Yang, Zihan Kan, and Qingquan Li. (2022). The impact of community shuttle services on traffic and traffic-related air pollution. *International Journal of Environmental Research and Public Health*, 19(22), 15128.<br>
  ![image](/images/Pollution.png)

  🚶 **Resilience:** The traditional way of using a single point to characterize the whole complex intersection cannot finely reflect the dynamic information of intersections. We upgrade the evaluation scale of intersections to turn level, propose intersection TSN, and achieve a refined and dynamic evaluation of urban intersections.
  - ***Zilong Zhao***, Luliang Tang, Xue Yang, Huazu Zhang, Guangyue Li, and Qingquan Li (2023). Identifying Critical Urban Intersections from A Fine-grained Spatio-Temporal Perspective. *Travel Behaviour and Society*.<br>
  ![image](/images/TSN.png)







