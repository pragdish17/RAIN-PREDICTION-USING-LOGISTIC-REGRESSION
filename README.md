# RAIN-PREDICTION-USING-LOGISTIC-REGRESSION
Predicting whether it will rain tomorrow in Australia using historical weather data and a Logistic Regression model. This project includes full data preprocessing, feature scaling, one-hot encoding, model training, evaluation, and saving/loading functionality.

# DATASET
The dataset used is from Kaggle: Weather Dataset Rattle Package. It contains historical weather observations from multiple locations in Australia.

- File: weatherAUS.csv
- Target Column: RainTomorrow
- Features: Temperature, Humidity, Rainfall, Wind, Pressure, Cloud Cover, etc.

# FEATURES
- Load dataset and handle missing values
- Train-validation-test split based on years
- Numeric feature scaling using MinMaxScaler
- Categorical feature encoding using One-Hot Encoding
- Logistic Regression for binary classification
- Model evaluation with accuracy and confusion matrix
- Feature importance visualization
- Predicting rain for a new single input
- Saving and loading trained model, imputer, scaler, and encoder

# Model Training and Evaluation
The notebook/script includes:

- Train, validation, and test splits
- Handling missing numeric and categorical values
- Scaling numeric columns
- One-hot encoding categorical columns
- Training a Logistic Regression model
- Visualizing feature importance
- Evaluating performance with accuracy and confusion matrix.

Expected accuracy: ~85% on training, ~84% on test/validation sets.

