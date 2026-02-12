# Stock Price vs Fundamental Analysis
A regression-based financial analysis project examining the relationship between stock prices and company fundamentals.

---

##  Objective

To evaluate whether corporate fundamentals such as:

- Sales Growth
- EBITDA Growth
- EBITDA Margin Change
- PAT Growth
- PAT Margin Change



---

##  Methodology

1. Data Cleaning
2. Descriptive Statistics
3. Outlier Detection (Z-score)
4. Normality Testing (Shapiro-Wilk)
5. Multicollinearity Testing (VIF)
6. Correlation Analysis
7. Simple Linear Regression
8. Multiple Regression
9. Scatter Plot Visualization

---

##  Key Insights

- Extremely small sample size (n = 5) limits statistical inference.
- Severe multicollinearity observed among profitability variables.
- Multiple regression overfits (R² = 1.0).
- Sales Growth shows moderate explanatory power in simple regression.

---

## Limitations

- Cross-sectional sample size is very small.
- Results should not be interpreted as statistically robust.

---

##  Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels

---



## Outputs 
- correlation heatmap
<img width="1000" height="800" alt="correlation_heatmap" src="https://github.com/user-attachments/assets/c98ba453-545a-4452-a2b7-a31b1e7622ac" />
-r-squared comparison
<img width="1200" height="600" alt="r_squared_comparison" src="https://github.com/user-attachments/assets/2cdc85c1-f1bd-4f5a-8539-0d48ec518dc3" />
- stock price (dependent) vs the same set of 5 fundamental variables (sales growth, ebitda margin change, ebitda growth, pat growth, pat margin change)
<img width="800" height="600" alt="scatter_EBITDA_Growth" src="https://github.com/user-attachments/assets/eb6cf8ae-aa15-4b67-8472-5d881c881452" />
<img width="800" height="600" alt="scatter_EBITDA_Margin_Change" src="https://github.com/user-attachments/assets/8124c6c5-61e6-47b2-a7a8-0401764c1150" />
<img width="800" height="600" alt="scatter_PAT_Growth" src="https://github.com/user-attachments/assets/54f8efe9-9d2b-42ea-b490-3892399f6280" />
<img width="800" height="600" alt="scatter_PAT_Margin_Change" src="https://github.com/user-attachments/assets/39552e03-4e80-43a7-972d-ee0be97f5e28" />
<img width="800" height="600" alt="scatter_Sales_Growth" src="https://github.com/user-attachments/assets/282cf04e-3c20-4c5b-8943-c293aa80b82e" />








---

##  Author

Thanmayee
