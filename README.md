## Player Playtime Analysis (KNN Regression)

This project explores whether demographic factors such as age and experience
can explain player playtime behavior. Exploratory data analysis (EDA) was
conducted to examine distributions, outliers, and variable relationships,
followed by non-linear modeling using K-Nearest Neighbors (KNN) regression.

### Key Findings
- Playtime is highly right-skewed, with most players exhibiting very short sessions.
- Neither age nor experience demonstrates meaningful predictive power for playtime.
- KNN regression produces near-flat predictions with large relative error,
  suggesting demographic variables alone are insufficient to explain playtime behavior.

### Methods
- Exploratory Data Analysis (EDA)
- Outlier handling (0–5 hour range)
- KNN Regression with GridSearchCV
- Model evaluation using RMSPE

### Tools
Python, pandas, scikit-learn, Altair
