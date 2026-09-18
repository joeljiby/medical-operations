# 🏥 Medical Operations Intelligence Dashboard

### Development of a Healthcare Operations Intelligence Dashboard with Decision Analytics

**Individual Project**

**Platform:** Microsoft Power BI

---

## 📌 Project Overview

The **Healthcare Operations Intelligence Dashboard** is a Power BI-based healthcare analytics project designed to provide an integrated view of hospital operations and support data-driven decision-making.

The final Power BI model brings together patient, admission, treatment, staff, bed, facility, department, date and geographic information for interactive analysis.

The final Power BI model contains the following tables:

* `Dim_Department`
* `Dim_Patient`
* `Dim_Facility`
* `Dim_Date`
* `Fact_Admissions`
* `Fact_Treatments`
* `Fact_Beds`
* `Fact_Staff`
* `_Measures`

### Data Authenticity Note

This documentation represents the final Power BI model and dashboard developed for the project.

No new records are added to the original dataset, no source values are intentionally changed, and the original dataset remains separate from the analytical model.

---

# 🎯 Project Objectives

The project aims to:

* Analyze hospital admissions and patient activity.
* Monitor treatment demand and treatment status.
* Analyze department-level operational workload.
* Understand bed status and hospital capacity.
* Analyze staff shifts and workforce efficiency.
* Compare facilities and cities.
* Track clinical and operational KPIs.
* Provide management-oriented insights through Power BI.
* Transform healthcare operational data into an interactive decision-support dashboard.

---

# 🧩 Milestone-to-Model Mapping

| Milestone       | Main Focus                            | Final Power BI Evidence                                        |
| --------------- | ------------------------------------- | -------------------------------------------------------------- |
| **Milestone 1** | Data preparation & project foundation | Dimension/fact table structure and integrated healthcare model |
| **Milestone 2** | Patient flow & service demand         | Patient, admission, treatment and department analysis          |
| **Milestone 3** | Resources, capacity & workforce       | Beds, facilities, staff and related measures                   |
| **Milestone 4** | Geographic performance & insights     | Geographic Performance and Insights & Recommendations pages    |

The milestones represent the progressive development of the same healthcare analytics project and final Power BI solution.

---

# 📚 Milestone-Wise Project Development

## 🔹 Milestone 1 — Data Preparation & Project Foundation

### Objective

The first milestone established the foundation for the Healthcare Operations Intelligence Dashboard by organizing the healthcare information required for analysis.

### Work Completed

* Identified the major healthcare entities required for analysis.
* Prepared the project data for Power BI.
* Worked with patient, admission, treatment, staff, bed and facility information.
* Performed the required data preparation and integration.
* Established department and date dimensions.
* Planned the operational KPIs and analytical questions.
* Structured the data into fact and dimension tables.

### Data Entities Established

The final Power BI model contains:

* `Dim_Patient`
* `Dim_Department`
* `Dim_Facility`
* `Dim_Date`
* `Fact_Admissions`
* `Fact_Treatments`
* `Fact_Beds`
* `Fact_Staff`
* `_Measures`

### Milestone 1 Outcome

The project progressed from healthcare operational data toward a structured Power BI data model capable of supporting patient, admission, treatment, workforce, facility and capacity analysis.

---

# 🔹 Milestone 2 — Patient Flow & Service Demand Intelligence

## Objective

Milestone 2 focused on understanding patient activity, admissions, treatment demand and department-level workload.

### Patient Flow

`Dim_Patient` was used to analyze:

* Patient activity
* Age
* Gender
* City
* Registration information
* Patient distribution

### Admissions Analysis

`Fact_Admissions` was used to analyze:

* Admission activity
* Admission type
* Department
* Admission date
* Discharge date
* Length of stay
* Patient movement

The model includes measures such as:

* Admissions
* Discharges
* Avg LOS
* Admission Growth %
* Discharge Growth %
* Net Flow

### Treatment Demand

`Fact_Treatments` was used to analyze:

* Treatment type
* Treatment status
* Treatment date
* Department
* Patient treatment activity

The final model contains measures including:

* Completed Treatments
* Completion Rate
* Cancellation Rate

### Department Workload

Department-level analysis combines operational activity from the relevant healthcare fact tables with `Dim_Department`.

This allows differences in workload, treatment activity and operational demand between departments to be explored.

### Milestone 2 Outcome

Milestone 2 established the patient-flow and service-demand analytical layer of the project and created the foundation for department and treatment analysis.

---

