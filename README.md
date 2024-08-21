# Customer-Churn
This project focuses on predicting customer churn based on various features such as phone service, internet service, and customer demographics. The goal is to identify factors that influence churn and build a model to predict which customers are likely to churn.

## Project Structure
- **Data Cleaning and Preprocessing**:
  - Loaded the dataset and checked the structure, including data types and statistics using functions like `head()`, `info()`, `shape`, and `describe()`.
  - Handled missing values by imputing the mean where necessary.
  - Removed unnecessary columns (e.g., Customer ID).
  - Checked for and confirmed the absence of outliers.

- **Exploratory Data Analysis (EDA)**:
  - Visualized features like PhoneService, InternetService, MultipleLines, StreamingTV, gender, and Dependents to understand their influence on customer churn.
  
- **Model Development**:
  - Built a logistic regression model using scikit-learn to predict customer churn.
  - Evaluated the model using various performance metrics such as accuracy, precision, recall, and F1 score.

## Model Evaluation
The model was evaluated using the following metrics:

- **Accuracy**: 
  - The percentage of correct predictions out of all predictions made.
  
- **Precision**: 
  - Measures the accuracy of positive predictions (customers who churn).

- **Recall**: 
  - Measures the model's ability to identify all actual positive cases (customers who churn).

- **F1 Score**: 
  - The harmonic mean of precision and recall, providing a balanced measure of the two.

## Key Insights
1. **Phone Service**: Customers with phone service influence churn more than those without.
2. **Internet Service**: Fiber optics customers influence churn more than other internet services.
3. **Gender**: Churn is balanced across male and female customers.
4. **Dependents**: Customers without dependents are more likely to churn compared to those with dependents.

## How to Run the Project
1. Install the necessary libraries listed in `requirements.txt`.
2. Load the dataset and run the notebook to execute data preprocessing, EDA, and modeling.
3. Review the model's performance metrics and interpret the insights from the analysis.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib

## Future Work
- Experiment with more advanced classification models (e.g., Random Forest, XGBoost).
- Perform hyperparameter tuning to further improve model performance.
- Explore additional features to enhance predictive accuracy.

## Author
- KrystalG
