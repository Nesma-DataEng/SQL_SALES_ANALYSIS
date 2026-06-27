# SQL_SALES_ANALYSIS
SQL queries for analyzing product sales, calculating total revenue, and ranking
### SQL Query:
```sql
SELECT PRODUCT, SUM(AMOUNT)
FROM SALES 
GROUP BY PRODUCT
ORDER BY SUM(AMOUNT) DESC;
```
