# Loan Risk Analysis using Statistics and Probability (Python)

## Overview

This project analyzes a loan application dataset using Python. It applies statistical analysis, probability concepts, data visualization, and basic linear algebra techniques to understand customer behavior and loan default patterns.

---

## Project Objective

The objective of this project is to:

- Analyze financial data using statistical measures  
- Evaluate loan default probabilities  
- Understand data distribution and trends  
- Apply linear algebra concepts for similarity analysis  
- Generate insights for risk assessment  

---

## Dataset Description

The dataset contains 5000 records with the following features:

- Customer_ID  
- Age  
- Income  
- Loan_Amount  
- Credit_Score  
- Loan_Term (months)  
- Default_Status (Yes/No)  

---

## Tools and Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- SciPy  

---

## Analysis Performed

### Central Tendency and Dispersion

- Calculated mean, median, and mode of Income  
- Calculated range, variance, and standard deviation of Loan_Amount  

Purpose: Understand distribution and variability of financial data  

---

### Probability and Events

- Computed probability of loan default  
- Created contingency table (Default_Status vs Credit Score category)  
- Calculated conditional probability  

Purpose: Analyze risk and likelihood of defaults  

---

### Distribution and Visualization

- Histogram of Credit Score with Gaussian curve  
- Skewness and kurtosis of Loan Amount  
- Q-Q plot for Income  

Purpose: Understand data distribution and normality  

---

### Linear Algebra Application

- Represented customers as vectors [Income, Loan_Amount]  
- Calculated dot product  
- Computed L2 norm (vector magnitude)  
- Found angle between vectors  

Purpose: Measure similarity between customers  

---

## Key Insights

- Customers with low credit scores are more likely to default  
- Income distribution is balanced around the mean  
- Loan amounts show moderate variation  
- High credit score customers have lower default risk  
- Majority of customers do not default  

---

## Use Cases

- Loan risk analysis  
- Credit scoring systems  
- Financial data analysis  
- Academic and portfolio projects  

---

## Limitations

- Static dataset  
- No predictive modeling  
- Limited feature engineering  

---

## Future Improvements

- Apply machine learning models (Logistic Regression)  
- Build loan default prediction system  
- Use real-world datasets  
- Add dashboard visualization  

---

## How to Run

1. Open Jupyter Notebook  
2. Load dataset (loan_Application.csv)  
3. Run all cells  
4. View outputs and visualizations  

---

## Conclusion

This project demonstrates how statistical analysis, probability, and linear algebra can be applied to financial datasets. It provides valuable insights for understanding loan risk and customer behavior.
