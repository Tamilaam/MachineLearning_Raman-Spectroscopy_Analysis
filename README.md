# Raman Spectroscopy Data Analysis of API Compounds

This project analyzes Raman spectra of 32 active pharmaceutical ingredients (APIs) to explore their chemical signatures and assess whether spectral data alone can reliably distinguish between different compounds.

Using a combination of data preprocessing, visualization, and machine learning, we aim to uncover structure in the spectra and validate classification performance.

## Goals

- Preprocess and normalize high-dimensional Raman spectra
- Visualize patterns and separability using PCA, t-SNE, UMAP
- Classify compounds using machine learning (Logistic Regression, SVM)
- Identify the most informative Raman shifts for compound discrimination
- Compare model-selected features to known spectral bands

## Steps

1. **Data Loading** – Import spectral data and compound metadata
2. **Preprocessing** – Normalize intensities and reformat Raman shift columns
3. **Single Spectrum Plot** – Visualize one spectrum and overlay expected bands
4. **Average Spectrum** – Plot mean spectra for selected compounds
5. **Peak Detection** – Use signal processing to highlight key spectral peaks
6. **PCA Visualization** – Reduce dimensionality and visualize compound clusters
7. **Classification** – Apply logistic regression and evaluate performance
8. **t-SNE and UMAP Visualization** – Create a non-linear 2D embedding of spectral data
9. **Feature Importance** – Identify which Raman shifts drive classification

---
