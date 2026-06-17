# 📊 Bank Marketing Classification

This project applies data cleaning, exploratory data analysis, and machine learning models to predict whether a client will subscribe to a term deposit based on the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

## 🎯 Objective

The goal is to build a classification model that predicts the variable **`y`** (whether a client subscribes to a term deposit) using demographic, financial, and campaign-related features.

---

## 📁 Project Structure

```
bank-marketing-classification/
│
├── data/              # Raw and processed datasets
├── notebooks/         # Jupyter notebooks (EDA, preprocessing, modeling)
├── models/            # Saved trained models
├── reports/           # Figures and evaluation outputs
├── requirements.txt   # Project dependencies
└── README.md
```

---

## 📌 Workflow

1. Data loading and exploration (EDA)
2. Data cleaning and preprocessing
3. Feature engineering
4. Model training (classification algorithms)
5. Model evaluation and comparison
6. Final model selection and export

---

## 🤖 Models Used

* Logistic Regression (baseline)
* Random Forest Classifier
* Gradient Boosting (optional)

---

## 📊 Evaluation Metrics

Models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone <your-repo-url>
cd bank-marketing-classification
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run notebooks or scripts from `/notebooks` or `/src`.

---

## 📦 Dataset

* Source: UCI Machine Learning Repository
* Dataset: Bank Marketing Dataset
* Target variable: `y` (client subscribed to term deposit: yes/no)

---

## 📌 Status

Project in progress — final version includes model comparison and evaluation.

---

## ⚠️ Limitations
- Analysis is exploratory and descriptive in nature
- Further segmentation and statistical testing could enhance insights
- Some patterns may require deeper domain-specific analysis

---

## 👤 Author

heleneInsights

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Plotly
* Matplotlib
* SciPy
* LazyPredict
* Jupyter Notebook