# 🔹 Milestone 3 — Resource Utilization, Capacity & Workforce Intelligence

## Objective

Milestone 3 expanded the dashboard from patient and treatment analysis into resource, capacity and workforce analysis.

## 🛏️ Bed & Capacity Analysis

`Fact_Beds` and `Dim_Facility` were used to analyze:

* Bed status
* Bed type
* Department
* Facility
* Available beds
* Maintenance beds
* Total facility beds
* Capacity-related indicators

The `_Measures` table includes:

* Available Beds
* Capacity Reconciliation Gap
* Maintenance Beds

## 👨‍⚕️ Workforce Analysis

`Fact_Staff` was used to analyze:

* Staff
* Role
* Department
* Assigned shifts
* Worked shifts
* Staff efficiency

The model includes measures such as:

* Assigned Shifts
* Fulfillment Rate

## 🏢 Facility Analysis

`Dim_Facility` provides:

* City
* Facility ID
* Facility name
* Facility type
* Total beds

This enables facility-level comparisons of infrastructure and capacity.

### Milestone 3 Outcome

Milestone 3 introduced resource utilization, bed capacity, facility capacity and workforce analysis, expanding the dashboard from patient-centric analysis to broader hospital operations intelligence.

---

# 🔹 Milestone 4 — Geographic Performance & Insights

## Objective

Milestone 4 completed the geographic and management-oriented analysis of the project.

## 🌍 Geographic Performance

The final dashboard uses city information from the patient and facility dimensions to compare:

* Patients by city
* Facilities by city
* Facility bed capacity by city
* Admissions by city

Interactive filters include:

* City
* Department
* Date

## 💡 Insights & Recommendations

The final dashboard converts the analytical results into management-oriented observations and operational recommendations.

The analysis covers:

* Bed utilization
* Length of stay
* Workforce performance
* Treatment completion
* Capacity
* Patient flow
* Workforce deployment
* Treatment status
* Geographic demand

---

# 📊 Final Dashboard Insights

The completed Power BI dashboard reports the following project-level indicators:

* **63.9% bed occupancy**
* **7.58 days average length of stay**
* **84.34% staff efficiency**
* **75.1% treatment completion**
* **Neurology** recorded the highest overall workload in the operational analysis.
* **Orthopedics** recorded the lowest overall workload in the operational analysis.
* **Neurology workload signal:** 540
* **Consultation** was the highest-volume treatment type.
* **Neurology treatment completion rate:** 78.35%
* **Dermatology treatment completion rate:** 68.85%
* **Dermatology pending treatment rate:** 24.59%

These values represent the analytical results documented from the completed Power BI dashboard.

---

# ⚠️ Operational Areas Requiring Attention

The dashboard highlights several areas that can be monitored through the available data.

### Capacity

Monitor bed utilization and available capacity against admission demand.

### Patient Flow

Monitor admissions, discharges and average length of stay to identify areas that may require operational attention.

### Workforce

Review assigned shifts, worked shifts and department-level staff efficiency.

### Treatment

Monitor pending and cancelled treatments by department and treatment type.

### Geographic Performance

Compare patient activity and facility capacity across cities.

---

# 🎯 Management Recommendations

## 1. Optimize Bed Allocation

Use bed status, department, facility and city information to monitor capacity and support effective bed allocation.

## 2. Improve Patient Flow

Monitor admission activity, discharge activity and length of stay to identify potential areas of delay or increased demand.

## 3. Balance Workforce

Use assigned shifts, worked shifts and staff efficiency to support workforce and shift planning.

## 4. Monitor Treatment Completion

Analyze treatment status by department and treatment type to identify areas with higher pending or cancelled activity.

## 5. Monitor Geographic Demand

Use city-level patient, admission and facility information to compare demand and available healthcare capacity.

---

# 🏗️ Final Power BI Data Model

The final model follows a fact-and-dimension structure designed to support healthcare operational analysis.

```text
                    Dim_Department
                          │
          ┌───────────────┼────────────────┐
          │               │                │
          ▼               ▼                ▼
 Fact_Treatments    Fact_Admissions    Fact_Beds
          │               │                │
          │               │                ▼
          │               │          Dim_Facility
          │               │
          │               ▼
          │            Dim_Date
          │
          ▼
     Dim_Patient

          │
          ▼
      Fact_Staff


              ┌───────────────┐
              │   _Measures   │
              │  DAX Measures │
              └───────────────┘
```

