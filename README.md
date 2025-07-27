IBM HR Analytics Project – Case Study

👩‍💼 Author: Jharna Thapa

📊 Tools Used: Excel, SQL (MySQL), Python (Pandas, Seaborn, Matplotlib, Scikit-learn)

📌 Objective

Analyze IBM HR data to identify factors contributing to employee attrition and recommend actionable strategies for retention based on data-driven insights.

🧩 Dataset Overview

File: hr_employee.csv

Records: 1,470

Features: 35+ including Age, Department, Monthly Income, OverTime, Job Role, YearsAtCompany, JobSatisfaction, etc.

🔧 Tools & Techniques

Phase

Tool/Library

Techniques Used

Data Cleaning

Excel, SQL

Null handling, type formatting, text encoding

Data Structuring

SQL (MySQL)

UPDATE, REPLACE, IS NULL, ALTER TABLE

Data Preprocessing

Python (sklearn)

LabelEncoding, RobustScaler

Data Analysis

Python (pandas, seaborn, matplotlib)

EDA, visualization, feature correlation

Reporting

PowerPoint

10-slide insights deck with recommendations

📊 Key Insights

🔍 38% attrition rate among employees with less than 2 years of tenure

🧑‍💼 Sales department had 22% higher attrition than other departments

⏱️ Employees working overtime showed a 44% higher risk of attrition

😐 Low job satisfaction accounted for over 30% of total attrition

💡 Recommendations

Implement retention programs for new joiners during their first 2 years

Reassess workload and overtime distribution across departments

Introduce satisfaction monitoring tools and exit feedback analysis

📈 Visuals Generated

Bar plots, histograms, and count plots for categorical variables

Heatmaps to show feature correlation

Boxplots comparing attrition across departments and roles

Pie charts for demographic and department-level breakdowns

🗂️ File Structure

├── hr_employee.csv
├── ibm_hr_analysis.ipynb
├── /images
│   ├── heatmap_correlation.png
│   ├── attrition_by_department.png
│   └── overtime_boxplot.png
├── ppt/IBM_HR_Analytics_Summary.pptx
└── README.md

🚀 How to Run This Project

Clone the repo or download the files

Open the Jupyter Notebook ibm_hr_analysis.ipynb
