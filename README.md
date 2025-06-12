🏙️ Buenos Aires Real Estate Price Predictor

A data science project that builds a machine learning pipeline to predict real estate prices in Buenos Aires using Ridge Regression. This project includes end-to-end data processing, model tuning to reduce overfitting, and a dynamic dashboard for user interaction.


 📌 Objectives

1. Develop a regression model using `scikit-learn` to predict property prices.
2. Build a preprocessing pipeline to handle missing values and encode categorical variables.
3. Enhance model performance by diagnosing and reducing overfitting.
4. Create an interactive tool using `ipywidgets` to predict prices dynamically.


 🧰 Technologies Used

| Tool/Library          | Purpose                                               |
| --------------------- | ----------------------------------------------------- |
| Pandas            | Data wrangling, feature extraction, and filtering     |
| Scikit-learn     | Model creation (Ridge Regression), pipelines, metrics |
| Seaborn           | Correlation visualization and exploratory analysis    |
| Category Encoders | Encoding neighborhood categorical features            |
| Ipywidgets       | Building an interactive prediction UI                 |
| Matplotlib       | Additional visualizations                             |



 🗂️ Dataset

Buenos Aires Real Estate Dataset:
The dataset includes property listings with features like surface area, price, number of rooms, and neighborhood.


🔍 Key Features

 📊 Feature correlation analysis to detect multicollinearity.
 🔄 Preprocessing pipeline with:

   `SimpleImputer` for missing data
   `OneHotEncoder` for categorical variables using `category_encoders`
 📉 Model optimization using Ridge Regression to manage overfitting.
 🧪 Evaluation metric: Mean Absolute Error (MAE).
 🧮 Interactive dashboard with adjustable inputs for live predictions.



 📈 Model Overview

Model: Ridge Regression
Pipeline Components:
Imputation
One-hot encoding
Model fitting
Performance: Evaluated using Mean Absolute Error (MAE)

## 🙌 Acknowledgements

* Buenos Aires Open Data Portal (for dataset)
* scikit-learn, pandas, seaborn, ipywidgets communities

