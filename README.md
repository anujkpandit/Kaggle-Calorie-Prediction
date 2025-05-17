# 🏋️‍♂️ Calorie Burn Prediction – Kaggle Playground Series S5E5

This is my submission for the **Kaggle Playground Series - Season 5, Episode 5** competition, where the goal is to **predict the number of calories burned** during a workout session based on physiological and workout metrics.

> 🔗 [View Kaggle Competition](https://www.kaggle.com/competitions/playground-series-s5e5)

---

## 📌 Problem Statement

Given data on:
- Age
- Height
- Weight
- Duration of exercise
- Heart rate
- Body temperature
- Gender (categorical)

...the task is to predict the number of calories burned (`Calories`) using regression models.

---

## 🧠 ML Approach

- **EDA**: Basic exploration using `.describe()` and visual inspection
- **Preprocessing**:
  - Encoded categorical variable `Gender`
  - No missing values
  - Skipped feature scaling as tree-based models were used
- **Model Used**: `RandomForestRegressor`
- **Evaluation Metric**: `RMSLE` (Root Mean Squared Logarithmic Error)

---

## 📊 RMSLE Score

**Validation RMSLE**: `0.0634`

---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `kaggle_calorie_model.ipynb` | Main Jupyter notebook with training, prediction, and submission code |
| `submission.csv` | Final predictions for submission |
| `requirements.txt` | Python libraries used |
| *(Note: train/test CSVs removed due to size, download them from Kaggle)* |

---

## 📥 How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/anujkpandit/Kaggle-Calorie-Prediction.git
   cd Kaggle-Calorie-Prediction
2. Install requirements:
   ```bash
   pip install -r requirements.txt
3. Download the dataset from Kaggle Competition Page

4. Run the notebook:
  ```bash
  jupyter notebook kaggle_calorie_model.ipynb

  
##🔧 Tech Stack
Python

Pandas

NumPy

Scikit-learn

Jupyter Notebook

📄 License
This project is under the MIT License – feel free to use, fork, or modify.
