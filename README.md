# Sales-Analysis

## Project Overview

This project analyses the trend in sales of a firm in the month of January. It uncovers insight into the performance of the products sold by the firm per day,the profit generated and the effect of tax rate charged on the profit of a firm in that month.

## Dataset Content 

This datasets contains 5 Dim tables and 1 FactTable

The Dim tables contain:

* Product - ProductKey,ProductName,ProductSubcategoryKey.
      
* Product Category - ProductCategoryKey,ProductCategoryName.
      
* Product Subcategory - ProductSubcategoryKey,ProductSubcategoryName,ProductCategoryKey.

* Product Name 
      
* Date
      
* Customer - CustomerKey,CustomerName,Region,Email.

## Tools Applied 

* Microsoft Excel and Power Query for Data cleaning
* Power BI for Visualization
* SQL for Data Querying
* Data Modelling in Power BI

 ## Data Cleaning 
  - Removal of Duplicates 
  - Fixing of inconsistencies in Product Name
  - Filling of Balnk rows

 ## Data Querying 
 What is the total number of sales per product

 ```
SELECT Product Name,Sales
FROM FactTable
Group by Product Name
Order by Sales DESC

```

Top 5 regions based on Revenue
```

SELECT Top 5 Region,Sales
From FactTable
GROUP BY Region
ORDER BY Sales DESC

```

## Answered Questions
 

