# Chance of Admission Prediction Using Linear Regression

This project aims to predict the chance of admission to a graduate program based on various factors using linear regression analysis.

# Dataset

The dataset used for this project includes the following columns:
- GRE Score: Graduate Record Examination score (out of 340)
- TOEFL Score: Test of English as a Foreign Language score (out of 120)
- University Rating: Rating of the university's reputation (out of 5)
- SOP: Statement of Purpose strength (out of 5)
- LOR: Letter of Recommendation strength (out of 5)
- CGPA: Undergraduate GPA (out of 10)
- Research: Research experience (0 or 1)
- Chance of Admit: Probability of admission (ranges from 0 to 1)

# Library Packages

- pandas
- scikit-learn
- numpy
- matplotlib

# Steps:

**1. Data Preprocessing**
- Load the dataset.
- Handle missing values by imputing or removing them.
- Normalize or standardize the data if necessary.
  
**2. Feature Selection**
- Analyze the features and their correlation with the target variable.
- Select features that contribute the most to predicting the chance of admission.
  
**3. Model Training**
- Split the data into training and testing sets.
- Train the linear regression model using the training set.
- Tune hyperparameters to improve model performance.
  
**4. Model Evaluation**
- Use the testing set to evaluate the model.
- Calculate metrics such as Mean Squared Error (MSE) or R-squared.
- Visualize the predicted vs. actual chance of admission.

# Conclusion

Linear regression effectively predicts the chance of admission based on applicant data, providing valuable insights for prospective students and academic institutions alike.
