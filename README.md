# SWYNEX Internship – Task 1: E-Commerce Sales Data Cleaning

## Project Overview

This project is part of my SWYNEX Internship – Task 1.

The objective of this task is to clean and transform an E-Commerce Sales dataset using Microsoft Excel and Power Query and prepare the data for further analysis.

## Dataset

The dataset contains e-commerce sales and customer-related information, including:

* Order details
* Customer information
* Order date and time
* Sales and discount information
* Payment details
* Shipping information
* Customer-related metrics

## Tools Used

* Microsoft Excel
* Power Query
* Power Query M Language

## Data Cleaning and Transformation

The following steps were performed using Power Query:

### 1. Import Dataset

Imported the E-Commerce Sales CSV dataset into Power Query.

### 2. Promote Headers

Promoted the first row of the dataset as column headers.

### 3. Correct Data Types

Reviewed and corrected the data types of the columns.

Examples:

* `order_date` → Date
* `order_time` → Time
* `customer_age` → Whole Number
* `customer_postal_code` → Text
* `quantity` → Whole Number
* Sales-related columns → Number
* `is_repeat_customer` → Logical

### 4. Handle Invalid Date Values

Removed rows containing errors in the `order_date` column.

### 5. Standardize Date Format

Applied the `en-US` locale to correctly interpret and standardize the `order_date` column.

### 6. Convert Discount Amount

Converted `discount_amount` into a numeric data type for accurate calculations.

### 7. Remove Duplicate Records

Removed exact duplicate rows from the dataset.

## Data Quality Checks

The following checks were performed:

* Checked for missing values
* Checked for duplicate records
* Checked column data types
* Checked invalid date values
* Checked numeric columns for consistency
* Reviewed identifier fields

## Important Data-Type Consideration

The `customer_postal_code` column was treated as **Text** because postal codes are identifiers and are not used for mathematical calculations. This also helps preserve leading zeros when applicable.

## Power Query Transformation Summary

The main transformations were:

1. Import CSV data
2. Promote headers
3. Apply appropriate data types
4. Remove errors from `order_date`
5. Standardize `order_date` using `en-US` locale
6. Convert `discount_amount` to number
7. Remove duplicate records

## Final Output

The cleaned and transformed E-Commerce Sales dataset was prepared in Excel after completing the Power Query data-cleaning process.

## Conclusion

This task helped improve the quality and consistency of the E-Commerce Sales dataset by correcting data types, handling invalid date values, converting numeric fields, and removing duplicate records.

The cleaned dataset is now prepared for further data analysis and reporting.
