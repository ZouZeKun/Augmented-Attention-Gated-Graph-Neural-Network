# Attention-Augmented Gated Graph Neural Network
## Project Overview
This repository contains the official implementation of the paper: ***"Explainable Graph Neural Network for Real-time Demand States Forecasting in Water Distribution System."***  
**Out of respect for others’ intellectual property, the code reproduced from others(Zhou et al., 2022)(Li et al., 2024) in this article will not be disclosed.**  

***
## Package Requirements
  **>torch version: 2.3.0+cu121**  
  **>numpy version: 1.26.4**  
  **>pandas version: 2.2.2**  
  
***
## DATASET
L-Town.inp exceeds 100Mb GitHub upload limit. If required, please contact us.  

**Data Input Format：**  
  **1. water_pressure_file: shape(number of time steps, number of nodes)**  
  **2. water_head_file: shape(number of time steps, number of nodes)**  
  **3. Adj_file: shape(number of nodes, number of nodes)**  
  **4. node_heights: shape(number of nodes, 2)**  
  **5. node_types: shape(number of nodes, 2)**  

***
If you have any questions, please contact us at: [*zekunzou@zju.edu.cn*]

***
***Zhou, X., Liu, S., Xu, W., Xin, K., Wu, Y. and Meng, F.  2022.  Bridging hydraulics and graph signal processing: A new perspective to estimate water distribution network pressures. Water Res 217, 118416.***  
***Li, Z., Liu, H., Zhang, C. and Fu, G.  2024.  Real-time water quality prediction in water distribution networks using graph neural networks with sparse monitoring data. Water Res 250, 121018.***  
