# minty-sales-inventory-app
##Task 1

Create a Sales/Inventory Management Application in Java using Spring Boot (Rest Controller) with an API(JSON) that supports the following: 

ü  Create a new product 

ü  Update an existing product.

ü  Get a list of all available products.

ü  Place an Order based on availability of product.

ü  Capture basic customer detail (name and phone number) for the Order.

ü  It should be possible to change the product’s price, but this shouldn’t affect the total value of orders which have already been placed.

ü  Publish the basic detail of the created Order to Kafka for reporting.

A Product should have:

ü  A name and some representation of its price.

ü  The total number of items in stock.

ü  Product description

ü  An Order should have:

ü  Order Id and basic details.

ü  Capture customer details.


### Task 2

 Create a Report Application in Java using Spring Boot (Rest Controller) that does the following.

ü  Subscribe to Kafka to consume Order Creation Payload.

ü  Expose an endpoint that returns an Order report that is grouped by date. A date range filter should be supported. Expected details are listed below.

v  Date

v  Total_Order

v  Total_Order_Amount

 

Topics to take into account

1.     Try to show your OOP skills

2.     Database modelization, using JPA or ORM

3.     Handling of possible concurrent order creation that affects product stock tracking.

4.     Code standards/clean code

5.     Software patterns

6.     Unit tests.   
