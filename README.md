# Maine Access to Care Analytics Dashboard
## 📊 About This Project

This project focuses on understanding access to care across counties in Maine. The goal was to simulate a real-world healthcare BI scenario where messy operational data needs to be cleaned, standardized, modeled, and turned into meaningful insights for leadership.

I wanted to build something practical, not overly complex, but realistic enough to reflect the kinds of problems healthcare systems actually deal with:
- Long appointment wait times
- Rural vs metro access gaps
- Missed appointments and lost capacity
- Provider supply vs population demand

## 🎯 Problem Statement

In healthcare, “access” can mean many things. In this project, I focused on operational access:
- How long patients wait
- Where delays are concentrated
- Whether missed visits are contributing to backlog
- Whether provider capacity aligns with demand

Instead of just showing averages, I structured the dashboard to help answer "Where should we intervene first?"

## 🗂 Data Sources

I combined public reference data with simulated transactional data:

Public datasets:
- CMS Hospital General Information
- CMS Doctors & Clinicians file
- CDC NCHS Urban–Rural Classification
- County population data

Simulated dataset:
- Appointment-level records created in Python

Included realistic data issues like:
- Inconsistent status values
- Mixed visit types
- Missing booking dates
- Negative wait times
- Duplicate rows

The idea was to work with imperfect data just like real operational systems.

## 🛠 Tools

- Python (Google Colab) – to simulate appointment data

- Power BI – for modeling and visualization

- DAX – for metrics and composite scoring

- Power Query – for data cleaning and transformation

## 📈 Key Metrics

I kept the executive view focused on five meaningful indicators:

- Average Days to Appointment

- Patients Waiting Over 30 Days

- Missed Appointment Rate

- Completion Rate

These metrics balance delay, backlog severity, operational efficiency, and care delivery.

## 🔍 Access Pressure Index

To help prioritize intervention areas, I created a composite Access Pressure Index.

It combines:
- Average wait time (50%)
- Long-wait rate (30%)
- Lost appointment capacity (20%)

This is not meant to be a performance score.
It is a prioritization tool that helps identify which counties may require attention first.

## 💡 What This Dashboard Helps Answer
- Which counties are experiencing the longest waits?
- Are rural areas more affected?
- Are missed visits contributing to access problems?
- Is telehealth helping reduce no-shows?
- Is provider capacity aligned with population demand?

## 🚧 Assumptions

- Appointment data is simulated for demonstration purposes
- Weighting in the Access Pressure Index can be adjusted
-Provider-to-county mapping is simplified

This project is meant to demonstrate BI modeling, data cleaning, and operational insight, not represent actual Maine system performance.

## 📎 What This Project Demonstrates

- Handling messy healthcare-style data
- Building a clean star schema model
- Creating meaningful executive-level KPIs
- Designing visuals for non-technical users
- Translating operational metrics into actionable insight
- Creating meaningful executive-level KPIs
-Designing visuals for non-technical users
-Translating operational metrics into actionable insight

## 📬 Author

### Arthi Anbalagan
Business Intelligence & Healthcare Analytics
