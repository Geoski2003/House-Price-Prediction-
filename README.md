# House-Price-Prediction-
# 🏠 House Price Prediction - Data Preprocessing

## 📌 Overview
This Jupyter Notebook provides a **data preprocessing pipeline** for housing price data. 
It is designed to load raw data, clean it, and prepare it for further analysis or machine learning modeling.

The notebook is implemented in **Python** and is compatible with **Google Colab** or local Jupyter Notebook environments.

---

## 📂 Workflow

1. **Data Upload**
   - Uses `google.colab.files` to upload the dataset (`Housing.csv`).

2. **Data Loading**
   - Load the dataset into a pandas DataFrame.

3. **Data Cleaning**
   - Remove duplicate records.
   - Handle missing values column by column:
     - For numeric columns → fill with mean or median.
     - For categorical columns → fill with mode (most frequent value).

4. **Data Preparation**
   - The cleaned dataset is stored in `df_cleaned`.
   - Ready for **EDA (Exploratory Data Analysis)** or **machine learning model training**.

---

## ⚙️ Requirements

Install dependencies before running:

```bash
pip install pandas numpy
```

---

## ▶️ Usage

1. Open the notebook (`House Price - Copy.ipynb`) in **Google Colab** or Jupyter.
2. Upload the dataset (`Housing.csv`) when prompted.
3. Run each cell in order to:
   - Upload data
   - Clean duplicates
   - Handle missing values
4. Use the resulting `df_cleaned` DataFrame for further modeling.

---

## 📊 Next Steps

- Perform **exploratory data analysis (EDA)** with visualizations.
- Build machine learning models (e.g., Linear Regression, Decision Trees, Random Forest).
- Evaluate models using metrics like **R², MAE, RMSE**.

---

## 📌 Notes

- This notebook currently focuses on **data cleaning only**.
- Extend it into a **full ML pipeline** by adding model training and evaluation.
