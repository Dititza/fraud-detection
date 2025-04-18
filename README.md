# Fraud Detection – INST414 Semester Project

This project applies machine learning techniques to detect fraudulent credit card transactions using the popular Kaggle dataset. The primary goal is to explore the full data science pipeline, from raw data to trained model, using a reproducible and modular project structure.

We follow the [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/) project organization for clean, collaborative, and scalable code management.

## Project Structure

```
├── data/
│   ├── raw/           <- Original `creditcard.csv` dataset (not tracked in Git)
│   ├── processed/     <- Cleaned datasets used for modeling
│
├── notebooks/         <- Contains `frauddetection.ipynb` with EDA & modeling
│
├── models/            <- Trained models (e.g., `.pkl` files)
│
├── src/               <- Source code for data, features, models, and visuals
│
├── reports/           <- Any visual outputs or figures
│
├── requirements.txt   <- All dependencies needed to run the project
└── README.md          <- This file
```

## Dependencies

- Python 3.x  
- pandas  
- scikit-learn  
- matplotlib  
- seaborn  
- jupyter  

To install all required packages:

```
pip install -r requirements.txt
```

## How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/Dititza/fraud-detection.git
cd fraud-detection
```

### 2. Add the dataset

⚠️ The dataset `creditcard.csv` is not included due to GitHub's file size limits.

Download it from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and place it here:

```
data/raw/creditcard.csv
```

### 3. Run the notebook

Launch Jupyter and open:

```
notebooks/frauddetection.ipynb
```

Run all cells to perform EDA, feature engineering, model training, and evaluation.

## Results & Evaluation

- Logistic Regression used as baseline model  
- Evaluated with:
  - Confusion matrix  
  - ROC-AUC score  
  - Classification report  

Full results are in the notebook under **Model Evaluation**.

## Reproducibility

- Code is modular and organized in the `src/` directory  
- Dataset is locally stored and ignored by Git  
- Project follows Cookiecutter standards for easy collaboration and repeatability

---

Project by **Demetri Tzamaras**  
INST414 – University of Maryland