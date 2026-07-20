# 🏥 Predicting Student Health Risk

> An end-to-end Machine Learning project developed for the **Kaggle Playground Series**, focused on predicting student health risk using feature engineering, ensemble learning, and deep learning techniques.

---

## 📌 Project Overview

This project explores multiple machine learning algorithms and ensemble techniques to predict student health risk from demographic and lifestyle-related features.

The complete workflow includes data preprocessing, feature engineering, model training, hyperparameter tuning, ensemble learning, neural network implementation, and Kaggle submission.

---

## 🎯 Objectives

- Predict student health risk accurately.
- Compare the performance of multiple machine learning models.
- Improve performance using ensemble learning.
- Implement a Neural Network using PyTorch.
- Optimize the model for the Kaggle evaluation metric.

---

## 📊 Dataset

**Competition:** Kaggle Playground Series

**Files**

```
train.csv
test.csv
```

The dataset contains demographic, lifestyle, and health-related attributes used to classify student health risk.

---

## ⚙️ Machine Learning Pipeline

```
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Handling Missing Values
        │
        ▼
Encoding Categorical Features
        │
        ▼
Feature Scaling
        │
        ▼
Model Training
        │
        ▼
Hyperparameter Tuning
        │
        ▼
Ensemble Learning
        │
        ▼
Neural Network (PyTorch)
        │
        ▼
Kaggle Submission
```

---

## 🤖 Models Implemented

- Logistic Regression
- Gaussian Naive Bayes
- Decision Tree
- Random Forest
- Extra Trees
- HistGradientBoosting
- XGBoost
- LightGBM
- CatBoost
- Voting Classifier
- Stacking Classifier
- Feed Forward Neural Network (PyTorch)

---

## 🏆 Best Result

| Metric | Score |
|---------|------:|
| **Best Public Kaggle Score** | **0.88233** |
| Evaluation Metric | Balanced Accuracy |
| Best Performing Model | Stacking Classifier |

---

## 📈 Model Performance

| Model | Balanced Accuracy |
|------------------------|----------------:|
| 🥇 Decision Tree | **0.884151** |
| 🥈 Stacking Classifier | **0.883117** |
| 🥉 Voting Classifier (Soft) | **0.883066** |
| XGBoost | 0.882870 |
| LightGBM | 0.881641 |
| Neural Network (PyTorch) | 0.842740 |

> **Note:** The Kaggle public leaderboard score may differ slightly from local cross-validation results.

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost
- PyTorch
- Jupyter Notebook

---

## 📂 Repository Structure

```
Predicting-Student-Health-Risk/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   ├── Health_Risk_Prediction_ML.ipynb
│   └── Health_Risk_Prediction_ANN.ipynb
│
├── models/
│
├── results/
│
├── images/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/mayankptdr/Predicting-Student-Health-Risk.git
```

Move into the project

```bash
cd Predicting-Student-Health-Risk
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 📌 Future Improvements

- Deploy the model using FastAPI
- Build a Streamlit dashboard
- Improve Neural Network performance
- Experiment with TabNet and FT-Transformer
- Automate the complete ML pipeline

---

## 👨‍💻 Author

**Mayank Patidar**

AI & Machine Learning Enthusiast

GitHub: https://github.com/mayankptdr

---

⭐ If you found this project useful, consider giving it a star.
