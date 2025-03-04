# House Price Prediction using Linear Regression

This repository contains a comprehensive implementation of a linear regression task aimed at predicting house prices based on several features. The project demonstrates the full machine learning pipeline—from data preprocessing and exploratory data analysis (EDA) to feature engineering, model training, evaluation, and predicting new data. Two implementations are provided: one using Scikit-Learn's built-in Linear Regression model, and another using a custom Gradient Descent approach.

## Project Overview

### Dataset
The dataset consists of the following features:
- **House_Age**
- **Num_Bedrooms**
- **Area_Sqft**
- **Distance_to_City_Center**
- **House_Price** (target variable)

### Tasks Covered
1. **Data Preprocessing and Exploration**
   - Load the dataset and handle missing values appropriately.
   - Visualize feature distributions and relationships with the target variable (House_Price).
   - Identify and handle outliers using statistical methods (e.g., the IQR method).

2. **Feature Engineering and Selection**
   - Normalize/scale numerical features to improve model performance.
   - Analyze feature correlations to identify the most significant predictors.
   - Create polynomial features to capture potential non-linear relationships.

3. **Model Training and Evaluation**
   - Split the dataset into training and testing sets (e.g., 80/20 split).
   - Train a Linear Regression model using Scikit-Learn.
   - Evaluate the model with performance metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.

4. **Implement Linear Regression using Gradient Descent**
   - Build a custom linear regression model from scratch using Gradient Descent.
   - Compare the performance of the custom implementation with Scikit-Learn's model.

5. **Predicting House Prices for New Data**
   - Develop a function that preprocesses new data and predicts house prices using the trained model.
   - Test predictions on unseen data to validate model performance.

## How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/linear-regression-house-price.git
   cd linear-regression-house-price
   ```

2. **Install Dependencies**
   Install the required packages using:
   ```bash
   pip install -r requirements.txt
   ```
   *(Make sure your Python version is 3.7 or higher.)*

3. **Run the Notebooks/Scripts**
   - Open the provided Jupyter Notebook (or Python scripts) to follow the step-by-step implementation.
   - Update file paths if necessary before running the code.

## Requirements

- Python 3.7+
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Scikit-Learn](https://scikit-learn.org/)
- (Optional) [Jupyter Notebook](https://jupyter.org/) for interactive analysis

## Discussion and Conclusion

The project emphasizes the importance of data preprocessing, proper feature engineering, and model tuning in achieving accurate predictions. By comparing the Scikit-Learn implementation with a custom Gradient Descent approach, we validate the robustness of our solution. Both models yield comparable results, reinforcing the effectiveness of the methodologies applied.

The repository serves as a practical guide for implementing linear regression in real-world scenarios, particularly for property valuation, and demonstrates how different techniques can be leveraged to solve regression problems.

---

Feel free to contribute, open issues, or suggest improvements. Enjoy exploring and enhancing the project!
