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

* Created 10 new measures using functions such as DIVIDE,SUM,AVERAGE.

## Tools Applied 

* Microsoft Excel and Power Query for Data cleaning
* Power BI for Visualization
* SQL for Data Querying
* Data Modelling in Power BI

 ## Data Cleaning 
  - Removal of Duplicates 
  - Fixing of inconsistencies in Product Name
  - Filling of Blank rows

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
 1. What is the total revenue by product and region
 2. The Average Revenue generated per day
 3. Correlation between Revenue and Profit
 4. Total cost Incurred based on region amd products
 5. How great does the tax rate impact the profit generated
 6. On average how much profit does the firm make per day
 7. On average, how much revenue does the firm generate per day
 8. The total number of orders
 9. The tax rate
 10. The total cost incurred by the firm

