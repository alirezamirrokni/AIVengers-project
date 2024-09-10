# AIVengers Project

The **AIVengers Project** aims to classify the emotional valence (positive or negative emotions) of EEG signals using machine learning techniques. This project uses Power Spectral Density (PSD) and Phase Locking Value (PLV) features extracted from EEG data to perform classification.

## Contents

- **Data Preprocessing**: Scripts for loading and preprocessing EEG datasets.
- **Feature Extraction**: Methods to compute PSD and PLV features from EEG signals.
- **Model Training**: Implementation of various machine learning models for valence classification.
- **Evaluation**: Tools for evaluating model performance, including metrics like accuracy and confusion matrices.

## Getting Started

To get started, clone the repository and follow the instructions below to set up your environment. The provided scripts can be used to preprocess data, train models, and evaluate results.

### Prerequisites

Ensure you have Python 3.x installed. The required Python libraries are listed in the `requirements.txt` file:

```bash
numpy
scipy
scikit-learn
matplotlib
pandas
imblearn
seaborn
