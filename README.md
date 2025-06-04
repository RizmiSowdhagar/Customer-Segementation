# Customer Segmentation Using KMeans Clustering

This project applies unsupervised machine learning techniques to group customers into distinct segments based on behavioral and demographic features. The goal is to enable businesses to better understand customer profiles and design targeted marketing strategies.

## Objective

- Segment customers based on features like Age, Annual Income, and Spending Score  
- Identify behavioral clusters for personalized targeting  
- Visualize and interpret group characteristics to support business decisions  

## Technologies & Libraries

- **Language**: Python  
- **Data Processing**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn, Plotly  
- **Machine Learning**:  
  - Clustering: KMeans (from Scikit-learn)  
  - Feature Scaling: StandardScaler  
  - Dimensionality Reduction: PCA (Principal Component Analysis)  

## Dataset Overview

- Features:
  - Customer ID  
  - Gender  
  - Age  
  - Annual Income (k$)  
  - Spending Score (1–100)  
- The dataset represents customer attributes collected from a retail environment

## Workflow

- Loaded and explored the dataset using Pandas and Seaborn  
- Checked for null values and handled data quality issues  
- Encoded categorical features (e.g., Gender)  
- Scaled numerical features using **StandardScaler**  
- Determined optimal number of clusters using the **Elbow Method** and **Silhouette Score**  
- Applied **KMeans clustering** to segment the customers  
- Visualized clusters in 2D and 3D using Matplotlib and Plotly  
- Used **PCA** for dimensionality reduction to aid interpretation

## Results & Insights

- Identified distinct clusters such as:
  - High-income, low-spending customers  
  - Low-income, high-spending customers  
  - Moderate-spending, younger customers, etc.  
- Cluster visualizations helped reveal patterns for customer targeting and resource allocation

## Key Visualizations

- Elbow Method plot to determine optimal number of clusters  
- Silhouette Score analysis for cluster validity  
- 2D and 3D scatter plots showing customer segments  
- Heatmaps and pair plots for feature distribution

## Future Work

- Include additional features such as purchase frequency or product categories  
- Apply other clustering techniques (e.g., DBSCAN, Hierarchical Clustering) for comparison  
- Build a web dashboard using Streamlit or Dash for interactive segmentation analysis  
- Combine with RFM analysis for deeper customer profiling
