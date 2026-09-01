# HR Employee Attrition Analysis

## Project Overview

This project analyzes employee attrition patterns using **Excel and Power BI** to identify workforce segments with higher employee turnover and provide actionable recommendations for improving employee retention.

The analysis uses data from **1,470 employees** and examines attrition across factors such as department, age, tenure, job role, overtime, business travel, job level, income, and distance from home.

---

## Business Problem

Employee attrition can increase recruitment costs, reduce productivity, and create workforce planning challenges.

The goal of this project is to answer:

* What is the overall employee attrition rate?
* Which employee groups have the highest attrition?
* Does attrition vary by tenure, age, job role, or department?
* How is overtime associated with employee attrition?
* Are frequent business travelers more likely to leave?
* Which areas should HR prioritize for retention efforts?

---

## Project Objectives

* Calculate key employee attrition metrics.
* Identify workforce segments with higher attrition rates.
* Analyze relationships between employee characteristics and attrition.
* Build an interactive Power BI dashboard for HR decision-making.
* Provide data-driven recommendations for employee retention.

---

## Tools & Technologies

* **Microsoft Excel** – Data cleaning, transformation, calculations, and exploratory analysis
* **Power BI** – Interactive dashboard and data visualization
* **DAX** – KPI and attrition calculations
* **Power Query** – Data transformation and calculated columns

---

## Key Metrics

| Metric                 | Result |
| ---------------------- | -----: |
| Total Employees        |  1,470 |
| Employees Left         |    237 |
| Overall Attrition Rate | 16.12% |

---

## Key Business Insights

### 1. Early-Tenure Employees Have Higher Attrition

Employees with less than 2 years of tenure had an attrition rate of **34.88%**, substantially higher than employees with longer tenure.

**Insight:** Early employee experience appears to be an important area for retention efforts.

### 2. Younger Employees Have Higher Attrition

Employees under 25 had the highest age-based attrition rate at **39.18%**, followed by employees aged 25–34 at **20.22%**.

**Insight:** Younger employees may benefit from stronger onboarding, mentoring, career development, and engagement programs.

### 3. Overtime Is Associated With Higher Attrition

Employees working overtime had an attrition rate of **30.53%**, compared with **10.44%** for employees who did not work overtime.

**Insight:** Workload, staffing levels, and overtime patterns should be monitored as part of employee retention efforts.

### 4. Certain Job Roles Have Higher Attrition

The highest attrition rates were observed among:

* Sales Representatives – **39.76%**
* Laboratory Technicians – **23.94%**
* Human Resources – **23.08%**
* Sales Executives – **17.48%**

**Insight:** Retention strategies may need to be tailored to specific roles rather than applied uniformly across the organization.

### 5. Sales Has the Highest Department-Level Attrition

Sales had an attrition rate of **20.63%**, compared with **19.05%** in Human Resources and **13.84%** in Research & Development.

**Insight:** Sales workforce planning and employee retention should be examined more closely.

### 6. Frequent Business Travel Is Associated With Higher Attrition

Employees who traveled frequently had an attrition rate of **24.91%**, compared with **8.00%** for employees who did not travel.

**Insight:** Travel demands, workload, and work-life balance may be areas worth investigating.

---

## Recommendations

Based on the analysis, the following actions could help improve employee retention:

### Strengthen Early-Tenure Support

* Improve onboarding programs.
* Introduce 30-, 60-, and 90-day employee check-ins.
* Establish mentoring programs for new employees.
* Provide clearer career development opportunities.

### Monitor Overtime and Workload

* Track overtime patterns by department and job role.
* Review staffing levels in high-overtime teams.
* Identify employees experiencing consistently high workloads.
* Consider workload balancing or scheduling improvements.

### Target High-Risk Roles

Develop role-specific retention strategies for positions with higher attrition, particularly:

* Sales Representatives
* Laboratory Technicians
* Human Resources roles
* Sales Executives

### Evaluate Business Travel

* Monitor attrition among frequent travelers.
* Review travel frequency and workload.
* Consider flexible work arrangements where appropriate.
* Gather employee feedback about travel expectations.

### Build Proactive Attrition Monitoring

HR teams can regularly monitor attrition KPIs through dashboards and investigate changes in high-risk employee segments.

---

## Power BI Dashboard

![HR Employee Attrition Dashboard](dashboard/HR_Attrition_Dashboard.png)

The Power BI dashboard provides an interactive view of employee attrition using KPI cards, charts, and slicers.

### Dashboard Includes

**KPI Cards**

* Total Employees
* Employees Left
* Attrition Rate

**Visualizations**

* Attrition Rate by Department
* Attrition Rate by Age Group
* Attrition Rate by Job Role
* Attrition Rate by Tenure
* Attrition Rate by Overtime
* Attrition Rate by Business Travel

**Interactive Filters**

* Department
* Job Role
* Age Group
* Overtime
* Gender

The dashboard allows users to filter the workforce and explore attrition patterns across different employee segments.

---

## Project Structure

```text
HR-Employee-Attrition-Analysis/
│
├── README.md
│
├── data/
│   └── HR_Employee_Attrition_Analysis.xlsx
│
├── powerbi/
│   └── HR_Employee_Attrition_Analysis.pbix
│
├── dashboard/
│   └── HR_Attrition_Dashboard.png
│
└── documentation/
    └── Business_Insights_and_Recommendations.md
```

---

## Key Skills Demonstrated

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis
* Excel Analysis
* Power Query
* Power BI
* DAX
* Data Visualization
* KPI Development
* Workforce Analytics
* HR Analytics
* Business Insights
* Data-Driven Recommendations

---

## Future Improvements

Future versions of this project could include:

* Predictive employee attrition modeling using Python
* Employee-level attrition risk scoring
* SQL-based data analysis
* Automated data refresh
* Additional HR KPIs
* Machine learning models for attrition prediction
* More advanced workforce segmentation

---

## Conclusion

This project demonstrates how employee data can be transformed into actionable workforce insights using **Excel and Power BI**.

The analysis identified several employee segments associated with higher attrition, particularly **younger employees, early-tenure employees, employees working overtime, certain job roles, and frequent business travelers**.

These findings can help HR teams prioritize retention initiatives and develop more targeted workforce strategies.
