# House Price Prediction using Linear Regression

This project implements a linear regression model to predict house prices based on various features. The dataset contains information such as price, area, number of bedrooms, bathrooms, and other amenities.

## Steps to Run the Project

### 1. Data Collection
- Upload your CSV dataset containing the following columns:
  - `price`
  - `area`
  - `bedrooms`
  - `bathrooms`
  - `stories`
  - `mainroad`
  - `guestroom`
  - `basement`
  - `hotwaterheating`
  - `airconditioning`
  - `parking`
  - `prefarea`
  - `furnishingstatus`

### 2. Data Exploration and Cleaning
- Check for missing values in the dataset.
- Fill missing values for numerical columns with the mean of the column.

### 3. Feature Selection
- Identify categorical columns and convert them to numerical values using one-hot encoding.
- The final dataset should consist of numerical features only, suitable for model training.

### 4. Model Training
- Split the dataset into training (80%) and testing (20%) sets.
- Standardize the features using `StandardScaler` to improve model performance.
- Train a linear regression model using the training data.

### 5. Model Evaluation
- Predict house prices on the test set.
- Evaluate the model performance using the following metrics:
  - Mean Squared Error (MSE)
  - R-squared value

### 6. Visualization (Optional)
- Create visualizations (e.g., scatter plots) to compare predicted and actual prices.

## Requirements
Make sure to install the necessary libraries:
```bash
pip install pandas scikit-learn matplotlib seaborn
