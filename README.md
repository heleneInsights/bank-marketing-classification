# 📊 Bank Marketing Classification

This project applies data cleaning, exploratory data analysis, and machine learning models to predict whether a client will subscribe to a term deposit based on the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

## 🎯 Objective

The goal is to build a classification model that predicts the variable **`y`** (whether a client subscribes to a term deposit) using demographic, financial, and campaign-related features.

---

## Dataset Description

This project uses the **Bank Marketing Dataset** from the UCI Machine Learning Repository. The dataset contains information from direct marketing campaigns conducted by a Portuguese banking institution, where clients were contacted by phone to promote term deposit subscriptions.

The dataset includes **4,119 client records** and **20 input features** describing client demographics, financial status, previous marketing interactions, and macroeconomic conditions. The target variable, **`y`**, indicates whether a client subscribed to a term deposit (`yes` or `no`).

The goal is to build and evaluate classification models that predict the likelihood of a client subscribing to the offered banking product.

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

* Decision Tree (baseline)
* Support Vector Machine
* Other (optional)

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
git clone https://github.com/heleneInsights/bank-marketing-classification.git
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