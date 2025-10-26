# Vaccination-Data-Analysis-and-Visualization
## Project Overview
This project analyzes global vaccination data to uncover trends in coverage, disease rates, and vaccine effectiveness. Using Python for data cleaning, SQL for database storage, and Power BI for interactive dashboards, it provides actionable insights to enhance vaccination strategies and improve public health outcomes globally.

## Table of Contents
- [Business Use Cases](#Business-Use-Cases)
- [Data Sources](#Data-Sources)
- [Methodology](#Methodology)
- [Technical Tags Used](#Technical-Tags-Used)
- [Deliverables ](#Deliverables)

## Business Use Cases
- **Public Health Strategy:**
  - Evaluate vaccination programs across regions and populations.
  - Prioritize areas with low vaccination coverage for focused efforts.
  
- **Disease Prevention:**
  - Identify diseases with high incidence rates despite vaccinations, suggesting areas for improvement.
  - Support policies on booster vaccines or new vaccine introductions.
- **Resource Allocation:**
  - Plan targeted resource distribution to regions with low coverage and forecast vaccine demand.
  - Forecast vaccine demand based on current trends for better supply chain management.

- **Global Health Policy:**
  - Provide data-driven recommendations for vaccination policies and support governments with evidence on vaccine effectiveness.

## Data Sources
- **Coverage Data:** Data on vaccination rates by region, year, target populations, and doses administered.
- **Incidence Rate:** Rates of disease occurrence by country and year.
- **Reported Cases:** Number of disease cases reported for specific regions and years.
- **Vaccine Introduction:** Information on whether a vaccine has been introduced in a country.
- **Vaccine Schedule Data:** Details on the dose or round of vaccines in the immunization schedule.

## Methodology
1. **Data Cleaning**
   - **Handling Missing Data:** Address incomplete records by imputing missing values or removing them as necessary.
   - **Standardizing Units:** Ensure consistency in measurement units across datasets, such as percentage coverage and reported case numbers.
   - **Date Formatting:** Maintain uniform date formats across tables to facilitate seamless integration and analysis.
2. **SQL Database Setup**
   - **Table Creation:** Store the structured and cleaned data in relational SQL tables, including vaccination data, disease incidence, and antigen details.
   - **Data Normalization:** Organize data into separate entities (e.g., vaccines, diseases, locations, and year periods) to minimize redundancy and enhance efficiency.
   - **Ensuring Data Integrity:** Implement primary and foreign key constraints to maintain referential integrity and data consistency.
4. **Power BI Integration**
   - **Database Connectivity:** Connect Power BI to the SQL database using its SQL connector to pull relevant tables for analysis.
   - **Interactive Dashboard Development:** Build dynamic reports with user-friendly filters and slicers for exploratory data analysis.
6. **Data Visualization in Power BI**
   - Build interactive dashboards with filters and slicers for user-friendly exploration of vaccination data.
   - Visualize key metrics such as vaccination rates, disease incidence, and antigen coverage over time and across regions.
   - Using line charts and bar graphs to track vaccination rates and disease trends over time.
   - Highlight regional variations in vaccination coverage and disease incidence.
   - Analyze correlations between vaccination coverage and disease incidence across different countries or regions.
   - Track progress toward vaccination and health targets.
8. **Exploratory Data Analysis (EDA)**
   - Analyze vaccination coverage, disease trends, and regional disparities using statistical summaries and correlation analysis.
   - Utilize visual analytics (e.g., bar charts, and trend lines) to uncover patterns, identify low-coverage areas, and evaluate the impact of immunization programs on disease reduction.

## Technical Tags Used
Python, SQL, EDA, Power BI, Data Cleaning, Data Analysis, Data Visualization, Healthcare Analytics, Public Health

## Deliverables
- **Python:** Scripts for data extraction and cleaning.
- **SQL Database:** Structured and normalized database containing the cleaned data.
- **Power BI Reports:** A set of interactive reports and dashboards showcasing key insights.
- **Documentation:** Detailed documentation explaining the process, challenges faced, and solutions implemented.

## Dashboard Output
https://app.powerbi.com/groups/me/reports/732f3905-abb5-4187-a78c-228c147c5394/8eea1f8e64348503da22?experience=power-bi
![image](https://github.com/user-attachments/assets/adcdd353-0488-4805-804f-8cc34e7ec0bc)
![image](https://github.com/user-attachments/assets/cfa5fc6d-9601-4e80-a9a8-d27b2c13f3cf)
![image](https://github.com/user-attachments/assets/3946bf2c-66fd-4ab1-b49a-2c6f0e6d40d5)

