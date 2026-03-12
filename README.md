# Healthcare Data Analytics Dashboard

## Project Overview

This project performs exploratory data analysis and visualization on a healthcare dataset containing **55,000+ patient records**. The objective is to analyze patient demographics, medical conditions, hospital admissions, and billing patterns to generate meaningful insights.

The project demonstrates a **complete data analytics workflow using Python and Power BI**, including data cleaning, feature engineering, and interactive dashboard development.

---

## Live Dashboard

You can explore the interactive Power BI dashboard here:

https://app.powerbi.com/links/7oRvAj1Fug?ctid=2c5bdaf4-8ff2-4bd9-bd54-7c50ab219590&pbi_source=linkShare

---

## Tech Stack

Python – Data cleaning and preprocessing
Pandas – Data manipulation and analysis
Power BI – Interactive dashboard and data visualization
GitHub – Version control and project documentation

---

## Dataset Information

The dataset contains healthcare-related information for **55,500 patients**.

### Key Columns

* Patient Name
* Age
* Gender
* Blood Type
* Medical Condition
* Hospital
* Insurance Provider
* Billing Amount
* Admission Type
* Medication
* Test Results
* Date of Admission
* Discharge Date

### Engineered Features

Additional features were created during data preprocessing:

* **Stay_Days** – Hospital stay duration
* **Age_Group** – Age category segmentation
* **Billing_Category** – Low, Medium, High billing segmentation

---

## Project Workflow

Raw Dataset
↓
Python Data Cleaning (Pandas)
↓
Feature Engineering
↓
Exploratory Data Analysis
↓
Power BI Dashboard Visualization

---

## Data Cleaning Steps

The dataset was preprocessed using Python:

* Standardized text formatting for names and categorical values
* Converted admission and discharge dates to datetime format
* Created hospital stay duration feature
* Created age group categories for demographic analysis
* Segmented billing amounts into categories
* Checked for missing values and inconsistencies

---

## Power BI Dashboard

The Power BI dashboard provides interactive insights into healthcare data.

### Key Metrics

* Total Patients
* Average Billing Amount
* Average Hospital Stay Duration

### Visualizations Included

* Patient distribution by gender
* Age group analysis
* Most common medical conditions
* Admission type distribution
* Billing amount by medical condition
* Insurance provider analysis
* Hospital performance analysis
* Patient stay duration analysis

### Interactive Features

* Dashboard navigation buttons
* Reset filter button
* Dynamic slicers
* Interactive charts

---

## Dashboard Preview

A preview of the dashboard is shown below.

(Add screenshot here)

---

## Key Insights

* Certain medical conditions result in longer hospital stays.
* Emergency admissions account for a large share of hospital visits.
* Billing amounts vary significantly across hospitals.
* Age groups show different patterns in hospitalization and treatment.

---

## Repository Structure

```
Healthcare-Data-Analytics/
│
├── data/
│   └── clean_healthcare_data.csv
│
├── notebooks/
│   └── healthcare_analysis.ipynb
│
├── powerbi/
│   └── healthcare_dashboard.pbix
│
├── images/
│   └── dashboard_preview.png
│
├── requirements.txt
└── README.md
```

---

## How to Run This Project

1. Clone the repository

git clone https://github.com/yourusername/Healthcare-Data-Analytics.git

2. Install dependencies

pip install -r requirements.txt

3. Open the Jupyter notebook

notebooks/healthcare_analysis.ipynb

4. Open the Power BI dashboard

powerbi/healthcare_dashboard.pbix

---

## Future Improvements

* Add predictive analytics for hospital stay duration
* Integrate additional healthcare datasets
* Deploy dashboards with cloud-based analytics tools
* Automate data pipeline updates

---

## Author

Anand Dubey
B.Tech Computer Science Engineering
Bennett University

Focused on **Data Analytics, Python, and Business Intelligence tools like Power BI**.
Portfolio: https://portfolio-upgrade-rho.vercel.app/
