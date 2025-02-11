# Coffee Shop Sales Analysis

## Project Overview
This Excel project analyzes sales data from a coffee shop to derive key insights on revenue trends, product performance, and customer purchasing behavior.

## Objectives
### Objective 1: Data Preparation
1. Add a new column to calculate **Revenue** using the formula:
   ```
   Revenue = Price * Quantity
   ```
2. Extract **Month** and **Day of the Week** from the transaction date to enable time-based analysis.
3. Extract **Hour** from the transaction time to analyze sales trends by time of day.

### Objective 2: Data Analysis Using PivotTables
1. Create a **PivotTable** on a new sheet to display **Revenue by Month**.
2. Add two additional **PivotTables** (on the same sheet) to analyze:
   - The **number of transactions by product category**, sorted in descending order.
   - The **number of transactions and revenue by product type**, sorted in descending order and filtered to the **top 15 product types by transactions**.

### Objective 3: Data Visualization and Dashboard Creation
1. **Add Pivot Charts**:
   - A **line chart** to show revenue by month.
   - **Column charts** to display transactions by day of the week and hour of the day.
   - A **bar chart** to show transactions by product category.
2. **Assemble a dashboard layout**:
   - Organize the charts and include space for the PivotTable showing the **Top 15 product types**.
3. **Add a slicer for store location**:
   - Connect the slicer to all PivotTables on the sheet for interactive filtering.
4. **Final Adjustments**:
   - Improve formatting, alignment, and polish the dashboard for better readability and presentation.

## Steps to Reproduce
1. **Load Data**: Import the coffee shop sales dataset into an Excel worksheet.
2. **Add Computed Columns**:
   - Use Excel formulas or Power Query to calculate Revenue, Month, Day of the Week, and Hour.
3. **Insert PivotTables**:
   - Navigate to the "Insert" tab and select "PivotTable."
   - Choose the appropriate data range and place the PivotTables on a new sheet.
   - Configure sorting and filtering options as required.
4. **Create Pivot Charts & Dashboard**:
   - Insert charts and arrange them in an easy-to-read layout.
   - Add a slicer and link it to relevant PivotTables.
   - Adjust formatting for clarity and professionalism.

## Tools & Features Used
- Excel formulas for calculated columns
- PivotTables for data summarization
- PivotCharts for visual representation
- Sorting and filtering for optimized data analysis
- Slicers for interactive data filtering
- Dashboard layout for structured insights

## Expected Insights
- Monthly revenue trends to identify peak sales periods.
- Most popular product categories based on transaction volume.
- Top-selling product types driving revenue and customer demand.
- Sales distribution across different times of the day and week.

---
This project provides a structured approach to analyzing sales data, helping business owners optimize pricing, inventory, and marketing strategies based on data-driven insights.

