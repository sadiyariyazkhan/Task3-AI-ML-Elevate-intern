# Task3-AI-ML-Elevate-intern
# 🧮 Task 3: Linear Regression

## 🎯 Objective
Implement and understand **Simple & Multiple Linear Regression** using Scikit-learn, Pandas, and Matplotlib.

---

## ⚙️ Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🚀 Steps Performed
1. Imported and preprocessed the dataset.
2. Split data into **training** and **testing** sets (80–20).
3. Fitted **Linear Regression** using `sklearn.linear_model.LinearRegression`.
4. Evaluated performance using **MAE**, **MSE**, and **R² Score**.
5. Plotted regression line and interpreted coefficients.

---

## 📊 Results Summary

| Model | MAE | MSE | R² Score |
|--------|------|--------|-----------|
| Simple Linear Regression | 342198.45 | 3.68 × 10¹² | 0.2729 |
| Multiple Linear Regression | 278980.23 | 1.75 × 10¹² | 0.6529 |

✅ Multiple Linear Regression performed better with higher R² (≈0.65).

---

## 🖼️ Visualizations
- Regression Line: shows relationship between **area** and **price**
- Residual Plot: checks model errors and linearity assumption

---

## 🧠 Interview Questions & Answers

**1️⃣ What assumptions does linear regression make?**
- Linearity between independent & dependent variables  
- Homoscedasticity (equal variance of errors)  
- No multicollinearity  
- Errors are normally distributed  
- Independence of observations  

**2️⃣ How do you interpret coefficients?**  
Each coefficient shows how much the target variable changes when that feature increases by one unit, keeping others constant.

**3️⃣ What is R² score and its significance?**  
R² shows how much variance in the target variable is explained by the model. Higher R² means a better fit.

**4️⃣ When would you prefer MSE over MAE?**  
Use **MSE** when you want to penalize larger errors more strongly.

**5️⃣ How do you detect multicollinearity?**  
By checking **correlation matrix** or using **VIF (Variance Inflation Factor)**.

**6️⃣ What is the difference between simple and multiple regression?**  
- **Simple:** One independent variable  
- **Multiple:** More than one independent variable  

**7️⃣ Can linear regression be used for classification?**  
No, it’s meant for continuous output; classification requires models like logistic regression.

**8️⃣ What happens if regression assumptions are violated?**  
The model becomes unreliable — coefficients and predictions can be biased or invalid.

---

## 🧑‍💻 Author
**Name:** Sadiya Riyaz Khan  
**Task:** 3 — Linear Regression  
**Dataset:** Housing.csv  
**Tools:** Scikit-learn, Pandas, Matplotlib  

---
