# Task 8 - K-Means Clustering (Mall Customer Segmentation)

## Objective
Perform K-Means clustering on the Mall Customers dataset and evaluate clusters with Elbow method and Silhouette Score.

## Files
- notebook.ipynb - Colab notebook with full pipeline
- Mall_Customers.csv - dataset (or link)
- results/mall_customers_with_clusters.csv - output with assigned cluster labels
- results/income_vs_spending_clusters.png - visualizatio

## Steps performed
1. Loaded dataset, basic EDA.
2. Selected numeric features: Age, Annual Income (k$), Spending Score (1-100).
3. Scaled features with StandardScaler.
4. Used Elbow method (inertia) and Silhouette Score to pick k.
5. Fitted KMeans and saved cluster labels.
6. Visualized clusters (PCA 2D and feature scatter).
7. Evaluated inertia and silhouette score.

## How to run
Open `notebook.ipynb` in Google Colab and run all cells. Make sure `Mall_Customers.csv` is uploaded to the notebook environment or mounted from Drive.
