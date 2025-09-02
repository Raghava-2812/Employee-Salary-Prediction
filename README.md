# Employee Salary Prediction

## Overview
This project predicts whether an employee’s annual income exceeds $50K based on demographic and employment-related features. It uses machine learning techniques to analyze patterns in the data and make accurate predictions.

## Dataset
The dataset includes attributes such as:
- Work class
- Education
- Marital status
- Occupation
- Relationship
- Race
- Gender
- Native country

Missing and irrelevant data were handled to improve model accuracy.

## Features
- **Data Cleaning:** Removed unnecessary or invalid categories and handled missing values.
- **Encoding:** Converted categorical features to numerical values using Label Encoding.
- **Normalization:** Scaled features using Min-Max scaling.
- **Modeling:** Gradient Boosting Regressor to predict income as a binary outcome (`<=50K` or `>50K`).
- **Evaluation:** Achieved ~86% accuracy on the test dataset.
- **Visualization:** Scatter plot comparing predicted vs actual income.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (Gradient Boosting Regressor)

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Raghava-2812/Employee-Salary-Prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Load the dataset (adult 3.csv) and update the path in the script.
4. Run the script:
   ```bash
   python employee_salary_prediction.py
   ```
## Output

- Model predictions for the test dataset.

- Accuracy score of the model.

- Scatter plot of predicted vs actual salaries.

- Predicted categories (<=50K or >50K).
