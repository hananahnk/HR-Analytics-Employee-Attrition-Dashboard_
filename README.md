HR Analytics – Employee Attrition Dashboard

This project analyzes factors influencing employee attrition using the IBM HR Analytics dataset (Kaggle) and visualizes the results in Looker Studio.

🚀 Objective

Identify the top factors that lead to employee attrition and provide actionable insights through an interactive HR dashboard.

🧠 Tools & Technologies
Python: Pandas, Scikit-learn, RandomForest
Feature Interpretation: Feature Importance (Tree-based)
Visualization: Looker Studio (Google Looker)
Data Handling: CSV integration for dashboard
🧩 Workflow

Data Cleaning & Feature Engineering

Removed redundant features
Encoded categorical variables
Balanced dataset using RandomOverSampler

Model Development

Built a Random Forest Classifier to predict attrition
Extracted top feature importances influencing attrition

Dashboard Design (Looker)
Created multiple visualizations:

Top 5 Attrition Reasons (Bar Chart)
Attrition Count by Department
Attrition Rate by Job Role
Employee Age Distribution
Monthly Income Distribution
Years at Company vs Attrition
Employee Count & Department Count (KPIs)
📊 Key Insights
Stock Options, Job Satisfaction, and Monthly Income were key attrition drivers.
Sales and R&D departments showed the highest attrition rates.
Younger employees and those with fewer years in the company tend to leave more often.

📸 Dashboard Preview

🧾 Dataset

IBM HR Analytics Employee Attrition & Performance – Kaggle

