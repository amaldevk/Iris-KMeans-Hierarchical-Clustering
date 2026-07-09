# Iris Clustering Analysis using K-Means and Hierarchical Clustering

## Project Overview

This project demonstrates the application of two popular clustering algorithms—**K-Means Clustering** and **Hierarchical Clustering**—on the Iris dataset. The objective is to group similar flowers based on their features without using the species labels, making it an example of **Unsupervised Machine Learning**.

The Iris dataset is loaded from the Scikit-learn library and contains four numerical features of iris flowers.

---

## Objective

- Load the Iris dataset from Scikit-learn.
- Preprocess the dataset by removing the species labels.
- Apply K-Means Clustering.
- Apply Hierarchical Clustering.
- Visualize the clusters using scatter plots.
---

## Dataset

**Dataset:** Iris Dataset

**Source:** Scikit-learn (`sklearn.datasets.load_iris()`)

### Features

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

Number of Samples: **150**

---

## Technologies Used

- Python
- Google Colab 
- Pandas
- Matplotlib
- Scikit-learn

---

## Clustering Algorithms

### 1. K-Means Clustering

K-Means groups similar data points into a predefined number of clusters by repeatedly updating the cluster centroids until the clusters become stable.

### 2. Hierarchical Clustering

Hierarchical Clustering groups similar data points by merging the closest clusters step by step, forming a tree-like structure called a dendrogram.

---

## Data Preprocessing

- Loaded the Iris dataset from Scikit-learn.
- Converted the dataset into a Pandas DataFrame.
- Removed the species column because clustering is an unsupervised learning task.

---

## Visualization

The clusters are visualized using scatter plots with:

- X-axis: Sepal Length
- Y-axis: Petal Length

Different colors represent different clusters.

---

## Results

- Successfully implemented K-Means Clustering.
- Successfully implemented Hierarchical Clustering.
- Visualized the clusters formed by both algorithms.
- Observed how similar flowers were grouped based on their feature values.

---

## Conclusion

Both K-Means and Hierarchical Clustering successfully grouped the Iris flowers into three clusters based on their similarities. K-Means is simple and efficient, while Hierarchical Clustering provides a tree-based view of how clusters are formed. Both algorithms are suitable for clustering the Iris dataset.




---

## Author

**Amaldev K**
