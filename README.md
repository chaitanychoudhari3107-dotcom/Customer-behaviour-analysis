Customer Shopping Behaviour Analysis: End-to-End Portfolio Project
📌 Project Overview
This project simulates a professional corporate workflow to solve a real-world business challenge. It covers the complete data analytics life cycle: from initial data cleaning in Python to advanced database querying in MySQL, and interactive storytelling via Power BI.
🛠️ Tech Stack
Python (Pandas, SQLAlchemy, PyMySQL): Data cleaning and feature engineering.
SQL (MySQL): Advanced data analysis and business logic.
Power BI: Interactive KPI dashboarding and DAX measures.
Gamma AI: Stakeholder-ready presentation deck.
🔄 Project Workflow
Phase 1: Data Preparation (Python)
Category-Specific Imputation: Missing ratings filled using the median within each category to avoid data bias
.
Snake_Case Standardisation: All column names converted for code consistency and MySQL compatibility
.
Feature Engineering: Created age_group bins and converted textual frequencies into a numeric purchase_frequency_days column
.
Phase 2: Advanced Data Analysis (MySQL)
The cleaned data was migrated to a MySQL database (Port 3306)
. Key techniques used:
Customer Segmentation: Utilised CTEs and Case Statements to group customers into "New," "Returning," and "Loyal" segments
.
Advanced Ranking: Implemented Window Functions (ROW_NUMBER) to identify the top three products in every category
.
Phase 3: Interactive Dashboard (Power BI)
Database Connection: Connected Power BI directly to the MySQL server
.
DAX Measures: Developed measures for total customers, average spend, and average ratings
.
User Interaction: Integrated dynamic button slicers for real-time data exploration
.
💡 Key Findings
Top Segment: Young Adults drive the highest revenue
.
Shipping: Express Shipping correlates with higher average spending
.
Opportunity: Many repeat buyers are not yet subscribers, suggesting a target for loyalty campaigns
