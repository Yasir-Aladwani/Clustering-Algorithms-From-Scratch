# Clustering Algorithms from Scratch

## Project Overview

This project implements two popular unsupervised learning algorithms **from scratch** to understand how clustering works internally.

The goal of the project is to explore how clustering algorithms behave on datasets with different shapes and structures.

The algorithms implemented in this project are:

* **K-Means**
* **DBSCAN**

The project also visualizes clustering results and evaluates the performance of each algorithm using multiple metrics.

---

## Datasets

To test the algorithms, several synthetic datasets were generated using `scikit-learn`.

The datasets include:

* **Blobs** – well-separated spherical clusters
* **Anisotropic clusters** – stretched clusters with different orientations
* **Noisy Moons** – non-linear curved clusters
* **Noisy Circles** – circular clusters with noise

These datasets help illustrate how different clustering algorithms behave under different data structures.

---

## Implemented Algorithms

### K-Means (From Scratch)

K-Means is a centroid-based clustering algorithm that works by:

1. Randomly initializing cluster centroids
2. Assigning each point to the nearest centroid
3. Updating centroids based on the mean of assigned points
4. Repeating until convergence

The **Elbow Method** is also used to estimate a suitable number of clusters.

---

### DBSCAN (From Scratch)

DBSCAN is a density-based clustering algorithm that groups points based on density rather than distance to centroids.

Key advantages of DBSCAN:

* Detects clusters of **arbitrary shapes**
* Identifies **noise points**
* Does **not require specifying the number of clusters**

---

## Visualization

The project visualizes:

* The original datasets
* Clustering results for **K-Means**
* Clustering results for **DBSCAN**
* Elbow method plots

These visualizations help compare how each algorithm performs on different dataset structures.

---

## Evaluation Metrics

To compare the clustering performance, the following metrics are used:

* **F-Measure**
* **Normalized Mutual Information (NMI)**
* **Rand Score**

These metrics measure how well the predicted clusters match the true labels of the datasets.

---

## Technologies Used

* Python
* NumPy
* pandas
* scikit-learn
* matplotlib

---

## Key Learning Outcomes

This project demonstrates:

* How clustering algorithms work internally
* Differences between centroid-based and density-based clustering
* How dataset structure affects clustering performance
* How to evaluate clustering results using multiple metrics

---

## Future Improvements

Possible improvements include:

* Comparing results with **scikit-learn built-in implementations**
* Adding **Silhouette Score analysis**
* Testing on **real-world datasets**
* Implementing additional clustering algorithms such as **Hierarchical Clustering**

---

## Author

**Yasir Abdullah Al-Adwani**

Artificial Intelligence Graduate

