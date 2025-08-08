#  Hospital Management System –  Aggregate Functions & Grouping

This project showcases the use of **SQL aggregate functions** and **grouping operations** within a Hospital Management System database.  
It is developed using **Oracle SQL\*Plus** and focuses on summarizing data using:

- Aggregate functions (`SUM`, `COUNT`, `AVG`)
- Grouping with `GROUP BY`
- Filtering grouped data using `HAVING`

---

##  Files Included

- **`task4_queries.sql`** – SQL script containing:
  - Table alteration to add a numeric column (`BILL_AMOUNT`)
  - Sample data updates to populate billing amounts
  - Aggregate queries using `SUM`, `COUNT`, and `AVG`

- **`README.md`** – This documentation file describing the task, structure, and learning outcomes

---

##  Tables and Column Modifications

In addition to the base schema from the main project, this task includes:

- **APPOINTMENT**  
  Extended with a new numeric column `BILL_AMOUNT` to allow billing calculations.

---

##  Operations Performed

- **ALTER TABLE** used to add `BILL_AMOUNT` to the `APPOINTMENT` table
- **UPDATE** used to assign sample billing values to existing appointments
- **Aggregate queries** performed using:
  - `COUNT()` – for counting rows and distinct values
  - `SUM()` – for total billing amounts per doctor and appointment date
  - `AVG()` – for average billing across doctors and appointments
- **GROUP BY** used to categorize data (e.g., by department, doctor, or gender)
- **HAVING** used to filter groups based on aggregate conditions

---

##  Key Concepts Demonstrated

- Use of aggregate functions: `SUM`, `COUNT`, `AVG`
- Grouping and filtering data using `GROUP BY` and `HAVING`
- Application of numeric operations on extended columns (`BILL_AMOUNT`)
- Real-world data summarization tasks within a healthcare database

---

##  How to Run

1. Open Oracle SQL\*Plus or any Oracle-compatible SQL environment.
2. Run the base `hospital_schema.sql` to create tables and insert data.
3. Execute the `task4_queries.sql` script to:
   - Add the `BILL_AMOUNT` column
   - Update sample values
   - Run all aggregate queries
4. Analyze the output and validate groupings and summaries.

---

##  Learning Outcomes

- Understand and apply aggregate functions in SQL
- Use `GROUP BY` to categorize and summarize tabular data
- Filter grouped data using `HAVING`
- Modify tables to support numeric analysis (e.g., billing summaries)
- Analyze hospital data such as:
  - Doctor workloads
  - Billing per patient/doctor
  - Appointment trends

---

##  Requirements

- Oracle SQL\*Plus or compatible SQL tool
- Oracle database (any edition)
- Hospital schema from the main project

---
