# 🏥 Hospital Emergency Room Dashboard | Power BI

## 📌 Project Overview

This project is an interactive **Hospital Emergency Room Dashboard** built using **Power BI** to analyze emergency room operations, patient admissions, wait times, referrals, demographics, and satisfaction scores.

The dashboard converts raw healthcare data into actionable insights that help hospital administrators monitor performance, optimize resources, and improve patient care through data-driven decision-making.

---

# 📊 Dashboard Preview

## Monthly View Dashboard

![Dashboard Overview](.png)

## Patient Details Dashboard

![Patient Details](patient-details-page.png)

---

# 🎯 Project Objectives

- Analyze emergency room patient volume.
- Monitor average patient wait times.
- Track admission and non-admission rates.
- Analyze patient demographics.
- Identify referral department trends.
- Measure patient satisfaction.
- Create an interactive healthcare analytics dashboard.

---

# 🛠 Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Modeling

---

# 📂 Dataset Information

The dataset contains emergency room patient records including:

- Patient ID
- Patient Name
- Patient Gender
- Patient Age
- Patient Race
- Admission Status
- Patient Admission Date
- Patient Admission Time
- Department Referral
- Patient Wait Time
- Patient Satisfaction Score
- Admission Hours
- Wait Time Status
- Age Group

---

# 📈 Dashboard Features

## KPI Cards

- Total Patients
- Average Wait Time
- Patient Satisfaction Score
- Total Patients Referred

## Interactive Filters

- Year Filter
- Month Filter
- Date Range Filter

## Interactive Visualizations

- Admission Status Analysis
- Patient Gender Distribution
- Patient Age Group Analysis
- Patient Race Analysis
- Department Referral Analysis
- Daily Patient Trends
- Wait Time Performance Analysis
- Detailed Patient Records

---

# 📊 Business Questions Answered

### 1. How many patients visited the emergency room?

Analyze overall patient volume during the selected period.

### 2. What is the average patient wait time?

Measure service efficiency and identify bottlenecks.

### 3. What percentage of patients were admitted?

Compare admitted versus non-admitted patients.

### 4. Which age groups visit the emergency room most frequently?

Understand patient demographics.

### 5. Which departments receive the highest referrals?

Identify referral patterns and workload distribution.

### 6. How does patient volume vary by day of the week?

Determine peak traffic periods.

### 7. Are patients being seen within target wait times?

Evaluate operational performance.

---

# 📷 Dashboard Components

✅ KPI Cards

✅ Bar Charts

✅ Line Charts

✅ Donut Charts

✅ Matrix Visual

✅ Interactive Slicers

✅ Navigation Buttons

✅ Detailed Patient Table

✅ Dynamic Filtering

---

# 📊 DAX Measures Used

## Total Patients

```DAX
No of Patients =
DISTINCTCOUNT('Hospital ER_Data'[Patient Id])
```

## Average Wait Time

```DAX
Avg Wait Time =
AVERAGE('Hospital ER_Data'[Patient Waittime])
```

## Average Satisfaction Score

```DAX
Patient Satisfaction Score =
AVERAGE('Hospital ER_Data'[Patient Satisfaction Score])
```

## Total Referred Patients

```DAX
No of Patients Referred =
CALCULATE(
    [No of Patients],
    'Hospital ER_Data'[Department Referral] <> "None"
)
```

---

# 📈 Key Insights

- Emergency room handled over **9,200+ patients**.
- Admission and non-admission rates were nearly equal.
- Average wait time was approximately **35 minutes**.
- Patient satisfaction averaged **4.99/5**.
- Saturday recorded the highest patient traffic.
- General Practice generated the highest referrals.
- Most patients were seen within target wait times.

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- Power Query
- Healthcare Analytics
- Dashboard Development
- KPI Design
- Data Visualization
- Business Intelligence
- Interactive Reporting

---

# 👨‍💻 Author

**Abhay Vadhvana**

📧 Email: av.com007@gmail.com

---

# ⭐ Support

If you found this project useful, consider giving it a **Star ⭐** on GitHub.
