# Production-Pivot

A small company sells electronics and electronic media wants to create a table which visualizes the cost of their recent orders. Using lookups, I created a pivot table which serves this purpose.

## Process

1. Determined the "Product Price" of each row in the "Orders" sheet by using a `VLOOKUP()` that references each row's "Product ID"

* The "Product Price" of a row does not include shipping

2. Determined the "Shipping Price" of each row in the "Orders" sheet by using a `VLOOKUP()` that references each row's "Shipping Priority"

3. Selected all of the data on the "Orders" sheet and create a new pivot table that calculates the sum of both "Product Price" and "Shipping Price" for each "Order Number" and "Product ID"
