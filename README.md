DATABASE DESIGN OF OINE SHOPPING CART
This tutorial provides complete steps to design a database schema of online shops and shopping carts to manage the users, products, transaction. It can be further used to develop an online shop and shopping cart based websites or applications.

USER TABLE
we will design the User Table to store user information. The same table can be used to relate the product creators(from the admin panel) and orders placed on the website. Users can track their own orders and track the status. Below mentioned is the description of all the columns of the User Table.
PRODUCT TABLE
we will design the Product Table to store the product data

TRANSACTION TABLE
We also need a transaction table to track the order payments made by the buyer and for bookkeeping. We can also use the same table to record the partial or full refund of the order.
Attributes for each entity:
For User Entity 
        -user_id,name,mobile,email
For Product Entity
         -product_id,user_id,title,price,shop

For Transaction Entity
         -user_id,payment_id,date
