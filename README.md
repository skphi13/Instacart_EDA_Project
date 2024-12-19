# Instacart-Data-Project
For this project, I worked with a dataset from 2017 released by Instacart. Instacart is a grocery delivery platform where customers can order groceries and have it delivered to their homes. I conducted an explorative data analysis on the data and answered informative business questions for the project.

# Datasets Description
There are five tables in the dataset. Below is a data dictionary that lists the columns in each table and describes the data that it holds.

`instacart_orders.csv`: each row corresponds to one order on the Instacart app
- 'order_id': ID number that uniquely identifies each order
- 'user_id': ID number that uniquely identifies each customer account
- 'order_number': the number of times this customer has placed an order
- 'order_dow': day of the week that the order placed (which day is 0 is uncertain)
- 'order_hour_of_day': hour of the day that the order was placed
- 'days_since_prior_order': number of days since this customer placed their previous order
  
`products.csv`: each row corresponds to a unique product that customers can buy
- 'product_id': ID number that uniquely identifies each product
- 'product_name': name of the product
- 'aisle_id': ID number that uniquely identifies each grocery aisle category
- 'department_id': ID number that uniquely identifies each grocery department category
  
`order_products.csv`: each row corresponds to one item placed in an order
- 'order_id': ID number that uniquely identifies each order
- 'product_id': ID number that uniquely identifies each product
- 'add_to_cart_order': the sequential order in which each item was placed in the cart
- 'reordered': 0 if the customer has never ordered this product before, 1 if they have
  
`aisles.csv`
- 'aisle_id': ID number that uniquely identifies each grocery aisle category
- 'aisle': name of the aisle
  
`departments.csv`
- 'department_id': ID number that uniquely identifies each grocery department category
- 'department': name of the department

# Conclusions

- There might be a techincal issues preventing customer from adding more than 64 items to their cart.
- The range from 10am to 3pm are the most active times people shop for groceries.
- People typically wait 7 days before placing their next order.
- Most customers placed less than 10 orders.
- Average items per order is around 10.
- Banana is the most frequently ordered product with 66050 orders and also top of the reorder list with 55673 reordered.
