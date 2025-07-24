# Health-Insurance Charges Prediction 
This project invollves predicting individual medical insurance charges usiing regressioon techniques. I expplore and ccompare Linear Regression and Random Forest Regressor, including feature engineering, data preprocessing and model evaluation.

<img width="1200" height="800" alt="Health Insurance" src="https://github.com/user-attachments/assets/0fd0bce9-7eb4-45a7-b5a8-e09b8cd30a4c" />



## Dataset
The dataset includes the following columns:

 - age: Age of the individual
  
 - sex: Gender (male, female)
  
 - bmi: Body Mass Index
  
 - children: Number of children
  
 - smoker: Smoking status (yes, no)
  
 - region: Residential region in the US
  
 - charges: Individual medical costs billed by health insurance
  
## Steps Performed
1. Data Preprocessing

- Handled missing values and standardized numeric fields.

- Performed encoding on categorical features.

- Added new features like:

bmi_category, age_group

2. EDA

- Visualized distributions and relationships between features.

- Explored correlations and feature-target relationships.

3. Modeling

- Linear Regression (with and without log transformation)

- Random Forest Regressor

Performance metrics:

- Mean Absolute Error (MAE)

- Root Mean Squared Error (RMSE)

- R-squared (R²)

4. Model Interpretation

Feature importance visualization for Random Forest.

## 🏁 Results Summary
1. Linear Regression: MAE= $4177, RMSE = ~ 5956, R-squared score = 0.81
2. After Log transform: MAE = $3756, RMSE = ~ 7198, R-squared score = 0.7180
3. Random Forest: MAE = 2614, RMSE = ~4692, R-squared score = 0.8802

✅ Random Forest outperforms Linear Regression in all evaluation metrics.


## 🚀 How to Run
1. Clone this repository or download the notebook.

2. Make sure insurance.csv is in the same directory.

3. Run the cells sequentially in project.ipynb using Jupyter Notebook or Jupyter Lab.

🧠 Author
Edna Juliet Maina
Aspiring Data Analyst | Python & Machine Learning Enthusiast

Reach out via GitHub or LinkedIn
