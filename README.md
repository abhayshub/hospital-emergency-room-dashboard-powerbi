🏥 Hospital Emergency Room Dashboard | Power BI
📌 Project Overview

This project is an interactive Hospital Emergency Room Dashboard developed using Power BI to analyze patient visits, admissions, wait times, referrals, demographics, and satisfaction scores.

The dashboard transforms raw healthcare data into meaningful insights that help hospital administrators and healthcare professionals monitor emergency room performance and improve patient care through data-driven decision-making.

📊 Dashboard Preview
Monthly View Dashboard

Patient Details Dashboard

🎯 Project Objectives
Analyze emergency room patient volume.
Monitor patient wait times and service efficiency.
Track admission and non-admission rates.
Analyze patient demographics by age, gender, and race.
Identify referral department patterns.
Measure patient satisfaction levels.
Build an interactive Power BI dashboard for healthcare analytics.
🛠 Tools & Technologies
Power BI
Power Query
DAX
Microsoft Excel
Data Modeling
📂 Dataset Information

The dataset contains emergency room patient records with the following fields:

Patient ID
Patient Name
Patient Gender
Patient Age
Patient Race
Admission Status
Patient Admission Date
Patient Admission Time
Department Referral
Patient Wait Time
Patient Satisfaction Score
Admission Hours
Wait Time Status
Age Group
📈 Dashboard Features
✔ KPI Cards
Total Patients
Average Wait Time
Patient Satisfaction Score
Total Patients Referred
✔ Interactive Filters
Year
Month
Date Range
✔ Interactive Visualizations
Admission Status Analysis
Patient Gender Distribution
Patient Age Group Analysis
Patient Race Analysis
Department Referral Analysis
Daily Patient Trend
Wait Time Performance Analysis
Patient Detail Table
📊 Business Questions Answered
1. How many patients visited the emergency room?

Analyze total patient volume during the selected period.

2. What is the average patient wait time?

Monitor service efficiency and identify bottlenecks.

3. What percentage of patients were admitted?

Compare admitted and non-admitted patients.

4. Which age groups visit the emergency room most frequently?

Understand patient demographics.

5. Which departments receive the most referrals?

Analyze referral trends across departments.

6. How does patient volume vary throughout the week?

Identify peak traffic days for resource planning.

7. Are patients being seen within the target wait time?

Evaluate emergency room operational performance.

📷 Dashboard Components

✔ KPI Cards

✔ Line Charts

✔ Bar Charts

✔ Donut Charts

✔ Matrix Visual

✔ Interactive Slicers

✔ Navigation Buttons

✔ Dynamic Filtering

✔ Detailed Patient Records

📊 DAX Measures Used
Total Patients
No of Patients =
DISTINCTCOUNT('Hospital ER_Data'[Patient Id])
Average Wait Time
Avg Wait Time =
AVERAGE('Hospital ER_Data'[Patient Waittime])
Average Satisfaction Score
Patient Satisfaction Score =
AVERAGE('Hospital ER_Data'[Patient Satisfaction Score])
Total Referred Patients
No of Patients Referred =
CALCULATE(
    [No of Patients],
    'Hospital ER_Data'[Department Referral] <> "None"
)
📈 Key Insights
Emergency room handled over 9,200+ patient visits.
Admission and non-admission rates were almost equally distributed.
Average patient wait time remained around 35 minutes.
Patient satisfaction score averaged 4.99 / 5.
Saturday recorded the highest patient traffic.
General Practice generated the highest number of referrals.
Most patients were seen within the target waiting period.
🚀 Skills Demonstrated
Data Cleaning
Data Transformation
Data Modeling
DAX Calculations
Power Query
Healthcare Analytics
Dashboard Development
Data Visualization
KPI Design
Interactive Reporting
Business Intelligence
📁 Repository Contents
📦 Hospital-Emergency-Room-Dashboard
 ┣ 📊 Hospital Emergency Room Dashboard.pbix
 ┣ 📷 dashboard-overview.png
 ┣ 📷 patient-details-page.png
 ┣ 📄 README.md
 ┗ 📄 Dataset.xlsx
💡 Business Value

This dashboard helps healthcare organizations:

Monitor emergency room performance.
Improve patient experience.
Reduce waiting times.
Track referral patterns.
Support operational decision-making.
Optimize resource allocation.
👨‍💻 Author

Abhay Vadhvana

📧 Email: Your Email

💼 LinkedIn: Your LinkedIn Profile

🐙 GitHub: https://github.com/abhayshub
