# Customer Segmentation using K-Means Clustering

This project demonstrates customer segmentation using the K-Means clustering algorithm. The goal is to group customers into different segments based on their annual income and spending score.

## About The Project

This project uses a Jupyter Notebook to perform the following steps:
1.  Generate a synthetic dataset of customers with 'annual_income' and 'spending_score' features.
2.  Use the Elbow Method to determine the optimal number of clusters (k) for the K-Means algorithm.
3.  Apply K-Means clustering to segment the customers into `k` clusters.
4.  Evaluate the clustering performance using the Silhouette Score.
5.  Visualize the customer segments and cluster centroids.

### Built With

* [Python](https://www.python.org/)
* [Jupyter Notebook](https://jupyter.org/)
* [Pandas](https://pandas.pydata.org/)
* [Scikit-learn](https://scikit-learn.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)

### Prerequisites

You need to have Python and Jupyter Notebook installed on your system. You can install the required libraries using pip:
```sh
pip install pandas scikit-learn matplotlib seaborn
```
## Results

The model's performance is evaluated using the Silhouette Score, which measures how similar an object is to its own cluster compared to other clusters. The Silhouette Coefficient for this model is **0.834**.

### Customer Segments

The scatter plot below visualizes the customer segments based on their annual income and spending score. The red dots represent the centroids of each cluster.

<img width="1012" height="624" alt="image" src="https://github.com/user-attachments/assets/92828ded-28eb-4cf9-8ac3-0f3b69a3cd8c" />
