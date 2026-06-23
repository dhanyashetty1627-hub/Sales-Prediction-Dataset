# Sales-Prediction-Dataset
# Sales Prediction Using Python

## 📖 Project Overview

This project aims to predict product sales based on advertising expenditures across different media channels such as TV, Radio, and Newspaper. The objective is to analyze the relationship between advertising budgets and sales performance using Machine Learning techniques.

A Linear Regression model is developed to estimate future sales and assist businesses in making data-driven marketing decisions.

---

## 🎯 Objective

* Analyze advertising data.
* Perform data preprocessing and cleaning.
* Conduct Exploratory Data Analysis (EDA).
* Build a Linear Regression model.
* Predict product sales based on advertising investments.
* Evaluate model performance using regression metrics.

---

## 📂 Dataset Information

Dataset: Advertising Dataset

### Features

| Feature   | Description                           |
| --------- | ------------------------------------- |
| TV        | Advertising budget spent on TV        |
| Radio     | Advertising budget spent on Radio     |
| Newspaper | Advertising budget spent on Newspaper |
| Sales     | Product sales generated               |

### Target Variable

* Sales

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

* Dataset inspection
* Missing value analysis
* Statistical summary
* Correlation analysis
* Pairplot visualization
* Sales distribution analysis
* Advertising channel impact on sales

### Key Findings

* TV advertising shows a strong positive correlation with sales.
* Radio advertising moderately affects sales.
* Newspaper advertising has a comparatively weaker impact on sales.

---

## 🤖 Machine Learning Model

### Algorithm Used

Linear Regression

### Train-Test Split

* Training Data: 80%
* Testing Data: 20%

---

## 📈 Evaluation Metrics

The model is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

Expected Result:

* R² Score ≈ 0.90

This indicates that the model explains approximately 90% of the variation in sales data.

---

## 📁 Project Structure

Sales-Prediction-Using-Advertising-Dataset/

│

├── Advertising.csv

├── Sales_Prediction.ipynb

├── sales_prediction.py

├── README.md

└── requirements.txt

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/Sales-Prediction-Using-Advertising-Dataset.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Notebook

```bash
jupyter notebook
```

Open:

```text
Sales_Prediction.ipynb
```

---

## 📷 Visualizations Included

* Correlation Heatmap
* Pair Plot
* Sales Distribution Plot
* TV vs Sales Scatter Plot
* Radio vs Sales Scatter Plot
* Newspaper vs Sales Scatter Plot
* Actual vs Predicted Sales Plot

---

## 🔮 Sample Prediction

Example Input:

| TV  | Radio | Newspaper |
| --- | ----- | --------- |
| 150 | 20    | 30        |

The model predicts the expected sales based on the provided advertising budget.

---

## 📌 Conclusion

The Sales Prediction model successfully predicts product sales using advertising expenditure data. Linear Regression demonstrated strong performance with a high R² score, indicating that advertising investments significantly influence sales outcomes. This project highlights how Machine Learning can assist businesses in optimizing marketing strategies and improving decision-making.

---

## 👨‍💻 Author

Dhanya

AI & Data Science Engineering Student

Internship Project - Sales Prediction Using Python
