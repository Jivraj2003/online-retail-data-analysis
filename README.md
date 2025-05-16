# 🛍️ Online Retail Data Analysis

A project showcasing data cleaning, transformation, visualization, RFM analysis, and customer churn analysis on a publicly available online retail dataset.

This repository contains all the code and insights gained from working with the **Online Retail Dataset**, which includes real-world transaction data from a UK-based online store. The goal is to explore the data, understand customer behavior, and identify potential churn risks.
> 📚 **This project was completed with guidance from the [Codebasics YouTube channel](https://www.youtube.com/c/codebasics). Big thanks to them for making learning so accessible!**

---

## 📦 Dataset

The dataset used in this project is the **Online Retail Dataset**, which includes invoice-level records with details like customer ID, country, purchase date, quantity, and price. Data Set is also Provided in zip format or you can download from the given link.

> 🔗 [UCI Machine Learning Repository – Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
Data Set is also Provided in zip format.

---

## 🔍 What's Inside the Analysis?

The Jupyter notebook (`online_retail_analysis.ipynb`) walks through the following steps:

1. **📥 Data Loading & Quick Peek**
   - Load the dataset and get familiar with its structure.

2. **🧹 Data Cleaning**
   - Handle missing values and remove invalid entries (e.g., negative quantities).

3. **🛠 Feature Engineering**
   - Add new columns like `TotalPrice` and extract `Month` from dates.

4. **📊 Exploratory Data Analysis (EDA)**
   - Visualize monthly sales trends.
   - Find the top 5 countries by total sales.
   - Discover the top 5 best-selling products.

5. **📈 RFM Analysis**
   - Group customers based on **Recency**, **Frequency**, and **Monetary** values.
   - Segment customers for marketing strategies.

6. **🚪 Customer Churn Analysis**
   - Identify customers who haven’t purchased recently.
   - Analyze churn patterns and trends.

---

## ⚙️ Requirements

To run this project, you’ll need the following Python libraries:

- `pandas`
- `matplotlib`
- `openpyxl` (to read Excel files)

You can install them using pip:

```bash
pip install pandas matplotlib openpyxl
