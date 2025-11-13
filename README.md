# Understanding Salary Determinants Through Machine Learning

## 📖 Overview
This project investigates the determinants of employee salaries using machine learning.  
It analyzes how demographic and professional factors—such as **age, education, gender, years of experience, job title,** and **location**—influence salary outcomes.  

The objective is to:
- Predict an individual's salary with high accuracy.
- Identify which variables are the strongest predictors.
- Explore pay equity and differences across gender, education, and location.
- Apply and compare regression and classification models.

## ⚙️ Project Stages
1. **Data Collection & Understanding** — Obtain dataset from Kaggle.  
2. **Data Cleaning & Preprocessing** — Handle missing values, outliers, encoding.  
3. **Exploratory Data Analysis (EDA)** — Identify trends, correlations, and distributions.  
4. **Feature Engineering** — Create meaningful variables and transformations.  
5. **Model Development** — Apply Linear Regression, Random Forest, and Neural Network models.  
6. **Evaluation** — Compare models using RMSE, R², Accuracy (for classification).  
7. **Interpretation & Visualization** — Explain results with feature importance and SHAP values.  
8. **Reporting & Presentation** — Summarize findings in HTML/PDF reports and a video walkthrough.

## 📊 Dataset
**Source:** [Salary Prediction Dataset – Kaggle](https://www.kaggle.com/code/dimassp1/salarypreds-91-pytorch)  
**Records:** 1,047  
**Attributes:**
| Attribute | Type | Description |
|------------|------|-------------|
| Age | Integer | Age of the individual |
| Gender | Categorical | Male, Female, Other |
| Education | Categorical | Highest educational attainment |
| YearsExperience | Integer | Total years of work experience |
| JobTitle | Categorical | Job title |
| Location | Categorical | City or region |
| Salary | Float | Annual salary (USD) |

## 📈 Initial Insights
- Average Salary: **$72,300**  
- Median Salary: **$69,000**  
- Top Job Title: **Software Engineer**  
- Correlation with Salary:  
  - Experience: **r = 0.61**  
  - Education: **r = 0.48**  
  - Age: **r = 0.33**  
  - Gender: **r = -0.08**

## 🧠 Research Questions
1. How accurately can salary be predicted based on age, education, experience, and job title?  
2. Which independent variable is the strongest predictor?  
3. Does education significantly impact salary when experience and job title are controlled?  
4. Is there a measurable gender pay gap?  
5. How does salary vary across regions?  
6. Which ML model provides the best predictions?  
7. Can a model classify individuals likely to earn over $50,000?

## 🧮 Tools & Libraries
- **Python 3.11**
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, shap, xgboost, pytorch
- **Environment:** Jupyter Notebook / VS Code

