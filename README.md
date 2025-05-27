# Predict Employee Attrition

This project implements an employee attrition prediction system using the IBM HR Analytics Employee Attrition & Performance dataset. The goal is to identify key factors influencing employee turnover and predict potential attrition to aid HR decision-making.
Features

Data Exploration: Analyzes dataset structure, distributions, and relationships using visualizations like count plots and correlation heatmaps.
Data Preprocessing: Encodes categorical variables using LabelEncoder and scales numerical features with StandardScaler.
Model Training: Trains a Random Forest Classifier for accurate prediction of employee attrition.
Evaluation Metrics: Uses Accuracy, Precision, Recall, and F1 Score to assess model performance.
Feature Importance: Identifies and visualizes key drivers of attrition (e.g., MonthlyIncome, OverTime).

## Tools & Libraries

Python
Pandas, NumPy
Scikit-learn (preprocessing, Random Forest, metrics)
Matplotlib, Seaborn (for visualization)

Final Results
## Model Performance:

andom Forest Classifier:
Class 0 (Non-attrition):
Precision: 0.88
Recall: 0.98
F1 Score: 0.93
Support: 255


Class 1 (Attrition):
Precision: 0.50
Recall: 0.10
F1 Score: 0.17
Support: 39


Overall Accuracy: 86.73%
Macro Average:
Precision: 0.69
Recall: 0.54
F1 Score: 0.55


Weighted Average:
Precision: 0.83
Recall: 0.87
F1 Score: 0.83





## Key Insight:
The model performs strongly for non-attrition cases (high precision and recall) but struggles to identify attrition cases, with low recall (0.10) for defaulters. This indicates class imbalance issues, which could be addressed with techniques like SMOTE, hyperparameter tuning, or alternative models to improve performance on the minority class.
How to Run

Clone the Repository (if applicable, or skip to step 2):
git clone https://github.com/your-username/employee-attrition-prediction.git
cd employee-attrition-prediction


Install Required Libraries:
pip install pandas numpy matplotlib seaborn scikit-learn


Run the Notebook:

Download the IBM HR Analytics dataset from Kaggle and place it in your working directory (e.g., as Attrition.csv).
Open task5.ipynb in Jupyter Notebook or JupyterLab and run all cells.



##Output

- Visualizations of attrition distribution and feature importance.
- Classification report with precision, recall, and F1 scores.
- Detailed insights into factors driving employee turnover.

## Contributing
Contributions are welcome! Fork the repo and submit a pull request for improvements, additional models (e.g., Gradient Boosting), or enhanced visualizations.
## License
This project is open-source and available under the MIT License.
