# CustomerHarbor: Clustering Wholesale Customers for In-Depth Spending Insights

## Overview

CustomerHarbor is a project focused on clustering wholesale customers to gain in-depth insights into their spending patterns. The primary objective is to group customers based on their purchasing behavior, allowing for targeted marketing and personalized strategies. The project employs the KMeans clustering algorithm and utilizes dimensionality reduction techniques such as Principal Component Analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE) for visualization.

## Key Features

- **Data Loading:** The dataset is sourced from the UCI Machine Learning Repository, containing information about wholesale customers.

- **Data Preprocessing:** The data is loaded and outliers are identified using Mahalanobis distance. Outliers are then analyzed to understand their impact on the dataset.

- **Clustering:** KMeans clustering is performed on the preprocessed data. The elbow method is employed to determine the optimal number of clusters.

- **Visualization:** The clusters are visualized using PCA and t-SNE, providing a graphical representation of the customer groups.

- **Understanding Customer Groups:** Mean spending patterns for each cluster are analyzed to understand the characteristics of each group.

- **Targeted Marketing Sections:** The project identifies top spending categories for each customer group, enabling targeted marketing strategies.

- **CSV Outputs:** The project outputs two CSV files - 'clusters.csv' containing cluster assignments for each customer and 'groupings.csv' containing mean spending values for each group.

## Project Structure

- **CustomerHarbor.ipynb:** Jupyter Notebook containing the main project code, including data loading, preprocessing, clustering, visualization, and analysis.

- **clusters.csv:** CSV file containing cluster assignments for each customer.

- **groupings.csv:** CSV file containing mean spending values for each customer group.

- **Wholesale customers data.csv:** Dataset sourced from the UCI Machine Learning Repository.

- **requirements.txt:** File listing the project dependencies, including pandas, numpy, seaborn, matplotlib, and scikit-learn.

## How to Use

1. **Clone the repository:**

   ```bash
       git clone https://github.com/NabilYimer/CustomerHarbor-Clustering-Wholesale-Customers-for-In-Depth-Spending-Insights
2. **Install the required dependencies:**

   ```bash
       pip install -r requirements.txt
