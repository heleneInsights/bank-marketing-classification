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

Good idea — this is exactly what makes the project look complete and professional.

Here’s a **clean, concise README “Results” section** you can paste directly:

---

# 📊 Results

## 🏆 Final Model Performance (Optimized XGBoost)

The final selected model was an optimized **XGBoost Classifier**, trained using a full preprocessing pipeline and tuned with Optuna.

### Overall performance:

* **Accuracy:** 0.894
* **ROC-AUC:** 0.9337
* **F1 Macro:** 0.7727
* **F1 Weighted:** 0.9025

---

## 🎯 Class-level performance

| Class                | Precision | Recall | F1-score |
| -------------------- | --------- | ------ | -------- |
| No Subscription (0)  | 0.97      | 0.91   | 0.94     |
| Yes Subscription (1) | 0.51      | 0.75   | 0.61     |

---

## 📈 Key insights

* The model achieves **strong separation capability** between classes (ROC-AUC = 0.93).
* It significantly improves detection of potential subscribers, reaching **75% recall for Class 1**.
* Performance prioritizes **recall over precision**, aligning with a marketing use case where identifying potential customers is more important than minimizing false positives.

---

## 🧠 Business impact

* Enables prioritization of high-probability clients for targeted campaigns.
* Improves marketing efficiency by focusing resources on likely converters.
* Supports data-driven decision-making in customer outreach strategies.

---

## 📦 Model artifacts

The final model is saved as a complete pipeline, including preprocessing and the trained classifier:

```
models/xgb_optimized_pipeline.joblib
```

---

## 🚀 Summary

The optimized XGBoost model provides a strong balance between predictive performance and business utility, making it suitable for deployment in customer targeting and campaign optimization systems.

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
* XGBoost

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

Project completed — end-to-end workflow including data cleaning, exploratory data analysis, feature engineering, hyperparameter tuning, and model evaluation with multiple classifiers.

---

## ⚠️ Limitations
- Analysis is exploratory and descriptive in nature
- Further segmentation and statistical testing could enhance insights
- Some patterns may require deeper domain-specific analysis
- Due to time and computational constraints, the project was developed using a minimal subset of the available data
- Increasing the amount of data in future iterations could further improve model performance and the robustness of the insights

---

## 👤 Author

heleneInsights

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Plotly
- Matplotlib
- SciPy
- XGBoost
- LightGBM
- JobLib
- LazyPredict
- Optuna
- Jupyter Notebook