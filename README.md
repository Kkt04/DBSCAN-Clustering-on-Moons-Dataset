# DBSCAN-Clustering-on-Moons-Dataset

This project demonstrates Density-Based Spatial Clustering of Applications with Noise (DBSCAN) using the make_moons dataset from sklearn.datasets. The goal is to visualize how DBSCAN clusters data points based on density, and how noise levels affect the results.

# 📘 Overview

DBSCAN is a density-based clustering algorithm that groups together points that are close to each other while marking points that lie alone in low-density regions as outliers.
This notebook explores DBSCAN with:

Synthetic two-moon dataset (make_moons)

StandardScaler for feature scaling

Visualization using Seaborn and Matplotlib

Parameter tuning (eps, min_samples)

Comparison of clustering under different noise levels

# 🧠 Key Concepts

## DBSCAN Parameters:

eps: Maximum distance between two samples to be considered as neighbors.

min_samples: Minimum number of points required to form a dense region (cluster).

Scaling: Using StandardScaler ensures fair distance measurement.

Noise Handling: DBSCAN automatically identifies and labels outliers as -1.
