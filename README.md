# Customer Churn Prediction

Predicting which bank customers are likely to leave using machine learning. This project helps businesses proactively retain customers by identifying churn risk before it happens.

## Problem Statement

Customer churn is one of the biggest challenges in banking. Acquiring a new customer costs 5–7x more than retaining an existing one. This project builds a classification model to flag at-risk customers so the business can intervene early.

## Dataset

The dataset (`bank.csv`) contains 10,000 records of bank customers with features including:
- Demographics: age, geography, gender
- Financial: credit score, balance, estimated salary
- Behavioural: number of products, tenure, credit card ownership, activity status

**Target variable:** `Exited` - whether the customer churned (1) or stayed (0)

## Project Workflow

1. **Exploratory Data Analysis** — Understanding distributions, correlations, and churn rates across different customer segments
2. **Data Preprocessing** — Handling categorical variables, feature scaling, and train/test split
3. **Model Building** — Training classification models to predict churn
4. **Evaluation** — Assessing model performance using accuracy, precision, recall, and confusion matrix

## Key Findings

- Customers from Germany had a significantly higher churn rate compared to France and Spain
- Customers with only one product and inactive accounts were most likely to churn
- Age was one of the strongest predictors - middle-aged customers (40–60) churned more

## Tools & Libraries

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data loading and manipulation |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Model training and evaluation |
| Jupyter Notebook | Development environment |

## Files

```
Customer-Churn-Prediction/
├── bank.csv              # Dataset
└── customer_churn.ipynb  # Main notebook with EDA and model
```

## How to Run

```bash
git clone https://github.com/210306105059/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook customer_churn.ipynb
```

## Results

The model achieved strong predictive performance on the test set, correctly identifying a significant portion of churning customers while keeping false positives low.

---
*Part of my data science portfolio. Feel free to raise an issue or suggest improvements!*
