# Titanic-Task-2
## 🛠 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📌 Objectives

- Generate summary statistics (mean, median, std, etc.)
- Visualize distributions, outliers, and relationships
- Understand feature relevance and patterns
- Identify skewness, correlation, and multicollinearity

---

## 📊 Key Visualizations & Insights

### 1. **Survival Distribution**
- More passengers **did not survive** than survived.

### 2. **Sex vs Survival**
- **Female passengers had a much higher survival rate** than males.
- Clear indication of the "women and children first" policy.

### 3. **Pclass vs Survival**
- Passengers in **1st class had the highest survival rate**, followed by 2nd and then 3rd.
- Socioeconomic status and cabin location likely influenced survival.

### 4. **Age Distribution**
- Age is **right-skewed**, with most passengers in the 20–40 range.
- Children had a relatively higher survival rate.

### 5. **Fare Distribution**
- **Highly skewed** with extreme outliers.
- Higher fares are associated with higher survival, mostly 1st class.

### 6. **Embarked vs Survival**
- Passengers from **Cherbourg (C)** had the highest survival rate.
- Likely more 1st class passengers boarded there.

### 7. **SibSp and Parch vs Survival**
- Survival was higher for passengers with **1–2 siblings/spouses** or **1–3 parents/children**.
- Indicates family presence helped survival.

### 8. **Correlation Matrix**
- `Fare` and `Pclass` show significant correlation with `Survived`.
- No multicollinearity detected (no pair has |correlation| > 0.8).

---

## 📈 Statistical Summary

- **Missing values** in `Age`, `Cabin`, and `Embarked`
- `Age` and `Fare` are **right-skewed**
- Use of boxplots revealed outliers in fare and age
- Features like `Sex`, `Pclass`, and `Fare` are strong predictors for survival

---
## ✅ Conclusion

EDA helped uncover patterns related to survival, especially the importance of gender, class, fare paid, and family presence. 
These insights are essential for building accurate predictive models and for understanding the human aspects behind the data.
