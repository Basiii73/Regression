# Regression Assignment

## Objective
This assignment evaluates the understanding of regression techniques by applying them to the California Housing dataset.

## Dataset
We use the California Housing dataset available in the `sklearn.datasets` library. It contains various house features along with their median prices.

## Steps Implemented

### 1. Data Loading & Preprocessing
- Loaded the dataset using `fetch_california_housing()`.
- Converted it into a Pandas DataFrame.
- Checked for missing values and performed feature scaling using `StandardScaler()`.

### 2. Regression Models Implemented
The following regression models were implemented:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **Support Vector Regressor (SVR)**

Each model was trained using the preprocessed data and evaluated.

### 3. Model Evaluation
The models were evaluated using the following metrics:
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R-squared Score (R²)**

The best and worst performing models were identified based on R² scores.

### 4. Results Comparison
- A comparison plot of R² scores was created using Seaborn.
- The best and worst performing models were highlighted.

## How to Run the Code
1. Clone this repository:
   ```bash
   git clone <repo_link>
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run all cells.

## Submission
This project was submitted as a Jupyter Notebook along with this README file.

---
### Author
Abdul Basith

