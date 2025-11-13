# 📱 Flipkart Mobile Sales Analysis & Price Prediction

## 📝 **Project Overview**

This project focuses on analyzing mobile phone sales data from **Flipkart** to uncover important trends, patterns, and insights related to mobile brands, pricing, ratings, and customer preferences.
Additionally, a **Linear Regression model** is built to predict the **Selling Price** of mobile phones based on various features.

---

## 📂 **Dataset**

The project uses the **https://www.kaggle.com/datasets/devsubhash/flipkart-mobiles-dataset** dataset, containing attributes such as:

* **Brand**
* **Model**
* **Color**
* **Memory**
* **Storage**
* **Rating**
* **Original Price**
* **Selling Price**

---

## 🔍 **Exploratory Data Analysis (EDA)**

Various visualizations and statistical summaries were used to understand the dataset:

### 📊 **Key Insights Visualized**

* **Original vs. Selling Price (Scatter Plot)** — Relationship between base price and discounted price.
* **Distribution of Ratings** — Frequency of ratings across all phones.
* **Rating Distribution by Brand (Box Plot & Violin Plot)** — Comparison of quality perception across brands.
* **Samsung Rating Distribution** — Deep dive into Samsung, the most frequently sold brand.
* **Most Selling Brands (Pie Chart)** — Market share of popular brands.
* **Number of Models per Brand (Bar Graph)** — Variety offered by each brand.
* **Top 10 Most Frequent Models** — Models appearing most in the dataset.
* **Most Selling Colors** — Popular color variants among customers.
* **Phone Sales Count by Brand** — Comparing sales volume.
* **Average Selling Price by Brand** — Brand-wise pricing comparison.
* **Phones in Different Price Ranges** — Categorized as *Low*, *Mid*, and *Premium*.
* **Most Expensive Models per Brand** — Highest-priced models for top brands.
* **Selling Price vs Rating (Scatter Plot)** — Relationship between price and customer satisfaction.

---

## 🤖 **Predictive Modeling**

A **Linear Regression** model was developed to predict the **Selling Price**.

### 🛠 **Data Preprocessing**

* Missing ratings imputed.
* Categorical features encoded using **LabelEncoder**:

  * Brand, Model, Color, Memory, Storage, Price Range
* Numerical features scaled using **StandardScaler**.
* Rows containing remaining NaN values were removed.

### 🧪 **Model Training**

* Dataset split: **80% Train / 20% Test**
* Trained using **LinearRegression** from scikit-learn.

### 📈 **Model Performance**

* **R² Score:** **97.16%**
* Scatter plot of *Actual vs Predicted* prices confirms high model accuracy and consistency.

---

## 📂 **Project Structure**

```
Flipkart-Mobile-Sales-Analysis/
│
├── Flipkart_Mobiles.csv
├── flipkart_analysis.ipynb
├── README.md
└── images/                   # Visualizations (optional)
```

---

## 🧰 **Technologies Used**

* Python
* pandas, numpy
* matplotlib, seaborn
* scikit-learn
* Jupyter Notebook

---
