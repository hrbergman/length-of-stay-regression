### Length-of-Stay Drivers with Multiple Linear Regression
**Tools: Python, statsmodels, scikit-learn, pandas, Seaborn** | M.S. Data Analytics Project (D208 - Predictive Modeling)

A regression analysis identifying which patient characteristics and comorbidities most influence how long patients stay in the hospital.
 
- Wrote reusable Python functions to automate feature selection, iteratively removing variables above a VIF threshold of 5 and then eliminating predictors with p-values above 0.05
- Compared the initial and reduced models using AIC and BIC, confirming a simpler model with better fit
- Identified admission type, complication risk, diabetes, back pain, high blood pressure, stroke history, and daily charges as key factors
- Documented assumptions and limitations, including multicollinearity, outlier sensitivity, and the difference between correlation and causation

[Documentation](https://github.com/hrbergman/postgresql-customer-services-query/blob/main/postgresql-customer-services-query/data-acquisition-documentation.pdf)
| 
[Video Presentation](https://youtu.be/jKOE0cG68rc)
