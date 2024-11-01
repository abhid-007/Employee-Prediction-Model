# Employee Attrition Prediction

This project aims to tackle employee attrition prediction using machine learning techniques. Employee attrition, or turnover, is a major concern for businesses, impacting productivity, morale, and financial performance. By analyzing employee data, we can understand the factors driving attrition and build predictive models to classify employees as likely to stay or leave. Accurate predictions allow HR teams to take proactive measures, retain valuable talent, and reduce costs associated with hiring and training new employees.

---

## Project Structure

### Files in This Repository
- **`df_merged_dept_emp_det.csv`**: Original dataset containing employee data.
- **`employee-prediction.ipynb`**: Jupyter notebook with the full analysis, preprocessing steps, modeling, and evaluation.
- **`requirements.txt`**: List of libraries and their versions required to run the notebook.
- **`submission_with_predictions.csv`**: Model predictions saved in CSV format, comparing predicted vs actual values for further evaluation.
- **`submission_with_predictions.xlsx`**: Excel file with the same model predictions, with incorrect predictions highlighted.

---

## Problem Statement

Employee attrition poses significant challenges for businesses, as unexpected employee departures can lead to high costs and a loss of valuable knowledge and skills. By identifying the main drivers of attrition and predicting which employees are likely to leave, companies can implement targeted retention strategies to improve employee engagement and job satisfaction, ultimately reducing turnover.

---

## Project Outline

Here's a summary of the steps taken to build the attrition prediction model.

### 1. Data Cleaning
### 2. Data Preprocessing
### 3. Exploratory Data Analysis (EDA)
### 4. Encoding of Categorical Columns
### 5. Feature Importance Validation
### 6. Saving Predictions for Train and Test Sets
### 7. Neural Network Ensemble

## Installation

To get started, install the necessary dependencies listed in `requirements.txt`:
```bash
pip install -r requirements.txt
```

---

## Usage

1. **Load the Dataset**: `df_merged_dept_emp_det.csv` contains all the employee records.
2. **Run the Jupyter Notebook**: Open and execute `employee-prediction.ipynb`.
3. **Save the Results**: The notebook will save predictions in  CSV format for further inspection.

---

## Results
### Model Performance
The neural network ensemble achieved high AUC scores, showing improved predictive power through model stacking.

---

## Future Enhancements
- **Model Tuning**: Experiment with hyperparameter optimization techniques for better accuracy.

---

## Contributions

Feel free to contribute to this project by opening issues or submitting pull requests.

---

## License

This project is open-source under the MIT License.

---

> *Let's make employee retention strategies data-driven and effective!*

---
