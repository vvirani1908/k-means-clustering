# K-Means Clustering Assignment

This repository contains the completed work for the K-means clustering assignment.

## Deliverables

- An executed copy of the reference Google Colab notebook
- All code-cell outputs saved in the notebook
- A README describing the work
- A video walkthrough explaining the important code, outputs, and conclusions

## Notebook

| Part | Topic | Notebook | Video |
|---|---|---|---|
| 1 | K-means clustering and variations | [01_kmeans_clustering.ipynb](notebooks/01_kmeans_clustering.ipynb) | [Watch video](https://youtu.be/cxHYL6YLP_c) |

## What the notebook covers

- K-means fundamentals and the SSE objective
- Lloyd's algorithm implemented from scratch
- Comparison with scikit-learn
- Random initialization and K-means++
- Empty clusters and outliers
- Bisecting K-means
- K-medians, spherical K-means, K-medoids, and MiniBatchKMeans
- Fuzzy c-means and Gaussian-mixture EM
- Clustering metrics and choosing K
- Feature scaling and failure cases
- Customer segmentation and drift monitoring
- Text, image, and embedding clustering
- Product quantization and GPU K-means context

## Verification

The submitted notebook was executed in an independent Google Colab runtime:

- 78 code cells executed
- 78 code cells contain saved outputs
- No error outputs
- Scratch K-means matches scikit-learn on the verification dataset

The RAPIDS section records the CPU fallback because cuML was not installed in that runtime. The full GPU/CPU comparison is a separate assignment part.

## Video

The video title is:

**K-Means Clustering Explained: From Scratch to Real-World Applications**

[Watch the Part 1 video](https://youtu.be/cxHYL6YLP_c)
