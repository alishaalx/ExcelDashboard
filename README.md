# ExcelDashboard
In this Project, I have used Excel to Analyse the consumer data of a coffee shop to determine sales by Year, Country and also detremined the top 5 customers as per the Sales. 
File -> Data_Coffeeorder :
        This Excel File contain the data which includes orders,customer data and product information. Each of these have multiple columns. The Dataset Orders include Customer_ID which acts as a primary key and available in the cutomers dataset where as Poduct_ID avalible in the products dataset.
The Functions used : XLOOKUP, MATCH [To get the columns from customers and Products Datasets to the Orders.]
Once the orders is completed Sales column is created by multipliying unitprice and Quantity.
Now The Pivot Table is used and then created the different visualisations including a line graph showing Total Sales over time (Yearly), Total Sales By Country, and Top 5 Customers. It is combined with a Timeline based on tye OrderDate Column of the Orders and 3 slicers including Roast Type Name (Meduim,Light,Dark),Size in Kgs and Finally Based on wheather the custoemrs have Loyality Card or not.

The resulting Dashboard is named as "Coffee Sales Dashboard".
