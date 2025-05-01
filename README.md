# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
COMPANY: CODTECH IT SOLUTIONS

NAME: PRAMIT KUMAR GUPTA

INTERN ID: CT04DA412

DOMAIN: DATA ANALYTICS

DURATION: 4 WEEKS

MENTOR: NELA SANTOSH

##Based on the analysis conducted across the three notebooks—House Pricing, Feature Engineering, and Feature Selection—this project focuses on a comprehensive data science pipeline for predicting house prices using the Ames Housing dataset. The methodology follows best practices in exploratory data analysis (EDA), feature engineering, and machine learning, with a strong emphasis on data preprocessing, transformation, and model interpretation. Below is a detailed summary of the tools, methods, and processes used:

Tools and Packages Used
The analysis employed Python's data science ecosystem, including the following core packages:

pandas and numpy: For data manipulation and numerical operations.

matplotlib and seaborn: For visualizations to understand feature distributions and relationships.

sklearn (Scikit-learn): For machine learning modeling and feature selection.

scipy.stats: For statistical computations.

statsmodels: For advanced statistical modeling.

missingno: For visualizing missing data.

xgboost and lightgbm: Gradient boosting algorithms used for regression modeling.

Feature-engine (inferred from methodology): For advanced feature transformations like imputation, encoding, and discretization.

Data Loading and Initial Exploration
The dataset is loaded from a CSV file (train.csv).

Initial inspection includes checking shape, head, and missing values.

Missing values are analyzed and visualized to understand their distribution and potential impact on target variable (SalePrice).

Variables are categorized into numerical, categorical, temporal, discrete, and continuous for tailored handling during feature engineering.

Exploratory Data Analysis (EDA)
Temporal variables (e.g., YearBuilt, GarageYrBlt) are examined in relation to the sale year (YrSold) to extract meaningful time differences.

Discrete and continuous numerical variables are separately analyzed for their relationship with SalePrice.

Categorical variables are grouped and visualized using bar plots and box plots to assess correlation with the target.

Distribution of the target variable (SalePrice) is plotted and log-transformed for normalization.

Feature Engineering
Key feature engineering techniques included:

Handling Missing Values:

Categorical features with nulls were imputed using mode or 'Missing' labels.

Numerical features were imputed using median values or zero, based on domain context.

Temporal Feature Transformation:

Calculated derived features like Age (difference between YrSold and construction-related year features).

Categorical Encoding:

Ordinal features were label-encoded based on domain knowledge (e.g., quality ratings).

One-hot encoding applied to nominal categorical variables.

Outlier Treatment:

Outliers were visualized using box plots and removed from the dataset for features with large deviations in SalePrice.

Feature Scaling:

Continuous variables were standardized using StandardScaler to improve model performance.

Feature Selection
Various feature selection methods were applied to reduce dimensionality and improve model generalization:

Univariate Selection (Chi-Square Test): Applied to identify important categorical variables.

Correlation Matrix: Heatmaps were used to visualize relationships and remove multicollinearity.

Recursive Feature Elimination (RFE): Applied using linear models to identify top contributing features.

Lasso Regularization: Used to shrink less important features’ coefficients to zero, aiding in sparse model creation.

Mutual Information: Evaluated to capture nonlinear dependencies between features and the target.

Modeling
Several regression models were explored, including:

Linear Regression: For baseline performance.

Ridge and Lasso Regression: To manage multicollinearity and perform embedded feature selection.

XGBoost and LightGBM: Used as high-performance ensemble learners, both tuned for optimized prediction.

Cross-validation: Employed using KFold and GridSearchCV to fine-tune model parameters and avoid overfitting.

Model Evaluation
Evaluation metrics included Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R² score.



Feature importance plots from tree-based models were used to interpret model decisions.

Conclusion
The notebooks comprehensively cover a full machine learning workflow tailored for regression problems, specifically housing price prediction. Through thorough EDA, strategic feature engineering, robust feature selection, and ensemble modeling, the analysis demonstrates how to extract meaningful insights and build a predictive pipeline from raw housing data. The consistent use of visualizations, statistical tests, and modeling best practices reflects a strong grasp of applied machine learning principles in real estate valuation.


## Output

![Image](https://github.com/user-attachments/assets/78e63656-bfb1-4607-a83b-4f9406e8d24c)
![Image](https://github.com/user-attachments/assets/8b88c37f-49c4-4939-8ccc-b068b9ec72de)
![Image](https://github.com/user-attachments/assets/fc0a4b58-c56b-4654-943a-34d9095f37f4)
![Image](https://github.com/user-attachments/assets/c3cd79dd-c028-4384-8ef5-6b4694b923fa)
![Image](https://github.com/user-attachments/assets/756ba3ab-54ef-4119-91d4-f21b077ba31b)
![Image](https://github.com/user-attachments/assets/3c279c76-abb9-4977-99bc-29c58de5a690)
![Image](https://github.com/user-attachments/assets/2fc4da1b-eb0c-474b-842d-f6a8819c8c72)
![Image](https://github.com/user-attachments/assets/c48d6b0c-992e-46b1-b62d-8fd67d53ad1a)
![Image](https://github.com/user-attachments/assets/3b29ea34-aaa4-4372-b885-b05555e9c4b1)
![Image](https://github.com/user-attachments/assets/3449130f-f126-4778-90d8-b9fcb6e76a8a)
![Image](https://github.com/user-attachments/assets/ad748364-c9e9-473a-a79a-575989df4b20)
![Image](https://github.com/user-attachments/assets/658ed845-6b36-49ae-acb0-94a7c6a913ab)
![Image](https://github.com/user-attachments/assets/ad8341c8-d415-48a2-ae53-79137411b754)
![Image](https://github.com/user-attachments/assets/9561d1e5-2fb4-483e-ac33-c2c81ba76318)
![Image](https://github.com/user-attachments/assets/0e625fb4-6860-45f2-b99c-9cf7b39ea164)
![Image](https://github.com/user-attachments/assets/e5bb1dfc-9551-4c96-a2f4-6ae1ee471f7d)
