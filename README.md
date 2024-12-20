# NBA Player Performance Prediction (Regression Analysis)

This project aims to predict the points scored by NBA players based on various player attributes and performance statistics. We use regression models, including **Linear Regression** and **Ridge Regression**, to predict the target variable `pts` (points scored by the player) based on features such as rebounds (`reb`), assists (`ast`), and usage percentage (`usg_pct`).

## **Project Structure:**
The project contains the following components:
- **Data Preprocessing**
- **Feature Selection**
- **Model Training**
- **Model Evaluation**
- **Model Comparison**

## **Tasks in this Project:**

### 1. **Data Preprocessing**
   - **Task**: Clean the dataset, handle missing values, and prepare the data for training.
   - **Description**: This step involves removing irrelevant features, dropping missing values, and preparing the dataset for training. Only relevant numerical features are retained for the model.

### 2. **Feature Selection**
   - **Task**: Identify and select the most important features.
   - **Description**: Based on correlation analysis, features that have a significant relationship with the target variable `pts` (points scored) are selected.

### 3. **Model Training**
   - **Task**: Train two regression models (Linear Regression and Ridge Regression).
   - **Description**: The dataset is split into training and testing sets. Both models are trained using the training data, and predictions are made on the test data.

### 4. **Model Evaluation**
   - **Task**: Evaluate the performance of the models.
   - **Description**: The models are evaluated based on the following metrics:
     - **Mean Squared Error (MSE)**: Measures the average squared difference between predicted and actual values.
     - **Mean Absolute Error (MAE)**: Measures the average absolute difference between predicted and actual values.
     - **R-Squared (R²)**: Represents the proportion of variance in the target variable explained by the model.

### 5. **Model Comparison**
   - **Task**: Compare the performance of the Linear Regression and Ridge Regression models.
   - **Description**: A comparison is made between the two models to determine which performs better in terms of prediction accuracy and metrics.

## **How to Run the Code:**

### Prerequisites:
- Python 3.8+
Before running the code, ensure you have the following libraries installed:
- `pandas` (for data handling)
- `numpy` (for numerical operations)
- `scikit-learn` (for machine learning models and evaluation)
- `matplotlib` and `seaborn` (for data visualization)

You can install the required libraries using the following command:
```bash
pip install -r requirements.txt
