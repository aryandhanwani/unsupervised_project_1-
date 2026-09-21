# Mall Customer Segmentation using Unsupervised Learning

## 📌 Project Overview

This project focuses on **Mall Customer Segmentation** using Unsupervised Learning techniques.

The main goal is to divide mall customers into different groups based on their characteristics and spending behaviour.

For this project, the following clustering algorithms are used:

- K-Means Clustering
- Agglomerative Hierarchical Clustering

The clustering is mainly performed using:

- Annual Income
- Spending Score

The **Silhouette Score** is used to evaluate the quality of the clusters.

---

## 📊 Dataset

### Dataset Name
Mall Customer Segmentation Data

### Source
Kaggle

### Dataset Link
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation

### Dataset Information

The dataset contains **200 customer records** with the following columns:

| Column | Description |
|---|---|
| CustomerID | Unique customer ID |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousands of dollars |
| Spending Score (1-100) | Spending score assigned by the mall |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

---

# 🔎 Project Workflow

The project follows these main steps:

1. Load the dataset
2. Perform Exploratory Data Analysis
3. Clean and prepare the data
4. Encode Gender
5. Apply StandardScaler
6. Select Annual Income and Spending Score
7. Find the suitable number of clusters using the Elbow Method
8. Find the best K using Silhouette Score
9. Perform K-Means Clustering
10. Visualize K-Means clusters
11. Perform Agglomerative Hierarchical Clustering
12. Visualize Hierarchical clusters
13. Compare K-Means and Hierarchical Clustering
14. Compare their Silhouette Scores
15. Analyze the customer segments

---

# 📈 Exploratory Data Analysis

Before applying clustering algorithms, the dataset was explored using different visualization techniques.

### Histograms

Histograms with KDE were created for:

- Age
- Annual Income
- Spending Score

This helps understand the distribution of each numerical feature.

### Pairplot

A pairplot was created to observe relationships between the different features and identify possible patterns or groups.

### Correlation Heatmap

A correlation heatmap was used to understand the relationships between numerical features.

---

# ⚙️ Data Preprocessing

## Column Renaming

The following columns were renamed for easier use in Python:

```text
Annual Income (k$) → Annual_Income
Spending Score (1-100) → Spending_Score
