# Network Threat Detection and Early Warning with ML and DL

**Course:** SDI201 — Software Design in Intelligent Systems  
**Author:** Maftuna Sharabbaeva

## Project Overview

This project explores machine learning and deep learning techniques for network threat detection and early warning using the TON_IoT network traffic dataset.

The notebook covers data exploration, preprocessing, classification, unknown-attack detection, and early-warning evaluation.

## Objectives

- Explore network traffic patterns and attack classes.
- Investigate data leakage and prepare features for machine learning.
- Train and evaluate a Random Forest baseline.
- Compare Random Forest, XGBoost, and a Multilayer Perceptron (MLP).
- Explore unknown-attack detection using leave-one-attack-out experiments.
- Build an autoencoder-based anomaly detection approach.
- Analyze alert thresholds and the impact of false positives on early-warning systems.

## Models and Techniques

- Random Forest
- XGBoost
- Multilayer Perceptron (MLP)
- Autoencoder-based anomaly detection
- Feature importance analysis
- Classification metrics and confusion matrices
- Alert threshold tuning

## Repository Contents

| File | Description |
|---|---|
| `SDI201_Lab_380261200262.ipynb` | Google Colab notebook containing code, experiments, visualizations, and evaluation |
| `SDI201_Lab_380261200262.pdf` | Project report documenting the experiments and findings |

## Results and Analysis

The notebook compares classification performance across models and investigates unknown attacks, anomaly detection, and early-warning false-alarm rates. See the notebook and PDF report for the detailed metrics, plots, and discussion.

## How to Run

1. Open the notebook in this repository.
2. Click **Open in Colab** if available, or download the notebook and upload it to [Google Colab](https://colab.research.google.com/).
3. Upload the required dataset when prompted by the notebook.
4. Run the cells in order.

**Note:** The notebook requires the TON_IoT network dataset referenced in the code. The dataset is not included in this repository.

## Disclaimer

This is an academic project developed for educational and research purposes. Model results depend on the dataset, preprocessing, and experimental setup.
