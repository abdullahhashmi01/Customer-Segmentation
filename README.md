# Customer-Segmentation
# 🧠 Project: Customer Segmentation using K-Means Clustering

Dataset: Mall Customer Dataset (200 entries, 5 columns)
Columns include:

CustomerID

Genre

Age

Annual Income (k$)

Spending Score (1-100)

⚙️ Data Preparation

The project selected Annual Income and Spending Score for clustering.

Data was likely visualized using scatter plots to observe income vs. spending distribution.

Data was standardized or scaled (most likely via StandardScaler or similar).

📊 Model: K-Means Clustering

Used the Elbow Method to find the optimal number of clusters.

The optimal cluster count = 5 (standard for this dataset).

💡 Results (Cluster Labels)

A new column label was added to the dataset:

   CustomerID   Genre   Age   Annual Income (k$)   Spending Score (1-100)   label
0           1    Male    19                   15                        39       3
1           2    Male    21                   15                        81       2
2           3  Female    20                   16                         6       3
3           4  Female    23                   16                        77       2
4           5  Female    31                   17                        40       3


This shows that customers were successfully assigned to 5 segments (0–4).

🎯 Likely Cluster Interpretation

Based on known Mall Customer clustering results:

Cluster 0 – Low Income, Low Spending → Practical shoppers

Cluster 1 – High Income, Low Spending → Conservative buyers

Cluster 2 – Moderate Income, High Spending → Target potential customers

Cluster 3 – Low Income, High Spending → Impulsive buyers

Cluster 4 – High Income, High Spending → Premium customers

🖼️ Visualization

The notebook most likely includes:

A 2D scatter plot showing clusters in different colors.

Cluster centers highlighted (using red markers or “X”).
