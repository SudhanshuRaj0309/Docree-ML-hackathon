# Docree-ML-hackathon
1. Import necessary libraries and modules.
2. Load the training dataset.
3. Perform data preprocessing and feature engineering.
4. Split the data into train and test sets.
5. Train a Random Forest Classifier model on the training data.
6. Evaluate the model's performance on unseen data.
7. Save the trained model.
8. Load the test dataset.
9. Perform data preprocessing on the test dataset.
10. Make predictions on the test dataset using the saved model.
11. Create a submission file with the predictions.

Feature Engineering:
1. Extract unique keywords from the training dataset.
2. Create dummy variables based on the keyword list.
3. Drop redundant columns.
4. Handle missing values.
5. Created dummy variables for the top 100 most frequent cities in USERCITY and all of the values in PLATFORM_ID 

Tools Used:
1. Python programming language.
2. Pandas library for data manipulation and preprocessing.
3. Scikit-learn library for training the Random Forest Classifier and evaluating the model's performance.
4. Joblib library for saving and loading the trained model.
