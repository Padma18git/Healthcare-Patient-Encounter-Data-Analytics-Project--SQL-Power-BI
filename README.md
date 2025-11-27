# Healthcare-Patient-Encounter-Data-Analytics-Project--SQL-Power-BI
This project demonstrates end-to-end healthcare analytics using PostgreSQL, SQL queries, data validation methods, and a Power BI dashboard.

## 🔹 Features
- Patient & Visit database built in PostgreSQL
- Data extraction queries for demographics and visit patterns
- Data validation rules (completeness, duplicates, referential integrity)
- Evaluation queries including visit trends, insurer analysis, patient risk flags
- Interactive Power BI dashboard

## 🔹 Tools Used
- PostgreSQL (pgAdmin) — data modeling & SQL
- Power BI Desktop — dashboard visualization
- GitHub — version control & portfolio presentation

## 🔹 Project Structure
- `sql/` → table creation, inserts, and analysis SQL
- `powerbi/` → Power BI .pbix dashboard
- `screenshots/` → visuals and reports

- ## 🔹 Methodology
  ## 1. Database Design
     ## Tables Created
 ## patients
  - patient_id
  - first_name
  - last_name
  - date_of_birth
  - gender
  - phone
## visits
- visit_id
- patient_id
- visit_date
- provider_id
- reason_of_visit

## lab results table
- lab_id
- patient_id
- test_name
- result_value
- result_unit
- test_date

## insurance claims table
- claim_id
- patient_id
- visit_id
- claim_amount
- claim_status
- submitted_date
- paid_date

- All tables created included in /SQL/create table queries.doc.

## 2. Insert sample healthcare data
Inserted the values for data extraction, validation, and analysis.
- All data inserted in to tables are included in /SQL/Insert data into table queries.doc.

## 3. Data Extraction SQL queries
- All data extraction queries in PostGreSql are included in /SQL/Data Extraction queries.doc.

## 4. Data validation queries
(to check for missing values, wrong dates, duplicate patients, invalid claims, etc.)
- All data validation queries in are included in /SQL/Data validation queries.doc.

## 5. Data Quality Rules 
## Completeness Rules 
1.	Patient first/last name must not be NULL
2.	Patient date of birth must be present
3.	Visits must have a reason
4.	Lab results must have a test name, value, and date
5.	Claims must have amount and status
- All data quality rules and queries are included in /SQL/Data quality rules.doc.

## 6. Data evaluation queries & Insights SQL queries
- All data evaluation and KPI metrics queries are included in /SQL/Data evaluation queries.doc.

## 🔹 Power BI Dashboard
## The final dashboard includes:
## KPI Cards
- Total Visits Per Provider
- Total No of Patient Visits
- Sum of Average Claim Amount
- Top 5 Highest Claim Amount

## Visuals
- Claims Processed Late Table
- Sum of Total Claimed BarChart
- Sum of Total Visits Barchart
- Sum of Claim Amount By Claim Status PieChart

##  A clean, 1-page dashboard with:
- Row 1 → KPI Cards
- Row 2 → Visuals and Table

## 🔹 How to reproduce
- Clone the repo
- Run SQL scripts in PostgreSQL
- Export query results to CSV (optional)
- Open the Power BI file
- load CSVs
- The PowerBI dashboard link is included in /PowerBI dashboards of the project and a screenshot of the Final Dashboard.
- All the outputs of the queries are in /Screenshots of the Output/SQL queries output screenshots.doc







 