The model combines dimension tables, operational fact tables and a dedicated measures table to support interactive Power BI analysis.

---

# 🗃️ Tables in the Final Power BI Model

## 1. Dim_Department

Contains department-level reference information used across the operational fact tables.

### Field

* Department

---

## 2. Dim_Patient

Contains patient-level demographic and registration information.

### Fields

* Age
* City
* Gender
* Patient ID
* Registration Date

---

## 3. Fact_Treatments

Contains treatment and healthcare service activity.

### Fields

* Department
* Patient ID
* Treatment Date
* Treatment ID
* Treatment Status
* Treatment Type

---

## 4. Fact_Admissions

Contains hospital admission and discharge activity.

### Fields

* Admission Date
* Admission ID
* Admission Type
* Department
* Discharge Date
* Length of Stay
* Patient ID

---

## 5. Fact_Beds

Contains bed-level operational information.

### Fields

* Bed ID
* Bed Type
* Department
* Facility ID
* Status

---

## 6. Fact_Staff

Contains workforce and shift information.

### Fields

* Department
* Role
* Shifts Assigned
* Shifts Worked
* Staff Efficiency
* Staff ID

---

## 7. Dim_Facility

Contains facility and city-level information.

### Fields

* City
* Facility ID
* Facility Name
* Facility Type
* Total Beds

---

## 8. Dim_Date

Provides time attributes for time-based analysis.

### Fields

* Date
* Month
* Month Number
* Quarter
* Year
* Year Month

---

# 📐 Measures

The final Power BI model contains a dedicated `_Measures` table for analytical calculations.

The measures include:

* Admission Growth %
* Admissions
* Assigned Shifts
* Available Beds
* Avg LOS
* Avg Pressure
* Cancellation Rate
* Capacity Reconciliation Gap
* Completed Treatments
* Completion Benchmark
* Completion Rate
* Demand Concentration %
* Department Demand
* Discharge Growth %
* Discharges
* Facilities
* Fulfillment Rate
* LOS Benchmark
* Maintenance Beds
* Net Flow

These measures are used across the dashboard for KPI calculations, comparisons and operational analysis.

---

# 📊 Final Dashboard

The completed Power BI report contains the following analytical pages:

1. Executive Dashboard
2. Patient Analytics
3. Admissions Analytics
4. Facilities Analytics
5. Staff Analytics
6. Treatment Analytics
7. Geographic Performance
8. Insights & Recommendations

---

## 1. 🏥 Executive Dashboard

Provides a high-level overview of hospital operations.

### Main Areas

* Patient activity
* Admissions
* Treatments
* Facilities
* Beds
* Department performance
* Monthly admission activity
* Patient distribution
* Gender distribution

The Executive Dashboard acts as the starting point for management-level exploration.

---

## 2. 👤 Patient Analytics

Focuses on patient demographics and registration information.

### Analysis

* Patient count
* Age
* Gender
* City
* Registration activity
* Patient distribution

### Filters

* Gender
* City
* Date

---

## 3. 🏥 Admissions Analytics

Focuses on admission and discharge activity.

### Analysis

* Admissions
* Admission type
* Department
* Admission date
* Discharge date
* Length of stay
* Monthly admission activity
* Patient movement

### Filters

* Admission Type
* Department
* Admission Date
* Discharge Date

---

## 4. 🏢 Facilities Analytics

Focuses on facilities and bed capacity.

### Analysis

* Total facilities
* Total beds
* Facility type
* Facility name
* City
* Bed capacity
* Facility comparisons

### Filters

* Facility Type
* City
* Facility

---

## 5. 👨‍⚕️ Staff Analytics

Focuses on workforce utilization.

### Analysis

* Staff distribution
* Staff by department
* Staff by role
* Assigned shifts
* Worked shifts
* Staff efficiency
* Department workforce comparison

### Filters

* Department
* Role

---

## 6. 💊 Treatment Analytics

Focuses on healthcare service demand and treatment completion.

### Analysis

* Total treatments
* Treatment type
* Treatment status
* Completed treatments
* Pending treatments
* Cancelled treatments
* Monthly treatment activity
* Department-level treatment demand

### Filters

* Treatment Status
* Treatment Type
* Department
* Date

---

## 7. 🌍 Geographic Performance

Uses city-level information to compare healthcare activity and capacity.

### Analysis

* Patients by city
* Facilities by city
* Facility bed capacity by city
* Admissions by city
* Geographic comparisons

### Filters

* City
* Department
* Date

