# 🏥 Insurance Premium Prediction (ML Project)

## 📌 Overview
This project predicts **medical insurance charges (premiums)** using the popular `insurance.csv` dataset.  
The goal is to analyze how factors such as **age, BMI, number of children, smoking status, sex, and region** influence insurance costs, and to build a regression model that can estimate premiums for new applicants.  

## 🔧 Tech Stack
- Python
- Pandas, NumPy
- Seaborn, Plotly, Matplotlib
- Scikit-Learn (Linear Regression, preprocessing)

## 🚀 Project Workflow
1. **Data Exploration (EDA)**  
   - Distribution of features (age, BMI, charges, etc.)  
   - Relationship analysis (age vs charges, smoker vs charges, etc.)  
   - Correlation heatmaps  

2. **Data Preprocessing**  
   - Encoded categorical variables (`sex`, `smoker`, `region`)  
   - Scaled numerical features (`age`, `bmi`, `children`)  

3. **Modeling**  
   - Implemented **Linear Regression** for predicting insurance charges  
   - Separate analysis for **smokers vs non-smokers**  
   - Extracted feature weights to identify the most influential factors  

4. **Evaluation**  
   - Metrics: RMSE, MAE, R² Score  
   - Compared predictions vs actual values  
   - Found smoking to be the strongest predictor of higher premiums  

5. **Premium Prediction Function**  
   - Built a function to estimate premium for **new applicants** given their details  

## 📈 Results
- RMSE ≈ *X* (replace with your model’s result)  
- Key factors influencing premium: **smoking, BMI, and age**  
- The model successfully predicts insurance charges with reasonable accuracy  

## 📝 Conclusion
This project demonstrates how **Machine Learning regression models** can be applied to real-world problems such as insurance pricing.  
It can be extended with more advanced models (Ridge, Lasso, Decision Trees, XGBoost) for improved performance.  

---

