# -Implement-and-understand-simple-multiple-linear-regression.-
# Housing Price Prediction using Linear Regression

This project demonstrates a machine learning workflow to predict housing prices using Linear Regression. It includes data preprocessing, model training, and evaluation using scikit-learn.

##  Dataset

- The dataset is loaded from a compressed CSV file: `archive (9).zip`
- It contains various features related to houses (location, area, number of rooms, etc.)
- The target variable is `price`.

## Key Features

- **Pandas & NumPy**: For data manipulation and analysis  
- **Matplotlib**: For visualizations (optional in current code)  
- **Scikit-learn**:
  - `train_test_split`: To split the dataset into training and testing sets
  - `LinearRegression`: To build the regression model
  - Evaluation Metrics: `MAE`, `MSE`, `R² Score`

##  Model Training

- The dataset is preprocessed using `pd.get_dummies()` to handle categorical variables.
- Feature matrix `X` and target vector `y` are created.
- Data is split with 80% for training and 20% for testing.
- A `LinearRegression` model is trained on the training set.

## Model Evaluation

- The model is evaluated using:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **R² Score**: Indicates how well the predictions match actual values.


##  How to Run

1. Clone the repository
2. Unzip the dataset if needed and place it in the working directory
3. Run the Jupyter Notebook in any Python environment

