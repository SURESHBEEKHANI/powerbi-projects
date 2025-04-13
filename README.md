# Power BI Projects

This workspace contains Power BI projects for financial and retail sales dashboards. Below is an overview of the project structure and contents.

## Structure

- **Credit_Card_Financial_Dashboard/**
  - `Credit_Card_Financial_Dashboard.pbix` – Power BI report file for visualizing credit card financial data.
  - `Credit_Card_Financial_Dashboard.pdf` – Documentation or export of the Power BI report.
  - `SQL Query - Financial Dashboard Data.sql` – SQL query file used to extract or manipulate data for the dashboard.
  - **Data/**
    - `cc_add.csv` – Data file (likely used for credit card related addresses or additional info).
    - `credit_card.csv` – Primary data file for credit card transactions or details.
    - `cust_add.csv` – Customer address data.
    - `customer.csv` – Main customer data file.

- **retail-sales-dashboard/**
  - `retail-sales-dashboard.pbit` – Template file for the retail sales dashboard.
  - `Retail Superstore Sales Performance Dashboard in Power BI.pdf` – PDF documentation or static version of the retail sales dashboard.

## Usage

1. **Credit Card Financial Dashboard**
   - Open the `.pbix` file in Power BI Desktop.
   - Review and execute the provided SQL query to ensure data is correctly loaded.
   - Use the CSV data files from the `Data/` folder to refresh the dashboard data.

2. **Retail Sales Dashboard**
   - Use the `.pbit` template file to create or update the retail sales dashboard.
   - Refer to the accompanying PDF for insights and performance overview of the sales data.

## Additional Information

This workspace is managed under version control with `.gitignore` included to specify files and folders that should not be tracked. For licensing information, refer to the `LICENSE` file. See also the [original README](e:/powerbi-projects/README.md) for more project context.

Happy Reporting!