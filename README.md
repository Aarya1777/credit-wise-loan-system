# Credit-Wise Loan System

**A machine learning project for loan approval prediction using data analysis and classification models.**

## Overview

The Credit-Wise Loan System is a machine learning project that analyzes applicant information to predict loan approval outcomes. It uses exploratory data analysis, data preprocessing, and classification algorithms to understand patterns in the dataset and evaluate model performance.

## Objectives

* Analyze applicant data to identify patterns related to loan approval.
* Perform data preprocessing and feature encoding.
* Visualize feature distributions and correlations.
* Train multiple machine learning classification models.
* Evaluate and compare models using standard performance metrics.

## Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

## Project Workflow

1. **Data Loading** — Load and inspect the loan dataset.
2. **Exploratory Data Analysis** — Analyze feature distributions and correlations using visualizations.
3. **Data Preprocessing** — Remove the applicant ID, encode categorical variables, and scale features.
4. **Train-Test Split** — Split the dataset into training and testing sets using an 80:20 ratio.
5. **Model Training** — Train multiple classification algorithms.
6. **Model Evaluation** — Compare model performance using accuracy, precision, recall, F1-score, and confusion matrices.

## Machine Learning Models

The following classification models were trained and evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Gaussian Naive Bayes

## Results

The notebook's recorded evaluation results are:

| Model                     | Accuracy | Precision | Recall | F1-Score |
| ------------------------- | -------: | --------: | -----: | -------: |
| Logistic Regression       |    86.5% |    78.33% | 77.05% |   77.69% |
| K-Nearest Neighbors (KNN) |    76.0% |    62.75% | 52.46% |   57.14% |
| Gaussian Naive Bayes      |    86.5% |    80.36% | 73.77% |   76.92% |

**Key Findings:**

* Logistic Regression and Gaussian Naive Bayes achieved the highest recorded accuracy of 86.5%.
* Gaussian Naive Bayes achieved the highest precision among the three models.
* K-Nearest Neighbors had lower overall performance on this dataset compared with the other evaluated models.

These results are based on the notebook's recorded outputs and may vary when the experiment is rerun.

## How to Run

1. Clone or download this repository.

2. Install Python and Jupyter Notebook.

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

4. Ensure the CSV dataset is available at the file path used in the notebook.

5. Open the notebook in Jupyter Notebook.

6. Run the cells in order.

## Future Improvements

* Perform hyperparameter tuning to improve model performance.
* Apply cross-validation for more reliable evaluation.
* Investigate class imbalance and additional evaluation metrics.
* Develop an interactive loan prediction interface using Flask.
* Explore model deployment.

## Disclaimer

This project is intended for educational purposes and machine learning practice. Its predictions should not be used as the sole basis for real-world lending decisions.

---

**Developed as a machine learning project focused on loan approval prediction.**
