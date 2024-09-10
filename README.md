# AIVengers Project

The **AIVengers Project** aims to classify the emotional valence (positive or negative emotions) of EEG signals using machine learning techniques. This project uses Power Spectral Density (PSD) and Phase Locking Value (PLV) features extracted from EEG data to perform classification.

## Contents

- **Data Preprocessing**: Scripts for loading and preprocessing EEG datasets.
- **Feature Extraction**: Methods to compute PSD and PLV features from EEG signals.
- **Model Training**: Implementation of various machine learning models for valence classification (SVM, LGBM, RandomForest, MLP).
- **Evaluation**: Tools for evaluating model performance, including metrics like accuracy and confusion matrices.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries: numpy, scipy, scikit-learn, matplotlib, pandas, imblearn, seaborn

Install the dependencies using:

```bash
pip install -r requirements.txt
```
## Usage

1. **Clone the repository**:

    ```bash
    git clone https://github.com/alirezamirrokni/AIVengers-project.git
    ```
    
2. **Navigate to the project directory**:

    ```bash
    cd AIVengers-project
    ``` 
3. **Open `ML_project.ipynb` file and run its cells.**

## Results

The following image shows the performance of different models (based on ROC curve):

[![roc.png](https://i.postimg.cc/vZTFdHSt/roc.png)](https://postimg.cc/RNkb79mW)

## Authors        
-[Alireza Mirrokni](https://github.com/alirezamirrokni)    

