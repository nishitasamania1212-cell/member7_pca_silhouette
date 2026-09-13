# Credit Card Customer Segmentation – PCA & Silhouette Analysis

This repository contains the **Member 7 contribution** to the Credit Card Customer Behaviour Segmentation project.

The main focus of this work is to evaluate the clustering results using **Principal Component Analysis (PCA)** and the **Silhouette Score**, and to compare the performance of K-Means and Agglomerative Clustering.

## 📌 Project Overview

Credit card customers have different spending, payment, and cash-advance behaviours. Clustering helps identify groups of customers with similar financial behaviour without requiring predefined labels.

In this project, clustering techniques such as **K-Means** and **Agglomerative Clustering** are used to identify meaningful customer segments.

This repository focuses specifically on:

- Principal Component Analysis (PCA)
- PCA-based cluster visualization
- Silhouette Score evaluation
- K-Means vs Agglomerative Clustering comparison

## 🎯 Objectives

- Reduce high-dimensional customer data using PCA.
- Visualize customer clusters in a 2D space.
- Evaluate the quality of Agglomerative Clustering using Silhouette Score.
- Compare K-Means and Agglomerative Clustering.
- Identify the clustering algorithm with better cluster separation.

## 🧠 Techniques Used

### 1. Principal Component Analysis (PCA)

PCA is used to reduce the dimensionality of the scaled customer dataset to two principal components.

This makes it easier to visualize the customer clusters in a two-dimensional space.

### 2. Silhouette Score

The Silhouette Score evaluates how well-separated and compact the clusters are.

- A score closer to **+1** indicates better-defined clusters.
- A score around **0** indicates overlapping clusters.
- A negative score may indicate poorly assigned data points.

### 3. Model Comparison

The Silhouette Scores of:

- K-Means
- Agglomerative Clustering

are compared to determine which algorithm produces better-separated clusters.

## 📊 Analysis Workflow

```text
Scaled Customer Data
        ↓
       PCA
        ↓
2D Cluster Visualization
        ↓
Silhouette Score
        ↓
K-Means vs Agglomerative Comparison
        ↓
Final Model Evaluation
