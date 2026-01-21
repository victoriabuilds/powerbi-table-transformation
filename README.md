
# Power BI – Table Transformations Project

##  Project Overview
This project demonstrates Power BI data transformation skills using Power Query.
The task involved connecting to multiple CSV files, cleaning data, creating calculated columns,
and preparing the model for reporting.



### Power BI Data Model Update – Product Tables

**Overview:**
We are updating the internal reports in Power BI with new data and modifications to the product table. The steps below outline the key objectives and tasks.


**Key Objectives:**

**Connect to New Data Sources**

* Create queries to connect to the following CSV files:

  * `Product Category Lookup`
  * `Product Subcategory Lookup`

**Query Setup**

* Name the queries:

  * `Product Category Lookup`
  * `Product Subcategory Lookup`
* Promote column headers and confirm that all data types are correctly set.

**Product Table Modifications**

* **SKU Type Extraction:**

  * Add a new column in the Product table to extract all characters **before the dash (“-”)** in the `Product SKU` column. Name this column `SKU Type`.
  * Update the `SKU Type` calculation to extract all characters **before the second dash** instead of the first.

* **Product Style Cleanup:**

  * Replace zeros (`0`) in the `Product Style` column with `"NA"`.

**Finalize Updates**

* Close and load all queries to the Power BI data model.

---

If you want, I can also make an **even more concise, presentation-friendly version** that fits on a single slide. Do you want me to do that?




##  Transformations Performed

### 1. Created New Queries
- Connected to **Product Category Lookup.csv**
- Connected to **Product Subcategory Lookup.csv**
- Queries named accordingly

### 2. Data Validation
- Promoted column headers
- Verified and corrected data types

### 3. SKU Type Column Creation
- Extracted characters before the **first dash (-)**
- Updated logic to extract characters before the **second dash**

### 4. Data Cleaning
- Replaced `0` values in **Product Style** column with `"NA"`

### 5. Data Model
- Loaded all queries into the Power BI data model

---

##  Key Skills Demonstrated
- Power Query transformations
- Text parsing and column extraction
- Data cleansing
- Lookup table integration
- Professional data modeling practices

---

