+++
image = "2022_ceus_feng.jpeg"
date = "2022-02-01"
title = "Determination of building flood risk maps from LiDAR mobile mapping data"
type = "gallery"
+++

Feng, Y., Xiao, Q., Brenner, C., Peche, A., Yang, J., Feuerhake, U., & Sester, M. (2022). Determination of building flood risk maps from LiDAR mobile mapping data. Computers, Environment and Urban Systems, 93, 101759.

### Abstract

With increasing urbanization, flooding is a major challenge for many cities today. Based on forecast precipitation, topography, and pipe networks, flood simulations can provide early warnings for areas and buildings at risk of flooding. Basement windows, doors, and underground garage entrances are common places where floodwater can flow into a building. Some buildings have been prepared or designed considering the threat of flooding, but others have not. Therefore, knowing the heights of these facade openings helps to identify places that are more susceptible to water ingress. However, such data is not yet readily available in most cities. Traditional surveying of the desired targets may be used, but this is a very time-consuming and laborious process. Instead, mobile mapping using LiDAR (light detection and ranging) is an efficient tool to obtain a large amount of high-density 3D measurement data. To use this method, it is required to extract the desired facade openings from the data in a fully automatic manner. 

This research presents a new process for the extraction of windows and doors from LiDAR mobile mapping data. Deep learning object detection models are trained to identify these objects. Usually, this requires to provide large amounts of manual annotations. In this paper, we mitigate this problem by leveraging a rule-based method. In a first step, the rule-based method is used to generate pseudo-labels. A semi-supervised learning strategy is then applied with three different levels of supervision. The results show that using only automatically generated pseudo-labels, the learning-based model outperforms the rule-based approach by 14.6% in terms of F1-score. After five hours of human supervision, it is possible to improve the model by another 6.2%.

By comparing the detected facade openings' heights with the predicted water levels from a flood simulation model, a map can be produced which assigns per-building flood risk levels. Thus, our research provides a new geographic information layer for fine-grained urban emergency response. This information can be combined with flood forecasting to provide a more targeted disaster prevention guide for the city's infrastructure and residential buildings. To the best of our knowledge, this work is the first attempt to achieve such a large scale, fine-grained building flood risk mapping.
