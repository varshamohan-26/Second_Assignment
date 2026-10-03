# Second_Assignment
Data Cleaning and Transformation
# Product Data Cleaning Using Power Query

## Description

This assignment focused on cleaning, transforming, and formatting a product dataset using **Excel Power Query**. Excel was used for the final conditional formatting requirements.

## Tasks Completed

### 1. Handling Missing Values

- Identified missing values in the **Price** column.
- Replaced the missing Price values using the **median of the available Price values**.
- Identified missing values in the **Category** column.
- Filled the missing Category values based on the corresponding products.

**Power Query features used:**
- Filter
- Add Custom Column
- Replace/Remove Columns
- Rename Columns

### 2. Correcting Inconsistent Data

- Standardized **Product Name** capitalization using **Capitalize Each Word**.
- Corrected the inconsistent category value **"Electroni"** to **"Electronics"**.

**Power Query features used:**
- Transform → Format → Capitalize Each Word
- Replace Values

### 3. Removing Duplicate Records

- Checked the dataset for duplicate rows.
- Removed duplicate records based on the complete row.

**Power Query feature used:**
- Remove Duplicates

### 4. Splitting and Merging Columns

- Split the **Product ID** using the hyphen (`-`) delimiter.
- Created **Manufacturing Date** from the day and month portions of Product ID.
- Created **Country Code** from the country portion of Product ID.
- Merged **Brand Name** and **Product Name** to create a new **Product Brand** column.

**Power Query features used:**
- Split Column by Delimiter
- Merge Columns
- Rename Columns

### 5. Number Formatting

- Formatted the **Price ($)** column as **Currency**.
- Converted **Manufacturing Date** into a date format and displayed it as **DD-MM-YYYY**.

**Power Query feature used:**
- Change Data Type

### 6. Conditional Formatting

- Applied **Data Bars** to the **Price ($)** column to visually compare product prices.
- Applied Conditional Formatting to highlight **Electronics** in the **Category** column.

**Excel features used:**
- Conditional Formatting → Data Bars
- Conditional Formatting → Text that Contains

## Final Dataset

The final cleaned dataset contains:

- Manufacturing Date
- Country Code
- Product Brand
- Price ($)
- Quantity
- Category

## Learning Outcome

Through this assignment, I learned how to use **Power Query** for data cleaning, missing-value handling, data standardization, duplicate removal, splitting and merging columns, and data type conversion. I also learned how to use **Excel Conditional Formatting** to visually represent and analyze cleaned data.
