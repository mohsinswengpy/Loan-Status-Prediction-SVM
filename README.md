# Loan Status Prediction using Support Vector Machine (SVM)

This project builds a predictive system to determine whether a loan applicant is likely to be approved or rejected based on various personal and financial features. It utilizes a Support Vector Machine (SVM) classifier to perform the prediction.

## Project Overview
The core objective is to analyze a loan dataset and train a machine learning model to classify loan statuses as 'Approved' (Y) or 'Rejected' (N). The process includes data cleaning, label encoding, data visualization, and model evaluation.

## Workflow
1.  **Data Collection & Processing**: Loaded the dataset and handled missing values by dropping rows with incomplete data.
2.  **Label Encoding**: Converted categorical variables (like Gender, Married status, Education, etc.) and the target 'Loan_Status' into numerical formats.
3.  **Data Visualization**: Analyzed the relationship between features (e.g., Education, Marital Status) and the loan outcome.
4.  **Feature Selection**: Separated features (X) and the target variable (Y).
5.  **Model Training**: Split the data into training and test sets and trained an SVM classifier with a linear kernel.
6.  **Evaluation**: Calculated the accuracy score for both training and test datasets.

## Key Technologies
*   **Python**: Primary programming language.
*   **Pandas & NumPy**: For data manipulation and numerical analysis.
*   **Seaborn & Matplotlib**: For data visualization.
*   **Scikit-Learn**: For preprocessing, model training (SVM), and performance evaluation.

## Performance
*   **Training Accuracy**: ~79.86%
*   **Test Accuracy**: ~83.33%

## How to Run
1.  Ensure you have the required libraries installed (`pandas`, `numpy`, `seaborn`, `scikit-learn`).
2.  Load your dataset (`dataset.csv`).
3.  Run the code in your Python environment or Jupyter notebook.
