# Mall Customer Segmentation Using K-Means

## Mall Customer Segmentation
This notebook applies K-Means Clustering to segment mall customers into distinct groups based on their Annual Income and Spending Score. It demonstrates essential unsupervised learning techniques using the Mall Customer Dataset.

## Objective
To cluster customers into distinct groups using K-Means algorithm, and evaluate clustering effectiveness using Elbow Method and Silhouette Score.


## Key Steps
- Load & Preprocess: Cleaned the dataset and scaled numeric features.
- PCA: Reduced dimensions to 2D for easy visualization.
- K-Means Clustering: Fitted K-Means and assigned cluster labels.
- Elbow Method: Identified optimal number of clusters (k).
- Visualization: Plotted clusters using PCA-reduced data.
- Evaluation: Measured clustering quality with Silhouette Score.


## Results
- Optimal Clusters (k): 5 (based on Elbow Method)
- Silhouette Score: ~0.40 (indicating moderately good clustering)
- Identified meaningful customer segments based on income and spending behavior.
