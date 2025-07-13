## 📊 PhonePe Analysis Power BI Dashboard

📁 Project Overview
This project presents a comprehensive analysis of PhonePe's digital transaction trends from 2018 to 2022 using Power BI. The dashboard provides insights into transaction volume and patterns across different Indian states, regions, years, and transaction types.

Dataset Source:
📌 PhonePe Pulse Data 2018–2022 on Kaggle - https://www.kaggle.com/datasets/nirmalcodes/phonepe-pulse-data-2018-2022

✅ Project Objectives
- Total transaction amount and count over the years.
- Yearly growth trends.
- State-wise and region-wise breakdown.
- Analysis by transaction type (e.g. P2P, merchant payments, bill recharges).
- Insights into user registration, app usage, and even device brand usage.

🧩 Workflow & Methodology

1. Data Collection
- Imported data from Kaggle dataset covering PhonePe digital transactions (2018–2022).
- Data includes multiple CSV files containing transaction details by state, region, year, and type.

2. Data Cleaning (Power Query Editor)
- Fixed column data types (dates, numerics, text).
- Removed duplicate entries.
- Handled null and missing values.
- Merged/removed unnecessary columns.
- Replaced inconsistent entries for consistency.

3. Data Modeling
- Established relationships between multiple tables (if applicable).
- Created star schema for optimized querying.

4. DAX (Data Analysis Expressions)
- Created measures (e.g., Total Transaction Amount, Total Transaction Count).
- Used calculated columns for derived fields.
- Created additional DAX logic for performance and filtering.

📈 Key Insights
- ₹121.41 Trillion total transaction volume and 71.72 Billion total transaction count from 2018–2022.
- Telangana, Maharashtra, and Karnataka were the top states in transaction volume.
- Southern and Western regions dominated the transaction landscape.
- Peer-to-Peer and Merchant Payments accounted for the highest transaction shares.
- Exponential growth in digital payments observed year-over-year.

🛠 Tools & Technologies
- Power BI	->  Data modeling & dashboard
- Power Query-> 	Data cleaning & transformation
- DAX	 ->      Calculated measures & columns
- Kaggle->   	Data source

## Dashboard :
![phone pe dashboard_pages-to-jpg-0001](https://github.com/user-attachments/assets/970b7c50-7b81-4d77-9bc5-baef103606c2)
![phone pe dashboard_page-0002](https://github.com/user-attachments/assets/ef673dce-76ad-4b8b-9848-62216583d4c7)


📌 Future Enhancements
- Add geo-mapping visualizations for better spatial representation.
- Incorporate user segmentation (rural vs. urban usage).
- Automate data refresh with live API if PhonePe provides public endpoints.
