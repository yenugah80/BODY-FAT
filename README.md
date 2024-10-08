1. Data Loading and Preprocessing:

 Data Information: The dataset contains 252 entries with 14 columns. All columns have nonnull values, indicating no missing data.
 Summary Statistics: The summary statistics provide insights into the distribution of each feature, including measures like mean, standard deviation, min, and max values.
 Missing Values: There are no missing values in the dataset.
 Independent Variables (X): The features include 'Density', 'Age', 'Weight', 'Height', 'Neck', 'Chest', 'Abdomen', 'Hip', 'Thigh', 'Knee', 'Ankle', 'Biceps', 'Forearm', and 'Wrist'.
 Dependent Variable (y): The target variable is 'BodyFat'.

 2. Model Training:

 TrainTest Split: The dataset is split into training (70%) and testing (30%) sets.
 Model Initialization: A Linear Regression model is initialized.
 Model Training: The model is trained using the training data.
 Model Coefficients and Intercept: The model's coefficients (slopes) and intercept are displayed, indicating the relationship between the features and the target variable.

 3. Evaluation using Mean Squared Error (MSE):

 Predictions: The model makes predictions on the test set.
 Evaluation Metrics:
 Mean Squared Error (MSE): 0.6257  Indicates the average squared difference between the actual and predicted values.
 Mean Absolute Error (MAE): 0.5403  Represents the average absolute difference between the actual and predicted values.
 Root Mean Squared Error (RMSE): 0.7910  The square root of MSE, providing error in the same units as the target variable.
 Rsquared (R²): 0.9879  Indicates that approximately 98.79% of the variance in the target variable is explained by the model.

Overall, the model demonstrates a high level of accuracy with low error metrics and a high Rsquared value, suggesting that it effectively predicts body fat percentage based on the given features.
