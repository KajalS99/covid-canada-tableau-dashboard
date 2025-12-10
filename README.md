# COVID-19 in Canada – Tableau Dashboard

This repository contains my Tableau workbook **Project_Group_7.twbx**, built for a group project at Douglas College. The goal was to analyze COVID-19 case data for Canada and create an interactive dashboard that helps stakeholders quickly understand where cases are concentrated and which populations are most affected.

> Tools: **Tableau**, **Excel** (data cleaning)

---

## Data Source

This dashboard is built using the **Canada COVID-19** dataset from Kaggle:

[Canada COVID-19 – Kaggle Dataset](https://www.kaggle.com/datasets/jaswanthhbadvelu/canada-covid-19)

The dataset contains case-level information for COVID-19 in Canada, including region, age group, gender, transmission type, and case outcome.

---

## Key Questions

The dashboard is designed to answer questions such as:

- How are COVID-19 cases distributed across Canadian regions and provinces?
- What is the overall **recovery status** (recovered, not recovered, unknown) in the dataset?
- Which **age groups and genders** have higher case counts?
- How do **case outcomes (recovered, death, other)** vary by **age group** and **region**?

---

## Views in the Dashboard

- **Recovery Status**  
  Pie chart summarizing the share of cases that are recovered, not recovered, or unknown. Highlights that a large proportion of records have unknown recovery status, indicating potential data quality issues.

- **Cases by Age Group & Gender**  
  Stacked bar chart showing how case counts vary by age group and gender, allowing quick comparison of demographic patterns.

- **Case Outcome by Region**  
  Bar chart comparing recovery, death, and other outcomes across regions (Atlantic, BC, Ontario, Prairies).

- **Case Outcome by Age Group**  
  Stacked bar chart showing how outcomes change with age, emphasizing the increased number of deaths in the older age groups (especially 80+).

- **COVID-19 Cases by Region (Map)**  
  Filled map of Canada showing total case counts by province, with labels and colour intensity for quick identification of hot spots.

---
## Dashboard Preview

![COVID-19 Canada Dashboard](images/dashboard_overview.png)

---

## Files

- `Project_Group_7.twbx` – Packaged Tableau workbook with all worksheets and the final dashboard  
- `images/dashboard_overview.png` – Screenshot of the final dashboard

---

## Skills Demonstrated

- Data cleaning and preparation for visualization
- Building calculated fields and filters in Tableau
- Designing multi-view dashboards (bar charts, pie charts, map)
- Communicating insights with titles, captions, and labels
- Basic geospatial visualization using province-level data

---

## How to Open the Workbook

1. Download `Project_Group_7.twbx` from this repository.
2. Open it in **Tableau Desktop** (or Tableau Public Desktop, if compatible).
3. Use the dashboard filters and interactive elements to explore the data.

## Download the Workbook

You can download the Tableau packaged workbook here:

[Download Project_Group_7.twbx]()



