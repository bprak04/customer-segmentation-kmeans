# Customer Segmentation – KMeans Clustering

This project applies KMeans clustering to segment customers from a bank marketing dataset. It uses feature scaling, PCA visualization, and cluster analysis to identify distinct customer groups for targeted marketing.

## 📁 Dataset

- Dataset: Bank Marketing Dataset (UCI)
- Format: Semicolon-separated `.csv`
- Features: Age, Balance, Job, Marital Status, Education, etc.

## 🛠 Tools & Libraries

- Python (Pandas, Seaborn, Scikit-learn, Matplotlib)
- KMeans Clustering
- PCA for 2D visualization

## 🔍 Key Steps

- Loaded and encoded categorical variables using `get_dummies`
- Scaled data using `StandardScaler`
- Used Elbow Method to select `k=3` clusters
- Trained KMeans and assigned cluster labels
- Summarized cluster profiles and visualized:
  - Average Balance per Cluster
  - Age Distribution
  - PCA-based 2D Scatter Plot

## ✅ Insights

- **Cluster 0**: Mid-age, low balance – cost-sensitive group
- **Cluster 1**: Younger customers, moderate income – good upsell candidates
- **Cluster 2**: Older, high balance – loyalty program prospects


