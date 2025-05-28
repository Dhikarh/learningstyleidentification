Project Title: Feature Reduction and Visualization for Learning Style Classification

This repository contains Python scripts and notebooks for dimensionality reduction, feature correlation analysis, model evaluation, and visualization in the context of student learning style classification based on the Felder-Silverman Learning Style Model (FSLSM).

Contents

Feature Generation and Labeling: Synthetic dataset creation and random labeling for experimentation.

Feature Selection and Correlation Analysis: Selection of 18 key features and their correlation heatmaps.

Dimensionality Reduction:

PCA (Principal Component Analysis) for feature compression.

t-SNE (t-distributed Stochastic Neighbor Embedding) for visualization.

Model Evaluation: Comparison of classification models based on accuracy, precision, recall, and F1-score.

Visualization:

Class distribution pre- and post-dimension reduction.

Confusion matrices for top-performing models.

Scree plot and heatmaps.

Directory Structure

├── feature_extraction.py           # PCA, t-SNE, and SVD analysis
├── visualization.py                # All plots and graphs
├── evaluation.py                   # Model metrics and confusion matrix
├── data_synthesis.py               # Synthetic data generation
├── figures/                        # Output visualizations
├── tables/                         # Evaluation and feature analysis tables
└── README.md                       # This file

Getting Started

Prerequisites

Python 3.7+

numpy

pandas

matplotlib

seaborn

scikit-learn

Install dependencies:

pip install -r requirements.txt

Running the Scripts

To perform PCA and visualize results:

python feature_extraction.py

To generate visualizations (heatmaps, scatter plots):

python visualization.py

To run model evaluation and print accuracy scores:

python evaluation.py

Highlights

Dimensionality Reduction: From 44 features down to 18 using PCA and correlation thresholds.

Model Accuracy: Models were trained and tested pre- and post-reduction, with top accuracy reaching 91.3%.

Visual Insights: High-quality t-SNE and PCA plots for interpretability of class clusters.

Example Outputs

Scree Plot for PCA

t-SNE 2D Scatter Plot showing 4-class distribution

Heatmaps of selected and original features

Table summarizing accuracy and feature counts

Repository DOI

This project and dataset are available at Zenodo:
DOI: 10.5281/zenodo.15531930

References

Felder-Silverman Learning Style Model (FSLSM)

scikit-learn documentation

License

This project is licensed under the MIT License. See the LICENSE file for details.

Citation

If you use this project in your research, please cite:

Andhika RH, "Multiclass Learning Style Classification via Dimensionality Reduction and Ensemble Techniques", 2025.
