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

✔️ **High-dimensional**: We combine ***GIScience methods*** with ***Tensor Theory*** to deal with high-dimensional spatio-temporal field data.

✔️ **Non-linear**: We combine ***GIScience methods*** with ***Deep Learning*** (e.g., Transformer) to reveal the intrinsic structure of complex spatio-temporal data.

✔️ **High-dynamic**: We break through the two-point form (origin-destination) for flow characterization and innovatively propose ***Path Flow***.


GeoAI | GIScience & Tensor Theory
------
  A high-dimensional tensor is a desirable representation of spatiotemporal field data with multi-dimensionality, such as traffic speed data.<br>
  - Incorporating *tensor models* into *geospatial analysis* provides a better way to deal with spatiotemporal field data, reveal the intrinsic structure of complex spatio-temporal data, and capture interdependencies in multiple dimensions.
  - The incorporation of *geographic thinking* endows *tensor models* with explicit representations of spatiotemporal patterns, thereby facilitating the practical application of high-dimensional analytical methods in real scenarios, such as urban perception and pattern analysis.

  🏕️ **Urban Traffic Data Imputation:** Adopt a manifold embedding approach to depict the local geometric structure of spatio-temporal domains, and propose a novel Spatio-Temporal constrained Low-Rank Tensor Completion (ST-LRTC) method.<br>
  - ***Zilong Zhao***, Luliang Tang, Mengyuan Fang, Xue Yang, Chaokui Li, Qingquan Li (2023). Toward urban traffic scenarios and more: a spatio-temporal analysis empowered low-rank tensor completion method for data imputation. *International Journal of Geographical Information Science*, 1-34. (JCR Q1, IF=5.7, **TOP Journal in GIS**) <br>
  
  ![image](/images/Imputation.png)

  🏕️ **Urban Traffic Anomaly Diagnosis:** A novel Spatio-Temporal constrained Low-Rank Sparse Tensor (ST-LRST) method is proposed to decompose urban traffic data into normal and anomalous components.<br>
  - ***Zilong Zhao***,Luliang Tang, Chang Ren, Xue Yang, Zihan Kan, Qingquan Li (2023). Diagnosing Urban Traffic Anomalies by Integrating Geographic Information and Tensor Theory. *GIScience & Remote Sensing*. (JCR Q1, IF=6.7, **TOP Journal in GIS&RS**) <br>
  
  ![image](/images/Anomaly.png)


GeoAI | GIScience & Deep Learning
------
  Fine-grained traffic forecasting is crucial for the planning and management of urban transportation systems.<br>
  
  🗺️ **Complex Urban Traffic Forecasting:** Most current approaches concentrate on point-based and grid-based forecasts, ignoring the real bidirectional-road-based network structure.
  - Guangyue Li, ***Zilong Zhao\****, Yang Chen, Luliang Tang, Jinghan Wang, Xu Chu, Chaokui Li. Towards Complex Urban Traffic Forecasting: A Fully Attentional Approach Enhanced by Graph Representation. *IEEE Transactions on Intelligent Transportation Systems*. (Under review)

  🗺️ **Integrated and Fine-grained Traffic Forecasting:** Road segments and intersection turns, as vital elements of road networks, exhibit diverse spatial structures, yet their traffic states are interconnected due to spatial proximity.
  - Guangyue Li, ***Zilong Zhao\****, Xiaogang Guo, Luliang Tang, Huazu Zhang, Jinghan Wang. (2023). Towards integrated and fine-grained traffic forecasting: A spatio-temporal heterogeneous graph transformer approach. *Information Fusion*. (JCR Q1, **IF=18.6**, **TOP Journal in AI**)<br>
  
  ![image](/images/Prediction.png)


Human Mobility & Sustainability
------
  The modeling and analysis of human mobility behavior can facilitate the sustainable development of transportation systems, including decarbonization and resilience. <br>

  🚶 **Sustainability:** Massive personal short-distance trips impose certain travel costs on travelers, cause considerable stress on road traffic, and degrade the surrounding environment. Constructing shuttle services and encouraging residents to shift travel patterns from private modes to shuttle services may reduce traffic pressure and further provide cost-effective and eco-friendly transportation for citizens.
  - ***Zilong Zhao***, Mengyuan Fang, Luliang Tang, Xue Yang, Zihan Kan, and Qingquan Li. (2022). The impact of community shuttle services on traffic and traffic-related air pollution. *International Journal of Environmental Research and Public Health*, 19(22), 15128.<br>
  
  ![image](/images/Pollution.png)

  🚶 **Resilience:** The traditional way of using a single point to characterize the whole complex intersection cannot finely reflect the dynamic information of intersections. We upgrade the evaluation scale of intersections to turn level, propose intersection TSN, and achieve a refined and dynamic evaluation of urban intersections.
  - ***Zilong Zhao***, Luliang Tang, Xue Yang, Huazu Zhang, Guangyue Li, and Qingquan Li (2024). Identifying Critical Urban Intersections from A Fine-grained Spatio-Temporal Perspective. *Travel Behaviour and Society*.(SSCI, IF=5.2)<br>
  
  ![image](/images/TSN.png)

  🚶 **Sensing:** Timely understanding of affected areas during disasters is essential for the implementation of emergency response activities. We propose a novel framework for fine-grained information extraction and dynamic spatial-temporal awareness in disaster-stricken areas based on Sina Weibo.
   - *Zhiyu Yan, Xiaogang Guo, ***Zilong Zhao***, Luliang Tang (2023). Achieving fine-grained urban flood perception and spatio-temporal evolution analysis based on social media. *Sustainable Cities and Society*. (JCR Q1, IF=11.7, TOP Journal in Urban studies)<br>


