📌 Project Overview
This project presents a comprehensive Bank Loan Analytics Dashboard built to analyze and visualize loan disbursement, collection, portfolio quality, and risk metrics. The dashboard provides actionable insights for banking stakeholders using real-world style financial data.

🛠️ Tools & Technologies Used
ToolPurposePower BIInteractive loan analytics dashboardTableauVisual data exploration and reportingExcel (XLSM)Data preparation, KPI calculation, macrosSQL (MySQL)Data extraction, KPI queries, aggregations

📁 Project Structure
Bank-Loan-Analytics-Project/
│
├── 📊 Loan_Dashboard.pbix               # Power BI Dashboard
├── 📈 Loan dashboard.twbx               # Tableau Dashboard
├── 📈 Bank debit and credit dashboard.twbx  # Tableau - Debit & Credit
├── 📋 Final Loan dashboard.xlsm         # Excel - Loan Data
├── 📋 Final Debit & Credit Dashboard.xlsm   # Excel - Debit & Credit Data
├── 🗄️ banking credit and debit sql query.sql  # SQL Queries
├── 🗄️ SQL query for KPI.sql             # SQL KPI Queries
├── 🖼️ powerbi dashboard 1.jpeg          # Dashboard Screenshot
└── 📄 README.md                         # Project Documentation

📊 Dashboard Features
Power BI Dashboard

KPI Cards — Total Loan Funded (732.70M), Total Loans (65.54K), Total Collection (814.90M), Total Distributed (750.97M), Total Interest (155.29M)
Disbursement Trend — Monthly loan distribution and number of loans
Branch Wise Performance — Total interest, revenue, and fees by branch
Product Group Wise Loan — Home Loan, Services, Business, Trade breakdown
Status Wise Distribution — Active, Fully Paid, Net-Off, Transferred
State Wise Distribution — Loan distribution across Indian states
Grade Wise Distribution — Loan amounts by credit grade (A, B, C, D)
Religion & Age Wise Analysis — Demographic loan distribution
Loan Maturity Profile — Maturity period breakdown
Data Quality Overview — Missing/unverified data tracking
Risk KPIs — Default count (1020), Delinquent count (7106), Default rate (1.56%), Delinquent rate (10.84%)

SQL KPIs Covered

Total Credit & Debit Amount
Credit to Debit Ratio
Net Transaction Amount
Account Activity Ratio
Transactions per Day / Week / Month
Total Transaction Amount by Branch
Transaction Volume by Bank
Transaction Method Distribution
Branch Transaction Growth (Monthly)
High-Risk Transaction Flagging (>4000)
Suspicious Transaction Frequency
Top 10 Customers by Transaction Amount
Average Transaction Amount
Daily Net Cash Flow


🔍 Key Insights

Home Loans dominate the portfolio at ₹278M, followed by Services (156M) and Business (83M)
Active Loans account for the largest share at ₹412M
Default Loan Rate stands at 1.56% with 1,020 defaults
Delinquent Loan Rate is 10.84% with 7,106 delinquent accounts
19.55% of loans fall under data quality concerns (unverified)
No Verified Loans count: 16.92K — flagged for review


🚀 How to Use
Power BI

Download Loan_Dashboard.pbix
Open in Power BI Desktop
Use slicers — Branch Name, State Name, Loan Status — to filter data
Navigate pages via the left sidebar or bottom tabs

Tableau

Download Loan dashboard.twbx
Open in Tableau Desktop or Tableau Public

SQL

Open banking credit and debit sql query.sql in MySQL Workbench
Run against your bank_transactions_db database
Execute individual KPI queries as needed

Excel

Open Final Loan dashboard.xlsm
Enable macros when prompted
Explore pivot tables and KPI sheets


📈 Filters Available in Dashboard
FilterOptionsBranch NameAll branchesState NameAll Indian statesLoan StatusActive, Fully Paid, Net-Off, Transferred

👤 Author
Anil Mattipa

GitHub: @AnilMattipa


📄 License
This project is for educational and portfolio purposes.


⭐ If you found this project useful, consider starring the repository!
