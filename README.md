# supervised-learning

Homework, week 19

This model uses two datasets prepared externally showing credit risk. The model is used to predict whether an individual presents a risk.  
The model is trained using data from 2019, with data from the first quarter of 2020 used to test the model's predictions.

Steps used were:
1. Generate the data using an established technique
2. Import data into Jupyter/Pandas
3. Categorise data using get_dummies
4. Add required additional columns for consistency between datasets
5. Fit models
6. Predict classes and check model performance
7. Scale the datasets
8. Fit models
9. Predict classes and check model peformance

Models used are:
- Logistic Regression
- Random Forest Classifier
- Random Forest Regressor

The work showed that none of the models were particularly good at predicting credit risk in the 2020 data. This suggests that there are additional factors changing credit risk in 2020 which are not covered in the dataset for 2019.