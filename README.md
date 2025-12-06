🚀 Gym Churn Predictor: Powering Customer Retention

✨ Project Overview
This project delivers a high-performance machine learning solution designed to predict customer attrition (churn) for a fitness center. By identifying high-risk members early, the model enables management to deploy targeted retention strategies, maximizing the Customer Lifetime Value (CLV).

🏆 Model Performance: 
Choosing the ChampionTwo robust models were trained and rigorously evaluated. Due to the critical nature of the imbalanced data (majority are non-churners), we prioritized Precision and Recall for the minority class (Churn).
<img width="866" height="266" alt="image" src="https://github.com/user-attachments/assets/ebd44f9d-b73f-4448-a59c-0d107e14de03" />

💡 Key Actionable Insights
Analysis of the model's coefficients and feature importance revealed the direct drivers of retention and attrition:The Churn Equation:Retention Master: Visits Per Month (Strongest Negative Correlation). High attendance = High loyalty.Attrition Trigger: Days Since Last Visit (Strongest Positive Correlation). Inactivity immediately escalates risk.Strategic Recommendations:Early Warning System (EWS): Implement a tracking system to flag members whose Visits Per Month drop below a defined baseline.14-Day Intervention Window: Initiate mandatory personal contact (staff calls, not automated emails) for any member absent for 14 days or more to interrupt the churn process.Incentivize Commitment: Actively promote annual and quarterly membership plans, as longer commitment is a proven counter-measure to churn risk.
🛠️ Project Structure & Usage
The project is structured for clarity and reproducibility..


├── data/
│   └── gym_data.csv            # Raw data file
├── notebooks/
│   └── Churn_Prediction_Analysis.ipynb # Full analysis, modeling, and results
├── README.md                   # This document
└── requirements.txt            # List of required dependencies

DependenciesTo replicate the analysis, please install the required libraries:Bash
pandas
numpy
scikit-learn
matplotlib
seaborn
⚙️ ContactAuthor: [[SeifMagdy66](https://github.com/SeifMagdy66)]  Linkedin: [https://www.linkedin.com/in/seifmagdy/]
