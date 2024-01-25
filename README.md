# HR Attrition Prediction

## Overview

This repository contains Python code for building and evaluating machine learning models to predict employee attrition in a Human Resources (HR) dataset. The predictive models are created using popular classifiers such as RandomForestClassifier, Logistic Regression, and Support Vector Machine (SVM). The code includes data preprocessing, feature engineering, model training, evaluation, and visualization of results.

## Files

- **HR.csv**: The dataset containing HR-related information, including features like age, daily rate, department, education, etc., and the target variable 'Attrition,' indicating whether an employee has left the company ('Yes') or not ('No').

- **attrition_prediction.ipynb**: Jupyter Notebook file containing the Python code for data preprocessing, feature engineering, model training, evaluation, and visualization.

## Dependencies

Ensure you have the following Python libraries installed:

- pandas
- matplotlib
- seaborn
- scikit-learn

You can install them using the following command:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

## Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/HR-Attrition-Prediction.git
   ```

2. **Navigate to the Repository:**

   ```bash
   cd HR-Attrition-Prediction
   ```

3. **Open and Run the Jupyter Notebook:**

   ```bash
   jupyter notebook attrition_prediction.ipynb
   ```

   This will open the Jupyter Notebook in your default web browser. You can run the cells one by one to execute the code.

4. **Review the Results:**

   The notebook includes sections for data exploration, visualization, feature engineering, model training, and evaluation. You can observe the accuracy, classification reports, and ROC curves for each model.

## Acknowledgments

- The dataset used in this project is fictional and created for educational purposes.
- The code includes pipelines for RandomForestClassifier, Logistic Regression, and Support Vector Machine models, demonstrating a comparative analysis of their performance.

Feel free to explore, modify, and extend the code to enhance the predictive models or adapt it for other datasets. If you have any questions or suggestions, feel free to reach out!
