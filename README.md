# K-Means Clustering Assignment

This repository contains the completed work for the machine-learning capabilities assignment.

## Deliverables

- An executed copy of the reference Google Colab notebook
- All code-cell outputs saved in the notebook
- A README describing the work
- A video walkthrough explaining the important code, outputs, and conclusions

## Notebook

| Part | Topic | Notebook | Video |
|---|---|---|---|
| 1 | K-means clustering and variations | [01_kmeans_clustering.ipynb](notebooks/01_kmeans_clustering.ipynb) | [Watch video](https://youtu.be/cxHYL6YLP_c) |
| 2 | AutoGluon capabilities landscape | [02_autogluon_capabilities_tour.ipynb](notebooks/02_autogluon_capabilities_tour.ipynb) | [Watch video](https://youtu.be/Ear5T0tX-PI) |
| 3 | AutoGluon end-to-end ML with metrics | [03_autogluon_zero_to_hero.ipynb](notebooks/03_autogluon_zero_to_hero.ipynb) | [Watch video](https://youtu.be/duZB_augdOI) |
| 4 | NVIDIA RAPIDS CPU/GPU comparison | [04_nvidia_rapids_zero_to_hero.ipynb](notebooks/04_nvidia_rapids_zero_to_hero.ipynb) | [Watch video](https://youtu.be/-xa0LcwWo4k) |
| 5 | PyCaret capabilities landscape | [05_pycaret_capabilities_tour.ipynb](notebooks/05_pycaret_capabilities_tour.ipynb) | [Watch video](https://youtu.be/aXdwTwDWvwI) |
| 6 | PyCaret end-to-end ML and MLOps | [06_pycaret_zero_to_hero.ipynb](notebooks/06_pycaret_zero_to_hero.ipynb) | [Watch video](https://youtu.be/39aNN6Valec) |

## Assignment parts

| Part | Topic | Status |
|---|---|---|
| 1 | K-means clustering and variations | Completed |
| 2 | AutoGluon capabilities landscape | Completed |
| 3 | AutoGluon end-to-end ML with metrics | Completed; video added |
| 4 | NVIDIA RAPIDS CPU/GPU comparison | Completed; video added |
| 5 | PyCaret capabilities landscape | Completed; video added |
| 6 | PyCaret MLOps | Completed; video added |

## Part 1 — K-means clustering and variations

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

## Part 2 — AutoGluon capabilities landscape

- Binary and multiclass classification
- Regression and quantile regression
- Rare-event fraud detection with cost-aware thresholds
- Time-series forecasting
- Text and tabular modeling
- Image classification
- Sentence embeddings and semantic search
- Tabular foundation models
- Feature importance and SHAP explanations
- Model saving, deployment, and latency comparison

## Part 3 — AutoGluon end-to-end ML with metrics

- AutoML baseline comparison
- Binary classification with ROC-AUC, PR-AUC, F1, calibration, and thresholds
- Regression and quantile regression
- Time-series forecasting and Chronos comparison
- Text-feature handling and multimodal fallback behavior
- Model ensembles, stacking, hyperparameter search, and distillation
- Deployment cloning, inference latency, and resource limits
- Feature drift, PSI monitoring, segment analysis, and data-quality checks

## Verification

The K-means notebook was executed in an independent Google Colab runtime:

- 78 code cells executed
- 78 code cells contain saved outputs
- No error outputs
- Scratch K-means matches scikit-learn on the verification dataset

The RAPIDS section records the CPU fallback because cuML was not installed in that runtime. The full GPU/CPU comparison is a separate assignment part.

The AutoGluon notebook was also executed in Google Colab:

- 84 code cells executed
- All code cells contain saved outputs
- The notebook has no saved error outputs
- The image-classification report was corrected to format text and numeric columns separately
- The MITRA foundation-model section records a memory fallback rather than claiming a completed run

The AutoGluon Zero-to-Hero notebook was executed in Google Colab. The dependency-install cell contains a recorded interruption because AutoGluon was already installed; the remaining 105 code cells contain saved outputs and the end-to-end sections completed.

The NVIDIA RAPIDS notebook was executed successfully:

- 118 code cells
- 117 code cells contain saved outputs
- No saved error outputs
- Covers cuDF, cuML, clustering, XGBoost, cuGraph, and MLOps workflows

The PyCaret capabilities notebook was executed successfully:

- 94 code cells
- 94 code cells contain saved outputs
- No saved error outputs
- Covers classification, regression, ensembles, fraud detection, clustering, anomaly detection, time series, text, interpretability, and deployment

The PyCaret Zero-to-Hero notebook was executed with no saved error outputs:

- 137 code cells
- 133 code cells contain saved outputs
- 4 optional late-stage cells have no saved output
- Covers the end-to-end lifecycle, preprocessing, classification, regression, tuning, interpretability, clustering, anomaly detection, time series, deployment, monitoring, and diagnostics

## Videos

- Part 1: [K-means clustering and variations](https://youtu.be/cxHYL6YLP_c)
- Part 2: [AutoGluon capabilities landscape](https://youtu.be/Ear5T0tX-PI)
- Part 3: [AutoGluon end-to-end ML with metrics](https://youtu.be/duZB_augdOI)
- Part 4: [NVIDIA RAPIDS CPU/GPU comparison](https://youtu.be/-xa0LcwWo4k)
- Part 5: [PyCaret capabilities landscape](https://youtu.be/aXdwTwDWvwI)
- Part 6: [PyCaret end-to-end ML and MLOps](https://youtu.be/39aNN6Valec)
