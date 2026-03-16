# E-Commerce Sales & Profitability Analysis 📊

## Overview
This project demonstrates an automated End-to-End Data Analysis workflow. I used **Python** to process raw e-commerce sales data (JSON) and automate the creation of a styled **Excel** report. Following the automation, I performed business and strategic analysis in Excel to uncover insights regarding pricing and profitability.

## Technologies Used
* **Python:** Data processing, JSON parsing.
* **openpyxl:** Excel automation, conditional formatting, and cell styling via code.
* **Excel:** Pivot Tables, What-If Analysis (Data Tables), Scatter Plots.

## Project Workflow
1. **Data Ingestion:** Reading raw JSON data containing product costs, selling prices, and sales volume.
2. **ETL & Automation (Python):** * Calculated Total Revenue, Total Profit, and **Profit Margin** for each item.
   * Generated an organized Excel workbook.
   * Applied automated conditional formatting to highlight inventory movement (e.g., items sold > 100).
3. **Business Intelligence (Excel):**
   * **Sensitivity Analysis:** Built a What-If Data Table to test price elasticity (e.g., changing a product's price from 90₪ to 200₪ to find the optimal revenue point).
   * **Visualizations:** Created a Scatter Plot (Price vs. Quantity) to identify "Star Products".

## Key Business Insights
* Discovered the difference between gross revenue and actual profit margins, highlighting low-cost/high-margin products that justify increased marketing budgets.
* Visualized how price drops impact overall revenue through automated sensitivity scenarios.

## Files in this Repository
* `store_data.json`: The raw input data.
* `sales_automation.py`: The Python script handling the logic and Excel generation.
* `store_data.xlsx`: The final output containing the report and analytical models.
