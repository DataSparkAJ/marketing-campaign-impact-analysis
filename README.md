# Measuring the Impact of a Marketing Campaign on Sales Using Statistical Analysis

## 📌 Business Problem
A company launched a new marketing campaign and management wanted to know whether the campaign actually increased daily sales or whether any observed increase was due to random variation.  
This project analyzes sales data before and after the campaign to determine its real impact using statistical and analytical techniques.

---

## 📊 Dataset
The dataset contains daily sales data for 60 days:
- 30 days **before** the campaign  
- 30 days **after** the campaign  

Each record includes:
- **Day**
- **Sales**
- **Campaign status** (Before / After)

The data was generated to realistically simulate business sales behavior.

---

## 🛠 Methods Used
This project applies a complete data analytics workflow:

- Descriptive statistics (mean, standard deviation)
- Data grouping and comparison
- Hypothesis testing (two-sample t-test)
- p-value based decision making
- Confidence interval for sales increase
- Linear regression
- Model evaluation using R²

---

## 🔍 Analysis Performed

### 1. Exploratory Data Analysis
Sales before and after the campaign were summarized using mean, standard deviation, and grouped statistics to understand the initial differences.

### 2. Hypothesis Testing
- **Null Hypothesis (H₀):** The campaign did not change average daily sales  
- **Alternative Hypothesis (H₁):** The campaign increased average daily sales  

A two-sample t-test was used to test whether the difference in sales was statistically significant.

### 3. Confidence Interval
A 95% confidence interval was calculated to estimate how much the campaign increased daily sales.

### 4. Regression Analysis
Linear regression was used to analyze sales trends over time and to evaluate how well time explained changes in sales using R².

---

## 📈 Key Results

- **Average sales increase:** ₹210.97 per day  
- **95% Confidence Interval:** ₹113.39 to ₹308.56  
- **p-value:** < 0.001 (statistically significant)  
- **Regression slope:** Positive trend in sales  
- **R²:** 0.15 (time explains 15% of sales variation)

---

## 🧠 Conclusion
The statistical analysis shows that the marketing campaign had a **significant and positive effect** on daily sales.  
The campaign increased sales by approximately ₹211 per day, and we are 95% confident that the true increase lies between ₹113 and ₹309 per day.  
The hypothesis test confirmed this improvement is highly significant, and regression analysis showed a positive sales trend over time.

Based on this evidence, the marketing campaign can be considered **successful and worth continuing**.

---

## 🚀 Tools & Libraries
- Python  
- NumPy  
- Pandas  
- SciPy  
- scikit-learn  

---

## 📌 Author
This project was created as part of a data analytics learning journey to demonstrate how statistical analysis can be used to support real business decisions.
