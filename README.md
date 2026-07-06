Power Bi Assignment July 04 2026 Dashboard The Power Bi dashboard is
divided into several parts. The top section covers the title, the
dashboard reset button and the Branch dropdown that allows for
filtering. The section highlighted in blue contains the KPIs that
breakdown the performance of LuxCars Logistics. The dashboard has 4
charts: the barchart with most sales, the car brand that was most sold
and the customer type that brought the most revenue. A trend chart shows
the revenue, units sold and gross profit. A silder was added that allows
the user to filter based on the date and the whole dashboard will
update. A table with the sales rep and the cumulative revenue generated
from each lead source is present. Below it, we have a matrix with the
branch star rating, branch name, total revenue per branch, and car units
sold. A second drill through page is added for the branches, and it has
the following: the total revenue, the gross profit, the top car by
revenue, the sales person with most revenue, the lead source, the
payment status, the revenue each month and delivery status. Once done,
you can ctrl + click the back button in the left hand side. Measures Avg
Branch star rating = AVERAGE('Jcars Flat Table (2)'[Customer Rating])
Avg delivery days = AVERAGE('Jcars Flat Table (2)'[Days to Deliver])
Gross Profit Margin = (([total revenue] - [COGS])/ [total
revenue]) * 100 Lead Source Highest Customers = TOPN(     1,    
VALUES('Jcars Flat Table (2)'[Lead Source]),    
CALCULATE(COUNT(Customer_dim[Customer Name])) ) No of orders =
COUNT('Jcars Flat Table (2)'[Order ID]) Sales Highest Rev & Highest
units = TOPN(     1,     VALUES(Sales_dim[Sales Rep]),    
CALCULATE(SUM('Jcars Flat Table (2)'[Revenue Recorded])), DESC,    
CALCULATE(SUM('Jcars Flat Table (2)'[Units Sold])),DESC ) total
delivery cost = SUM('Jcars Flat Table (2)'[Delivery Fee]) total
logistics cost = SUM('Jcars Flat Table (2)'[Logistics Cost]) total no
of cars sold = COUNT(Car_dim[Car_id]) total revenue = SUM('Jcars Flat
Table (2)'[Revenue Recorded]) Vehicle Type High Revenue & Units sold =
TOPN(     1,     VALUES(Car_dim[Vehicle Type]),    
CALCULATE(SUM('Jcars Flat Table (2)'[Revenue Recorded])), DESC,    
CALCULATE(SUM('Jcars Flat Table (2)'[Units Sold])),DESC )
Branch With Highest Revenue = TOPN(     1,    
VALUES(location_dim[Branch]),     CALCULATE(SUM('Jcars Flat Table
(2)'[Revenue Recorded]))
)
Gross Profit = [total revenue] - SUM('Jcars Flat Table (2)'[Total
units sold]) - SUM('Jcars Flat Table (2)'[Delivery Fee]) - SUM('Jcars
Flat Table (2)'[Logistics Cost]) Highest Make Sold = TOPN(     1,    
VALUES(Car_dim[Car Model]),     CALCULATE(SUM('Jcars Flat Table
(2)'[Units Sold])) )
payment method Highest total revenue = TOPN(     1,     VALUES('Jcars
Flat Table (2)'[Payment Method]),     CALCULATE(SUM('Jcars Flat Table
(2)'[Revenue Recorded])) )
Region Highest Rev = TOPN(     1,     VALUES(location_dim[Region]),  
  CALCULATE(SUM('Jcars Flat Table (2)'[Revenue Recorded])) )
Top Car Make by Revenue = TOPN(     1,     VALUES(Car_dim[Car Make]),
    CALCULATE(SUM('Jcars Flat Table (2)'[Revenue Recorded])) )
Insights Nakuru Branch had the highest logistics cost compared to sales
revenue. SUV's are the most sold vehicles. Toyotas are the top selling
cars. The revenue has been reducing as the year has been progressing.
Car dealers and the Government are the highest car purchasers. Kakamega
branch had the highest revenue. Mpesa was the payment method that
contributed to the most revenue Delivered is the delivery status with
the highest orders. Nissan specifically pickups are the most returned.
Faith Achieng generated the most sales revenue
Recommendations To increase profit margins, the unit selling price
should be increase to at least break even. The delivery fee and
logistics costs are too high thus finding a more efficient method for
transporting and delivering cars would increase profit margins. More
advertisements should be done in Instagram, Facebook, and other social
media spaces since they have brought in a significant amount of revenue.
