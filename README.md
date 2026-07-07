# 🛒 Predictive Modeling of Supermarket Sales Using Machine Learning

## 📌 Project Overview

This project develops a machine learning model to predict supermarket transaction sales using historical sales data. The objective is to help supermarkets make data-driven decisions regarding inventory management, staffing, and business planning by accurately estimating transaction sales.

The project was completed as the capstone project for the learning phase of the **DeepTech_Ready Data Science and Machine Learning Internship Program**.

---

## 🎯 Project Objectives

- Analyze supermarket transaction data to identify factors influencing sales.
- Perform exploratory data analysis (EDA) to uncover business insights.
- Engineer relevant features for machine learning.
- Build and compare multiple regression models.
- Select the best-performing model based on evaluation metrics.
- Provide actionable business recommendations.

---

## 📂 Dataset

**Dataset:** Supermarket Sales Dataset

**Source:** Kaggle

https://www.kaggle.com/datasets/faresashraf1001/supermarket-sales

The dataset contains **1,000 supermarket transactions** with **17 features**, including:

- Branch
- City
- Customer Type
- Gender
- Product Line
- Unit Price
- Quantity
- Payment Method
- Date
- Time
- Rating
- Sales (Target Variable)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Distribution of Sales
- Average Sales by Branch
- Average Sales by City
- Average Sales by Product Line
- Average Sales by Gender
- Customer Type Distribution
- Payment Method Distribution
- Average Sales by Hour
- Average Sales by Day of the Week
- Correlation Heatmap

The exploratory analysis provided valuable insights into customer purchasing behaviour and sales patterns.

---

## ⚙ Feature Engineering

The following preprocessing steps were performed:

- Converted Date to datetime format.
- Extracted Year, Month, Day of Week, and Hour.
- Encoded categorical variables using One-Hot Encoding.
- Split the dataset into training and testing sets.
- Removed variables that could introduce **data leakage**, including:
  - Tax 5%
  - cogs
  - gross income

---

## 🤖 Machine Learning Models

Four regression models were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

---

## 📈 Model Performance

| Model | MAE | RMSE | R² Score |
|-------|------:|------:|------:|
| Linear Regression | 58.919 | 79.565 | 0.903 |
| Decision Tree | 8.489 | 13.354 | 0.997 |
| Random Forest | **6.872** | **10.283** | **0.998** |
| Gradient Boosting | 7.594 | 10.345 | 0.998 |

**Best Model:** Random Forest Regressor

---

## 💡 Key Business Insights

- Product lines contribute differently to average sales.
- Average transaction values vary slightly across branches and cities.
- Weekend sales are generally higher than weekday sales.
- Customers use all payment methods frequently, with E-wallet being slightly more popular.
- The supermarket has a strong proportion of member customers.
- Accurate sales prediction can support inventory planning, workforce scheduling, and operational decision-making.

---

## 📁 Repository Structure

```
Predictive-Modeling-of-Supermarket-Sales
│
├── notebook/
│   └── Supermarket_Sales_Prediction.ipynb
│
├── images/
│   ├── distribution_of_sales.png
│   ├── average_sales_by_branch.png
│   ├── average_sales_by_city.png
│   ├── average_sales_by_product_line.png
│   ├── average_sales_by_gender.png
│   ├── customer_type_distribution.png
│   ├── payment_method_distribution.png
│   ├── average_sales_by_hour.png
│   ├── average_sales_by_day.png
│   └── correlation_heatmap.png
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone this repository.

```bash
git clone https://github.com/Etim-Antai/Predictive-Modeling-of-Supermarket-Sales.git
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook.

```bash
jupyter notebook
```

or upload the notebook to **Google Colab**.

---

## 📚 What I Learned

This project strengthened my understanding of:

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Regression modeling
- Model evaluation and comparison
- Identifying and preventing data leakage
- Translating analytical findings into business insights

Beyond building accurate models, this project reinforced the importance of understanding the data, selecting appropriate evaluation metrics, and developing machine learning solutions that provide meaningful business value.

---

## 👨‍💻 Author

**Etim Antai**

Electrical & Electronic Engineer | Data Analyst | Machine Learning Enthusiast

- LinkedIn: *(https://www.linkedin.com/in/etim-antai-a59328198/)*
- GitHub: *(https://github.com/Etim-Antai)*

---

## ⭐ Acknowledgements

This project was completed as part of the **DeepTech_Ready Data Science and Machine Learning Internship Program**, delivered in collaboration with:

- DeepTech_Ready
- 3MTT Nigeria
- Microsoft
- Data Science Nigeria (DSN)
- 8thGear® Hub & Venture Studio
