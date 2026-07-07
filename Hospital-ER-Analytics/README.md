# 🏥 Hospital Emergency Room Analytics Dashboard (Power BI)

A comprehensive **Power BI Business Intelligence Dashboard** built to analyze Emergency Room (ER) operations, patient flow, service quality, and hospital performance using real-world healthcare data.

The project transforms raw patient records into interactive dashboards that help hospital administrators monitor operational efficiency, identify bottlenecks, improve patient experience, and support data-driven decision making.

---

# Project Objective

The objective of this project is to design an interactive analytics solution that provides actionable insights into Emergency Room performance by monitoring:

- Daily patient volume
- Average waiting time
- Patient satisfaction
- Referral patterns
- Admission trends
- Demographic analysis
- Operational efficiency
- Patient-level records

The dashboard enables healthcare administrators to quickly identify trends and optimize hospital resources.

---

# Dataset Information

- **Duration:** April 2023 – October 2024
- **Total Patients:** 9,216
- **Data Type:** Emergency Room Patient Records

The dataset contains information such as:

- Patient ID
- Admission Date
- Patient Name
- Gender
- Age
- Race
- Department Referral
- Wait Time
- Admission Status
- Satisfaction Score

---

# Data Preparation

The following preprocessing steps were completed before building the dashboard.

### Data Cleaning

- Removed unnecessary inconsistencies
- Validated missing values
- Corrected data formatting

### Custom Columns

Created a new column:

- **Patient Full Name**
  - Combined First Name and Last Name

### Data Standardization

Expanded abbreviated gender values:

| Original | Updated |
|----------|----------|
| M | Male |
| F | Female |
| NC | Not Confirmed |

### Date Table

Created a dedicated Date Dimension containing:

- Date
- Month
- Month Name
- Year
- Day
- Weekday

This supports efficient time intelligence and filtering.

---

# Dashboard Overview

The Power BI report consists of three interactive dashboards.

---

# Dashboard 1 — Monthly View

### Purpose

Monitor Emergency Room performance month by month.

### KPIs

- Total Patients
- Average Wait Time
- Average Satisfaction Score
- Number of Patients Referred

### Visualizations

- Patient Admission Status
- Patient Age Distribution
- Department Referrals
- Percentage Seen Within 30 Minutes
- Gender Distribution
- Race Distribution
- Patient Volume by Day
- Patient Volume by Hour

This dashboard helps identify monthly operational trends and performance.

<img width="1190" height="724" alt="image" src="https://github.com/user-attachments/assets/aa4660e0-660e-4203-a1d3-ea9fc20cc275" />


---

# Dashboard 2 — Consolidated View

### Purpose

Provide an overall summary across any selected date range.

Users can interactively filter dates to analyze:

- Patient Count
- Wait Time
- Satisfaction
- Referrals
- Admissions
- Demographics
- Time-based trends

This dashboard provides executive-level insights into overall hospital performance.


<img width="1190" height="731" alt="image" src="https://github.com/user-attachments/assets/d14d21c4-ac75-4832-a213-5e444a830a6c" />

---

# Dashboard 3 — Patient Details

### Purpose

Provide patient-level drill-down information.

The dashboard includes:

- Patient ID
- Patient Full Name
- Gender
- Age
- Admission Date
- Patient Race
- Wait Time
- Department Referral
- Admission Status

Useful for operational reviews and troubleshooting.


<img width="1188" height="726" alt="image" src="https://github.com/user-attachments/assets/a19f63a1-c356-4799-ad9f-de8fe1db276f" />

---

# Key Business Requirements Implemented

## Daily Patient Count

- Total ER patients per day
- Daily trend visualization using sparklines

<img width="231" height="132" alt="image" src="https://github.com/user-attachments/assets/e89075c7-1b82-4f78-8f13-dda4d1cdbfa0" />

---

## Average Wait Time

- Average waiting time before consultation
- Daily trend analysis

<img width="235" height="131" alt="image" src="https://github.com/user-attachments/assets/a5649b97-60c4-47e7-8b45-8c8aaa7ab6c0" />

---

## Patient Satisfaction

- Average daily satisfaction score
- Trend analysis to identify service quality fluctuations

<img width="228" height="136" alt="image" src="https://github.com/user-attachments/assets/7c301cc2-0487-40a2-aff4-671a0bf97cd1" />

---

## Department Referrals

Daily referral analysis across departments to identify resource requirements.

<img width="230" height="131" alt="image" src="https://github.com/user-attachments/assets/702ffd31-a0ec-4627-85b7-739f2f80ab8a" />

---

# Key Insights

## Overall Statistics

- Total Patients: **9,216**
- Time Period: **April 2023 – October 2024**
- Average Wait Time: **35.3 minutes**
- Average Satisfaction Score: **4.99 / 10**

---

## Patient Wait Time

Average waiting time is approximately **35 minutes**, indicating opportunities to improve patient flow and reduce delays.

---

## Patient Satisfaction

Average satisfaction is **4.99/10**, suggesting moderate patient experience with scope for operational improvements.

---

## Department Referrals

Most patients did not require referrals.

Among referred patients:

| Department | Patients |
|------------|----------|
| General Practice | 1,840 |
| Orthopedics | 995 |
| Physiotherapy | 276 |
| Cardiology | 248 |

General Practice received the highest referral volume.

---

## Peak Patient Traffic

### Busiest Days

- Monday — 1,377 patients
- Saturday — 1,322 patients
- Tuesday — 1,318 patients

### Peak Hours

- 11 AM
- 1 PM
- 7 PM
- 11 PM

These periods may require increased staffing.

---

## Patient Demographics

Largest age group:

- 30–39 years (1,200 patients)

Followed by:

- 20–29 years (1,188 patients)

---

## Race Distribution

Largest groups:

- White — 2,571
- African American — 1,951
- Multi-racial — 1,557
- Asian — 1,060

Approximately 1,030 patients declined to identify their race.

---

## Admission Pattern

- Admitted: 4,612 patients
- Treated & Released: 4,604 patients

Admissions were almost evenly split.

---

# Power BI Features Used

- Data Modeling
- Relationships
- Date Table
- DAX Measures
- Calculated Columns
- Interactive Filters
- Slicers
- KPI Cards
- Area Sparklines
- Bar Charts
- Donut Charts
- Matrix Table
- Time Intelligence
- Conditional Formatting
- Custom Business Metrics

---

# Skills Demonstrated

- Power BI
- Power Query
- Data Cleaning
- Data Transformation
- Data Modeling
- DAX
- Dashboard Design
- Business Intelligence
- Healthcare Analytics
- Data Visualization
- KPI Development
- Time Series Analysis

---

# Business Value

The dashboard enables hospital management to:

- Monitor Emergency Room workload
- Improve patient flow
- Reduce waiting time
- Track patient satisfaction
- Allocate staff efficiently
- Understand referral patterns
- Analyze demographic trends
- Support data-driven operational decisions

---

# Tools Used

- Microsoft Power BI Desktop
- Power Query
- DAX
- Microsoft Excel / CSV Dataset

---

# Future Improvements

- Predictive patient arrival forecasting
- Wait time prediction using Machine Learning
- Bed occupancy monitoring
- Doctor performance dashboard
- Real-time hospital monitoring
- Integration with SQL Server
- Automated data refresh
- Role-Level Security (RLS)
