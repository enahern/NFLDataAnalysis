NFL Combine Clustering Analysis
Project Overview

This project applies unsupervised learning techniques to NFL Combine data (2008–2022) to identify performance-based player archetypes. Using K-means clustering and Principal Component Analysis (PCA), the analysis reveals distinct profiles of athletes based solely on physical and athletic metrics—without position labels.

The goal is to demonstrate how machine learning can uncover hidden patterns in sports performance data, offering potential applications in scouting, player evaluation, and strategy development.


Key Findings

Optimal clustering at k = 2, confirmed by Elbow and Silhouette methods

Two athletic archetypes emerged:

- Cluster 1: Speed & agility (WR, CB, S profiles)

- Cluster 2: Size & strength (TE, LB, QB profiles)

Strong alignment with real-world positions, despite excluding position data

PCA and radar plots were essential in interpreting cluster separation

Full details, methodology, and visualizations are available in the final report (PDF)



Tools & Technologies

- Python

- Pandas, NumPy – data preprocessing

- Scikit-learn – K-means clustering, PCA, scaling

- Matplotlib, Seaborn – visualization



Repository Contents

NFL_Combine_Clustering_Report.pdf – Full project write-up with methods, results, and figures

Source code notebooks/scripts for clustering, preprocessing, and visualization
