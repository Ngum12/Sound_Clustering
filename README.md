# Sound Dataset Clustering Assignment.

## Overview

This project applies advanced clustering techniques to an unlabeled sound dataset, with the aim of uncovering potential groups or patterns in audio recordings.
Using state-of-the-art feature extraction (Mel Spectrograms), dimensionality reduction (PCA and t-SNE), and multiple clustering algorithms (KMeans, DBSCAN), the analysis delivers not just code, but also detailed visualizations and clear, insightful interpretation at every step.

## Key Steps

1. **Data Loading & Feature Extraction**

   * Loads `.wav` sound files efficiently.
   * Extracts Mel Spectrogram features using Librosa for each recording.

2. **Feature Visualization**

   * Uses pair plots and correlation heatmaps to explore raw features before dimensionality reduction.
   * Reflects on the challenges of visualizing high-dimensional audio features.

3. **Dimensionality Reduction**

   * Applies PCA (linear) and t-SNE (nonlinear) to project the high-dimensional Mel features to 3D.
   * Compares and visualizes both projections side by side.

4. **Clustering**

   * Implements both KMeans (with optimal k selected via elbow method and silhouette scores) and DBSCAN.
   * Visualizes clusters in 3D using color-coded scatter plots.

5. **Evaluation & Interpretation**

   * Evaluates clustering with Silhouette Score, Davies-Bouldin Index, and Inertia (for KMeans).
   * Presents all metrics in easy-to-read barplots and histograms.
   * Provides concise, plain-language interpretation of every result.
   * Discusses the impact of dimensionality reduction and the limitations due to unlabeled data.

6. **Capstone Extension: Hidden Markov Models (HMM)**

   * Includes a structured, original write-up on how HMMs could be used for sound event segmentation in a capstone project.

## Deliverables

* **Well-documented Jupyter Notebook:**
  Each code cell includes comments and is paired with analytic markdowns that explain results, challenges, and reasoning.
* **High-quality Visualizations:**
  Every major step includes visualizations: pair plots, heatmaps, 3D cluster scatter plots, metric barplots, and silhouette histograms.
* **Clear Results & Discussion:**
  All results are interpreted in concise, original markdown reflections, directly referencing code outputs and visual evidence.
* **Professional HMM Write-Up:**
  PART 2 demonstrates how a Hidden Markov Model could be applied to audio data for unsupervised segmentation.

## How to Run

1. **Open the notebook in Google Colab or JupyterLab.**
2. **Mount your Google Drive** (for Colab) and set the directory path to your audio data.
3. **Run all cells in order.**
   Outputs and plots will be displayed after each step.
4. **Review markdown reflections** for key insights at every stage.

## Author

* \[Ngum Dieudonne]
* \[7/04/2025 , second semester final year]
* For formative coursework: ML tech 2

---

**This project exemplifies best practices in exploratory audio data science, clustering, and technical communication.**
For questions or further collaboration, please reach out!

---

