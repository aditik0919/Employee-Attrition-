# Employee Attrition Analysis

## Overview

This project analyzes employee attrition in an organization to identify key factors influencing employee turnover. Using statistical techniques and machine learning models, it provides actionable insights to help organizations improve employee retention and reduce attrition rates.

## Features

- Exploratory data analysis (EDA) to identify patterns in attrition.
- Analysis of key factors influencing employee turnover (e.g., job satisfaction, salary, work-life balance).
- Predictive modeling to classify employees at risk of attrition.
- Visualizations to present insights effectively.

## Dataset

The project uses a dataset containing employee information such as demographics, job roles, salary, work experience, and attrition status.

- **Source**: https://www.kaggle.com/datasets/patelprashant/employee-attrition
- **Size**: The dataset contains 1470 rows and 35 columns ![image](https://github.com/user-attachments/assets/d078441e-b848-489e-9ad2-f7c0a7508a8a)
- **Attributes**: Examples include `Age`, `Job Role`, `Monthly Income`, `Years at Company`, `Attrition Status`, etc.

## Technologies Used

- **Programming Languages**: Python, R
- **Libraries**: 
  - Data analysis: Pandas, NumPy
  - Visualization: Matplotlib, Seaborn, Plotly
  - Machine Learning: Scikit-learn

## Key Steps

1. **Data Cleaning**: Handle missing values, outliers, and data inconsistencies.
2. **Exploratory Data Analysis**:
   - Analyze trends in attrition based on employee demographics and job features.
   - Correlation analysis to identify relationships between variables.
3. **Feature Engineering**:
   - Create new features to enhance model performance.
4. **Predictive Modeling**:
   - Implement classification models (e.g., Logistic Regression, Decision Trees).
   - Evaluate model performance using accuracy, precision, recall, and F1-score.
5. **Visualization**:
   - Generate dashboards to present findings and recommendations.

## Insights


  - Employees with low job satisfaction have a higher likelihood of attrition.
  - Work-life balance and growth opportunities are significant factors in retention.
  - Predictive model achieves an accuracy of 85% in identifying at-risk employees.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/username/employee-attrition-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd employee-attrition-analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the analysis scripts or Jupyter notebooks:
   ```bash
   python analysis.py
   ```
5. View visualizations and insights in the `results` folder or Power BI dashboards.

## Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

