# CNN-model-and-SHAP-analysis-for-EMI-based-compressive-strength-prediction-of-GPC
“CNN model and SHAP analysis for EMI-based compressive strength prediction of geopolymer concrete”
GPC_EMI_CNN_SHAP

This repository contains all scripts, Jupyter Notebooks, and example data related to the study:

“Non-destructive compressive strength prediction of geopolymer concrete using CNN and SHAP explainability of EMI signatures” submitted to Composites Part B: Engineering.

Contents:

Notebook.ipynb — Complete workflow: data preprocessing, CNN model definition, training, evaluation, and SHAP analysis of frequency-domain EMI data.

requirements.txt — Python packages and versions required to run the notebook.

data/ — Example EMI datasets (small, for demonstration purposes).

model/ — Trained CNN model weights (optional, for reproducibility).

Purpose:
The repository enables full reproducibility of the results presented in the manuscript, including:

CNN-based regression modeling of compressive strength from EMI frequency signatures.

Feature importance analysis using SHAP to interpret influential frequency bands (notably 400–500 kHz).

Generation of figures such as SHAP beeswarm and summary plots.

Usage Instructions:

Clone the repository:

git clone https://github.com/yourusername/GPC_EMI_CNN_SHAP.git


Install dependencies:

pip install -r requirements.txt


Open Notebook.ipynb and follow the cells to reproduce all figures and analysis.

Data Availability:
All code, workflows, and sample data are publicly available in this repository to ensure transparency and reproducibility of the published study.
