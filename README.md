Bookstore Finance Evaluation

This repository provides a comprehensive analysis of a bookstore chain’s financial and payroll data. The included SQL queries address:

* Revenue versus debt obligations – assessing quarterly net revenue relative to loan interest.
* Employee payroll and tenure – identifying longest-tenured staff and calculating cumulative gross pay.
* Payroll reconciliation – detecting discrepancies between payroll liabilities and recorded bank withdrawals.
* Store-level payroll insights – summarizing active employees and total gross payroll by location.

All scripts are implemented in T-SQL, designed to ensure accuracy in reporting and handle missing or incomplete data. The datasets include Employees, Payroll, Sales, Loans, and Checking Balanced Dataset.

Datasets:
* Bookstore Checking Balanced Dataset.csv
* bookstore_employees.csv
* bookstore_loans.csv
* bookstore_payroll.csv
* bookstore_sales.csv

**IMPORTANT:**
When importing these CSV files into your database, rename them to the following table names so the SQL queries function correctly:

* Bookstore Checking Balanced Dataset.csv → dbo.[Checking Balanced Dataset]
* bookstore_employees.csv → dbo.Employees
* bookstore_loans.csv → dbo.Loans
* bookstore_payroll.csv → dbo.Payroll
* bookstore_sales.csv → dbo.Sales
