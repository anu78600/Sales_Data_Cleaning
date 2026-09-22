#  Sales Data Cleaning & Transformation Using Excel Power Query

A practical data-cleaning project where raw sales datasets were cleaned, transformed, and combined using **Microsoft Excel Power Query**.

The goal of this project was to take multiple raw CSV files, identify data-quality issues, apply transformation steps, and create structured datasets ready for further analysis in **Power BI, Excel, or SQL**.

---

##  Project Overview

This project focuses on the **data preparation stage of the analytics process**.

The raw data contained multiple tables related to:

* Customers
* Products
* Stores
* Regions
* Transactions
* Returns

Using **Excel Power Query**, the datasets were imported, cleaned, transformed, and organized into a structured Excel workbook.

### Main Objective

> Transform messy/raw business data into clean, consistent, analysis-ready datasets.

---

## 🛠️ Tools Used

* **Microsoft Excel**
* **Power Query**
* Data Cleaning & Transformation
* Basic Data Validation

---

## 📂 Dataset Structure

The project contains the following datasets:

| Dataset           | Records | Purpose                     |
| ----------------- | ------: | --------------------------- |
| Customers         |  10,281 | Customer information        |
| Products          |   1,560 | Product details and pricing |
| Regions           |     109 | Sales region information    |
| Stores            |      24 | Store information           |
| Returns           |   7,087 | Product return records      |
| Transactions 1997 |  86,837 | 1997 transaction data       |
| Transactions 1998 | 182,883 | 1998 transaction data       |

---

##  Data Cleaning Process

The datasets were processed using **Excel Power Query**.

### 1. Data Import

Imported multiple CSV files into Power Query and reviewed their structure, columns, and data types.

### 2. Data Type Transformation

Checked and corrected appropriate data types for:

* Dates
* Numbers
* Text fields
* IDs
* Currency-related columns
* Quantities

### 3. Column Transformation

Performed transformations such as:

* Renaming columns
* Removing unnecessary columns
* Reordering columns
* Creating calculated columns
* Standardizing column names

### 4. Data Cleaning

Reviewed the datasets for common data-quality issues including:

* Blank values
* Inconsistent values
* Incorrect data types
* Unnecessary fields
* Duplicate or redundant information

### 5. Data Combination

Used Power Query to work with multiple related datasets and prepare them for analysis.

Transaction data from different years was also structured consistently for easier downstream analysis.

### 6. Calculated Fields

Created useful business metrics in the transaction dataset, including:

* **Sales**
* **Cost Price**
* **Profit**

Example:

**Sales = Quantity × Retail Price**

**Cost Price = Quantity × Product Cost**

**Profit = Sales − Cost Price**

---

##  Final Cleaned Dataset

The cleaned datasets were consolidated into:

**`Cleaned_sales_Dataset.xlsx`**

The workbook contains structured tables for:

* Sales Dataset
* Customers
* Products
* Regions
* Returns
* Stores
* Transactions 1997
* Transactions 1998

The cleaned data can be used as a foundation for further projects involving:

* Power BI dashboards
* SQL analysis
* Sales analysis
* Customer analysis
* Product performance analysis
* Profitability analysis

---

##  Key Skills Practiced

Through this project, I practiced:

* Excel Power Query
* Data Cleaning
* Data Transformation
* Data Type Management
* Data Validation
* Column Transformation
* Calculated Columns
* Working with Multiple Datasets
* Preparing Data for Analysis

---

##  Why This Project?

Data analysis does not start with a dashboard.

It starts with **clean and reliable data**.

This project helped me understand the importance of the data-preparation stage and gave me practical experience using Power Query to turn raw datasets into analysis-ready data.

---

## 📁 Project Files

```text
Sales-Data-Cleaning/
│
├── Cleaned_sales_Dataset.xlsx
│
├── Customers.csv
├── Products.csv
├── Regions.csv
├── Returns_1997-1998.csv
├── Stores.csv
├── Transactions_1997.csv
└── Transactions_1998.csv
```

---

##  Next Step

The cleaned data can be used for a future **Power BI Sales Analysis Dashboard** and **SQL-based business analysis**.

---

##  Anupam

**Data Analytics Learner**

Focused on building practical projects using:

**Excel | Power Query | SQL | Power BI**
