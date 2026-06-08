# ✈️ Airline Delay Analytics & Performance Monitoring

## 📌 Project Overview

This project analyzes airline operational performance and flight delays using Python and Power BI. The objective is to identify delay patterns, evaluate airline reliability, analyze delay causes, and provide actionable insights through interactive dashboards.

The project covers the complete analytics lifecycle, including data cleaning, preprocessing, exploratory data analysis (EDA), feature engineering, dimensional modeling, and dashboard development.

---

## 🎯 Business Objectives

* Monitor airline operational performance.
* Identify the main causes of flight delays.
* Analyze delay trends across months and weekdays.
* Compare airline carriers based on reliability and delay rates.
* Evaluate airport performance and operational bottlenecks.
* Estimate potential operational improvements through what-if analysis.

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Power BI
* Data Modeling (Star Schema)
* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization

---

## 📂 Dataset

The dataset contains historical flight operations data including:

* Flight schedules
* Departure and arrival times
* Delay durations
* Airline carriers
* Origin and destination airports
* Delay reasons
* Cancellation and diversion information

---

## 🔄 Project Workflow

### 1. Data Cleaning & Preprocessing

* Handled missing values.
* Processed HHMM time fields into analyzable formats.
* Standardized column naming conventions.
* Removed irrelevant and duplicate records.
* Created additional analytical features.

### 2. Feature Engineering

Generated:

* Departure Hour
* Arrival Hour
* Scheduled Departure Hour
* Scheduled Arrival Hour
* Time Period Categories

  * Morning
  * Afternoon
  * Evening

### 3. Exploratory Data Analysis (EDA)

Performed analysis to understand:

* Delay distribution
* Monthly trends
* Airline performance
* Airport performance
* Delay reasons
* Operational patterns

### 4. Data Modeling

Implemented a Star Schema data model.

#### Fact Table

**Fact_Flight_Delays**

Contains:

* Delay metrics
* Flight duration metrics
* Distance metrics
* Cancellation indicators
* Foreign keys to dimensions

#### Dimension Tables

* Dim_Date
* Dim_Carrier
* Dim_Origin_Airport
* Dim_Destination_Airport
* Dim_Time
* Dim_Flight

---

## 📊 Dashboard 1: Executive Summary

### KPIs

* Total Flights
* Total Delay Minutes
* Delay Rate %

### Visualizations

* Delay Rate Over Months
* Worst 10 Carriers by Delay Rate
* Delay Rate by Day of Week
* Delay Reason Distribution
* What-if Analysis for Delay Reduction
* Potential Time Savings Calculator

### Key Insight

Late Aircraft Delay and NAS Delay account for the majority of delay minutes across all carriers.

---

## 📈 Dashboard 2: Airline Delay Analysis

### Visualizations

* Carrier Delay Rank by Month
* Detailed Carrier Performance Metrics
* Reliability vs Volume Performance Matrix
* Delayed Flights Timeline
* Worst Performing Airports
* Delay Cause Analysis

### Key Insight

Several low-volume carriers exhibit significantly higher delay rates than major carriers, indicating operational efficiency challenges.

---

## ⭐ Star Schema Model

The project uses a dimensional model to improve reporting performance and analytical flexibility.

### Dimensions

* Date
* Carrier
* Origin Airport
* Destination Airport
* Time
* Flight

### Fact

* Flight Delay Facts

---

## 📸 Dashboard Preview

### Executive Summary Dashboard

*Add screenshot here*

### Airline Delay Analysis Dashboard

*Add screenshot here*

### Star Schema Model

*Add model screenshot here*

---

## 🚀 Key Outcomes

* Analyzed over 2 million flight records.
* Identified major contributors to operational delays.
* Built a scalable dimensional model for reporting.
* Developed executive-level and operational dashboards.
* Enabled data-driven decision making through KPI monitoring and scenario analysis.

---

## 👩‍💻 Author

**Rahma Osama**

Data Analyst | Python | SQL | Power BI

GitHub: https://github.com/Rahma-Osama
