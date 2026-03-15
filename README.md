# Digital Payments Fraud Monitoring & Analysis

## Project Overview
This project detects and monitors potential fraudulent transactions in digital payment data using Power BI analysis and visualization. It includes data cleaning in Power Query Editor and analytical dashboards for fraud risk monitoring, behavior trends, and actionable insights.

## Data Source
- Source: Kaggle
- Dataset: Digital payments/fraud transactions dataset (downloaded from Kaggle repository)

## Tools Used
- Data cleaning: Power BI Power Query Editor
- Analysis & visualization: Power BI Desktop
- Output: Power BI reports / dashboards

## Folder Structure
- `Raw Data/` - Original datasets exported from Kaggle
- `Clean Data/` - Cleaned and transformed tables from Power Query
- `Result/` - Final report outputs, visuals, and analysis summary
- `Description/Description.txt` - Project notes and dataset descriptions

## Data Cleaning Process (step-by-step)
1. **Import raw CSV files** into Power BI.
2. **Inspect columns** and data types (transaction ID, timestamp, amount, merchant, customer, fraud label, etc.).
3. **Remove duplicates** and invalid transactions.
4. **Handle missing values** with fill, replace, or row exclusions.
5. **Standardize categories** (payment type, merchant category, location labels).
6. **Create date/time features** (transaction date, hour, day of week, month).
7. **Add fraud risk flags** (binary fraud label, high-risk category, unusual amount thresholds).
8. **Load clean dataset** into Power BI model for measures and visual analysis.

## Analysis Workflow
1. Define key questions:
   - What percentage of transactions are fraudulent?
   - Which merchants or categories have the highest fraud rates?
   - How does fraud trend over time (daily/weekly/monthly)?
   - Which transaction amounts, locations, or user behaviors indicate higher risk?
2. Build Power BI measures:
   - Total transactions
   - Fraud count, fraud rate
   - Average amount by fraud status
   - Fraud by merchant/category
3. Create visuals:
   - Time series fraud trend
   - Fraud rate by merchant and payment type
   - Heatmaps for risky hours/days
   - Segment comparisons for customer groups
4. Validate with data drill-down and filter interactions.
5. Document findings and recommendations in the report.



