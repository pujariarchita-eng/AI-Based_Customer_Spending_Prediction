# AI-Based Customer Spending Prediction

## Project Overview

This project uses machine learning to predict customer spending categories based on customer information such as age, annual income, gender, membership type, website visits, and preferred shopping category.

The customers are classified into three groups:
- Low Spending
- Medium Spending
- High Spending

The project demonstrates the basic workflow of a machine learning classification problem, from data preparation and visualization to model training and evaluation.

## Internship Details

- **Organization:** Veda Technology
- **Project Title:** AI-Based Customer Spending Prediction
- **Domain:** Artificial Intelligence and Machine Learning
- **Language:** Python
- **Environment:** Jupyter Notebook

## Objectives

- Create and prepare a customer dataset.
- Perform basic data cleaning and feature engineering.
- Explore customer data using visualizations.
- Build classification models to predict spending categories.
- Compare model performance using evaluation metrics.
- Generate predictions for a new customer.
- Identify useful customer spending patterns.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset Description

The project uses a synthetic dataset containing 1,000 generated customer records.

The dataset includes the following features:

| Feature | Description |
|---|---|
| Age | Customer's age |
| Gender | Customer's gender |
| Income | Annual income |
| Purchases | Number of purchases per year |
| Order_Value | Average order value |
| Website_Visits | Number of website visits |
| Membership | Membership category |
| Category | Preferred shopping category |
| Annual_Spending | Estimated annual spending |
| Spending_Category | Low, Medium, or High |
| Income_Per_Purchase | Income divided by purchase frequency |

**Note:** The dataset is generated using Python for educational purposes and does not contain actual Veda Technology customer data.

## Project Workflow

1. Import the required Python libraries.
2. Generate the customer dataset.
3. Inspect the data and remove duplicate records.
4. Calculate annual spending and create spending categories.
5. Perform feature engineering.
6. Conduct exploratory data analysis.
7. Create five visualizations to understand the data.
8. Prepare numerical and categorical features.
9. Split the dataset into training and testing sets.
10. Train Logistic Regression and Decision Tree models.
11. Compare accuracy, precision, recall, and F1-score.
12. Display the confusion matrix and classification report.
13. Examine Decision Tree feature importance.
14. Predict the spending category of a new customer.
15. Summarize the findings.

## Exploratory Data Analysis

The project includes the following visualizations:

1. Customer spending category distribution.
2. Annual income distribution.
3. Spending by membership type.
4. Purchase frequency versus annual spending.
5. Correlation heatmap.

These visualizations help explore customer characteristics and spending patterns.

## Machine Learning Models

### 1. Logistic Regression

Logistic Regression is used as a classification model to predict whether a customer belongs to the Low, Medium, or High spending category.

### 2. Decision Tree Classifier

The Decision Tree model classifies customers using decision rules learned from the training data.

Both models are evaluated on the same test dataset.

## Model Evaluation

The models are compared using:

- **Accuracy:** Overall proportion of correct predictions.
- **Precision:** Proportion of predicted class assignments that are correct.
- **Recall:** Proportion of actual class members correctly identified.
- **F1-score:** Harmonic mean of precision and recall.
- **Confusion matrix:** Shows correct and incorrect predictions for each category.

The model with the highest weighted F1-score is selected for the sample prediction.

Actual evaluation scores are generated when the notebook is executed.

## Sample Prediction

The project includes a prediction function that accepts customer details and predicts the spending category.

A sample customer is created with the following details:

- Age: 30
- Gender: Female
- Annual income: 75,000
- Website visits: 20
- Membership: Gold
- Preferred category: Electronics

The predicted category is displayed when the notebook runs.

## Expected Outcome

After executing the notebook, the project produces:

- A prepared customer dataset.
- Five exploratory data analysis visualizations.
- Two trained classification models.
- A model comparison table.
- A classification report and confusion matrix.
- A feature importance visualization.
- A sample customer spending prediction.
- Basic business insights.

## Business Applications

This type of project can help businesses explore customer segmentation, plan targeted promotions, understand shopping behavior, and develop customer engagement strategies.

Since the current dataset is synthetic, the results should be validated using real customer data before being used for business decisions.

## How to Run the Project

1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. Open Jupyter Notebook.
4. Open `customer_spending_prediction.ipynb`.
5. Run the notebook cells in order.
6. Review the generated charts, model scores, and prediction.

## Conclusion

This project demonstrates a basic machine learning workflow for customer spending prediction. It combines data preparation, exploratory data analysis, feature engineering, classification, and model evaluation in Python.

The project provides practical experience with the fundamental concepts of AI and machine learning and can be extended in the future using real customer datasets and additional classification techniques.

## Author

Completed as part of the AI/ML internship project at Veda Technology.
