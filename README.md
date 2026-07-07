# Data-Driven Policy Innovation

A data analytics project developed as part of a Datathon to analyze educational access, student retention, and dropout trends across India using large-scale public datasets.

## Live Demo

- **Visualization:** https://datathon-drab.vercel.app/
- **Presentation:** https://docs.google.com/presentation/d/1RR_FXRUs_VLhelqh4l3s26YOj5RvSALk/edit?usp=sharing

---

## Project Overview

This project combines educational and socioeconomic datasets to identify factors affecting student enrolment, retention, and dropout rates. The objective is to generate data-driven insights that can support evidence-based policy decisions for improving educational equity.

---

## Problem Statements

- Analyze dropout and retention patterns across urban and rural districts, categorized by gender and caste.
- Study the impact of school infrastructure and teacher availability on student retention.
- Examine the relationship between household income, parental education, employment status, and student enrolment.

---

## Datasets

### UDISE
Contains district and school-level educational information such as:
- Student enrolment
- Dropout rates
- Teacher availability
- School infrastructure

### NFHS
Contains demographic and socioeconomic information including:
- Household income
- Parental education
- Employment status
- Urban/Rural classification

---

## Methodology

1. Data cleaning and preprocessing
2. Merging UDISE and NFHS datasets
3. Exploratory Data Analysis (EDA)
4. Correlation and trend analysis
5. Interactive dashboard development
6. Policy insight generation

---

## Key Insights

- Rural districts generally exhibit higher dropout rates than urban districts.
- Teacher availability and functional school infrastructure are positively associated with better retention.
- Lower household income and parental education are strongly linked to increased dropout rates.
- Significant disparities exist across gender and caste groups.

---

## Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy
- **Visualization:** React.js
- **Environment:** Jupyter Notebook
- **Deployment:** Vercel

---

## Repository Structure

```
Datathon-main/
│── code.ipynb
│── datathon.ipynb
│── feature importance_rf.ipynb
│── analysis_ready_dataset_final.csv
│── analysis_ready_dataset copy.csv
│── datafile_nfhs.csv
│── dropout_retention_rates_corrected.csv
│── Presentation.pptx
└── README.md
```

---

## Results

- Analyzed over one million records from multiple public datasets.
- Built an interactive dashboard for exploring district-level educational trends.
- Generated actionable policy recommendations based on statistical analysis and visualization.



