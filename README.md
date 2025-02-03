# Network Traffic Anomaly Detection using DBSCAN

## Overview
This project focuses on detecting anomalies in network traffic using DBSCAN (Density-Based Spatial Clustering of Applications with Noise), an unsupervised machine learning algorithm. Anomaly detection is crucial for identifying suspicious activities, cyber threats, and unusual traffic patterns in network security. 

## Methodology
The project follows a structured workflow, starting with data preprocessing, where missing values are handled, categorical features are encoded, and data is normalized for better clustering performance. The DBSCAN algorithm is applied to detect anomalies by clustering normal network traffic while labeling outliers as anomalies. The key advantage of DBSCAN is that it does not require the number of clusters to be predefined and can efficiently detect irregular patterns.  

## Key Features 
- Data Preprocessing : Handling missing values, encoding categorical data, and feature scaling.  
- DBSCAN Clustering : Identifying dense clusters of normal traffic while flagging outliers.  
- Visualization : Using Matplotlib to analyze traffic patterns.  
- Performance Evaluation : Evaluating the clustering effectiveness using Silhouette Score.  



## Results 
The model successfully detects anomalous network traffic, identifying potential security threats. The Silhouette Score validates the clustering efficiency, and outliers are flagged for further investigation. 

