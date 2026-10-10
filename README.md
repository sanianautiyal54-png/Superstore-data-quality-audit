# Superstore Data Quality Audit

## Project Overview
This project focuses on checking the quality of the Superstore dataset using Python and Pandas. It identifies missing values, duplicate records, invalid values, and data consistency issues.

## Objectives
- Identify missing values and duplicate records.
- Check invalid sales, quantity, and discount values.
- Validate order dates and shipping dates.
- Create an issue log with the number of affected records.
- Clean the dataset and prepare the final deliverables.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Google Colab
- Microsoft Excel

## Dataset
The Superstore dataset contains information about orders, customers, products, sales, quantity, discount, and profit.

## Data Quality Checks
- Missing values
- Duplicate rows
- Sales values less than or equal to zero
- Quantity values less than or equal to zero
- Discounts outside the range of 0 to 1
- Shipping dates earlier than order dates
- Negative profit values
- Repeated Order ID and Product ID combinations

## Validation Rules
- Required values should not be missing.
- Exact duplicate rows should be reviewed.
- Sales and quantity should be greater than zero under the selected validation rules.
- Discount values should be between 0 and 1.
- Ship Date should be on or after Order Date.

Negative profit may represent a genuine business loss, so it is not automatically treated as an error. Repeated order-product combinations are also checked before any records are removed.

## Data Cleaning
- Created a separate copy of the original dataset.
- Removed exact duplicate rows, if any.
- Removed extra spaces from text values.
- Checked date formats and data types.
- Reviewed potential data quality issues.

## Project Deliverables
1. **Audit Report:** Summary of data quality checks and results.
2. **Issue Log:** List of identified issues and affected row counts.
3. **Cleaned Sample:** Cleaned dataset saved as a CSV file.

## Output Files
- `Superstore_Audit_Report.xlsx`
- `Superstore_Cleaned.csv`
- `Superstore_Data_Quality_Audit.ipynb`

## How to Run the Project
1. Open the notebook in Google Colab.
2. Upload the Superstore Excel dataset.
3. Run the code cells in order.
4. Review the audit results and issue log.
5. Download the generated output files.

## Conclusion
This project demonstrates how Python can be used to audit data quality, validate business rules, document issues, and prepare a cleaned dataset for further analysis.# Superstore-data-quality-audit
A Data Quality Audit project using Python and Pandas to identify missing values, duplicates, invalid data, and consistency issues in the Superstore dataset. Includes an audit report, issue log, and cleaned dataset.
