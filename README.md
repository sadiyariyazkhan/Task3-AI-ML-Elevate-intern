# Task3-AI-ML-Elevate-intern
# 🏡 Task 3: Linear Regression — House Price Prediction

## 🎯 Objective
Implement and understand **simple and multiple linear regression** using the Housing dataset.

---

## 🧰 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Dataset Description
**Dataset Name:** `Housing.csv`  
The dataset contains housing features such as:
- Area (sq. ft.)
- Bedrooms
- Bathrooms
- Stories
- Parking
- Furnishing status
- And other binary indicators like mainroad, guestroom, etc.

**Target Variable:** `price`  
Goal: Predict the house price based on the above independent features.

---

## 🔍 Steps Performed

### 1️⃣ Data Import & Exploration
- Loaded dataset using pandas.
- Checked for missing values and data types.
- Explored categorical and numerical columns.
- Visualized key distributions (bedrooms, bathrooms, stories, etc.).

### 2️⃣ Data Preprocessing
- Label encoded categorical features (`mainroad`, `guestroom`, `basement`, etc.).
- Dropped unimportant column: `hotwaterheating`.
- Feature-target split: `X` = independent variables, `y` = price.
- Train-test split: 80% training, 20% testing.

### 3️⃣ Model Training
- Used **LinearRegression()** from `sklearn.linear_model`.
- Trained model on training data.

### 4️⃣ Model Evaluation
Evaluated model on the test set using:
- **Mean Absolute Error (MAE)** = 730364.5450  
- **Mean Squared Error (MSE)** = 814863259975.9052  
- **R² Score** = 0.7604  

✅ **Interpretation:**  
The model explains **~76% of the variance** in house prices — fairly good for a simple regression model.

### 5️⃣ Visualization
- Plotted **Actual vs Predicted Prices** using scatter plot.
- Regression line added for model interpretation.

---

## 📈 Model Coefficients

| Feature | Coefficient |
|----------|--------------|
| area | 232.1630 |
| bedrooms | 142975.2255 |
| bathrooms | 942811.2639 |
| stories | 480787.6433 |
| mainroad | 531231.5658 |
| guestroom | 224627.9273 |
| basement | 324868.6188 |
| airconditioning | 816201.0029 |
| parking | 322459.2740 |
| prefarea | 617706.6612 |
| furnishingstatus | -212354.6425 |

**Intercept:** 71403.1306

---

## 🧮 Example Prediction

**Input:**  
`[6000, 3, 2, 2, 1, 0, 0, 1, 1, 1, 1]`

**Predicted Price:** 💰 `$6,815,748.22`

---

## 💡 Key Learnings
- Linear regression helps estimate continuous outcomes.
- Coefficients represent the impact of each variable on price.
- R² is used to evaluate goodness of fit.
- Encoding categorical features is crucial for regression models.

---

## 🧠 Interview Questions & Answers

**1️⃣ What assumptions does linear regression make?**
- Linearity between predictors and target.
- Independence of errors.
- Homoscedasticity (constant variance of residuals).
- Normal distribution of residuals.
- No multicollinearity.

**2️⃣ How do you interpret coefficients?**  
Each coefficient shows how much the target variable changes when that feature increases by one unit, holding others constant.

**3️⃣ What is R² score and its significance?**  
It indicates how well the model explains variability in the target variable. Closer to 1 = better fit.

**4️⃣ When would you prefer MSE over MAE?**  
When you want to penalize large errors more severely — MSE squares the errors.

**5️⃣ How do you detect multicollinearity?**  
Using **VIF (Variance Inflation Factor)** or correlation heatmaps.

**6️⃣ Difference between simple and multiple regression?**  
Simple = one independent variable; Multiple = two or more.

**7️⃣ Can linear regression be used for classification?**  
No, it predicts continuous values. For classification, use logistic regression.

**8️⃣ What happens if you violate regression assumptions?**  
Model predictions become unreliable, biased, or inconsistent.

---

## 📁 Repository Contents
- `Task3_Linear_Regression.ipynb` — Code file
- `Housing.csv` — Dataset used
- `README.md` — Summary report

---

## 📤 Submission
After uploading to GitHub, paste your repository link in the submission form.

---