This page provides a geographic view of patient activity, admissions and healthcare infrastructure.

---

## 8. 💡 Insights & Recommendations

The final page converts dashboard analysis into management-oriented observations and recommendations.

### Key Indicators

**Bed Utilization**

The dashboard reports **63.9% bed occupancy**, providing an overview of utilized and remaining hospital bed capacity.

**Patient Stay**

The operational analysis reports an **average length of stay of 7.58 days**.

**Workforce Performance**

The dashboard reports **84.34% staff efficiency**, providing an indicator of workforce utilization.

**Treatment Completion**

The dashboard reports approximately **75.1% treatment completion**.

### Department-Level Observations

* Neurology recorded the highest overall workload in the operational analysis.
* Orthopedics recorded the lowest overall workload.
* Neurology's workload signal was 540.
* Consultation was the highest-volume treatment type.
* Neurology recorded a treatment completion rate of 78.35%.
* Dermatology recorded a treatment completion rate of 68.85%.
* Dermatology recorded the highest pending treatment rate at 24.59%.

---

# 🔄 Project Workflow

```text
Healthcare Data
       ↓
Data Preparation
       ↓
Data Integration
       ↓
Power BI Data Model
       ↓
DAX Measures
       ↓
Interactive Visualizations
       ↓
Operational Analysis
       ↓
Insights
       ↓
Recommendations
       ↓
Management Decision Support
```

---

# 🛠️ Tools & Technologies

## Data & Analysis

* Python
* Pandas
* NumPy
* Jupyter Notebook

## Business Intelligence

* Microsoft Power BI

## Version Control

* Git
* GitHub

---

# 👤 Project Execution

This project was completed as an **individual Power BI project**.

The complete development and analytical workflow was carried out independently, including:

* Data preparation
* Data integration
* Data modeling
* Power BI development
* DAX measure creation
* Patient analytics
* Admission analysis
* Treatment analysis
* Bed and capacity analysis
* Workforce analysis
* Facility analysis
* Geographic analysis
* Dashboard design
* Insights and recommendations
* Project documentation

There is no team contribution section because the project was completed individually.

---

# 📋 Project Completion

| Component                  | Status      |
| -------------------------- | ----------- |
| Data Preparation           | ✅ Completed |
| Data Integration           | ✅ Completed |
| Power BI Data Model        | ✅ Completed |
| DAX Measures               | ✅ Completed |
| Patient Analytics          | ✅ Completed |
| Admissions Analytics       | ✅ Completed |
| Facilities Analytics       | ✅ Completed |
| Staff Analytics            | ✅ Completed |
| Treatment Analytics        | ✅ Completed |
| Geographic Performance     | ✅ Completed |
| Insights & Recommendations | ✅ Completed |
| Final Power BI Dashboard   | ✅ Completed |
| Project Documentation      | ✅ Completed |

---

# 🔐 Data Authenticity & Integrity

This documentation represents the final Power BI project as implemented.

### Data Handling Principles

* The original dataset remains unchanged.
* No artificial records are added to the source data.
* Dashboard values are based on the Power BI model and its analytical measures.
* No dashboard values are intentionally fabricated for documentation.
* Table names and fields correspond to the final Power BI model.
* Any future transformations should be maintained separately from the original source data.

---

# 🏁 Final Outcome

The **Healthcare Operations Intelligence Dashboard** provides an integrated Power BI environment for analyzing:

* Patients
* Admissions
* Treatments
* Staff
* Beds
* Facilities
* Departments
* Dates
* Cities
* Operational KPIs

The final model combines fact tables, dimension tables and a dedicated measures table to support interactive healthcare operations analysis.

The solution transforms operational healthcare information into:

```text
Data
 ↓
Data Model
 ↓
Measures
 ↓
Dashboard
 ↓
Analysis
 ↓
Insights
 ↓
Recommendations
 ↓
Management Decision Support
```

---

# 📌 Final Project Statement

**Healthcare Operations Intelligence Dashboard** is an individual Power BI-based healthcare analytics solution that integrates patient, admission, treatment, staff, bed and facility information into an interactive decision-support dashboard.

The project focuses on understanding hospital operations through structured data analysis, DAX-based measures and interactive visualizations while maintaining the integrity of the underlying dataset.

**Project:** Development of a Healthcare Operations Intelligence Dashboard with Decision Analytics
**Project Type:** Individual Project
**Platform:** Microsoft Power BI
**Final Report File:** Hospital_Management_Dashboard by harshada-2.pbix
