# Target-Brazil-Sales-Analysis

**Introduction**

Target is one of the world’s most recognized brands and one of America’s leading retailers. Target makes itself a preferred shopping destination by offering outstanding value, inspiration, innovation, and an exceptional guest experience that no other retailer can deliver.

This business case has information on **100k orders** from **2016 to 2018** made at Target in Brazil. Its features allow viewing an order from multiple dimensions: from order status, price, payment, and freight performance to customer location, product attributes, and finally reviews written by customers.

Data is available in 8 CSV files:

customers.csv

geolocation.csv

order_items.csv

payments.csv

reviews.csv

orders.csv

products.csv

sellers.csv

Each feature or column of different CSV files is described below:

**customers.csv:**

customer_id : *Id of the consumer who made the purchase.*

customer_unique_id : *Unique Id of the consumer.*

customer_zip_code_prefix : *Zip Code **of** the location of the - consumer.*

customer_city : *Name of the City from where the order is made.*

customer_state : *State Code from where order is made(Ex- sao paulo-SP).*

**sellers.csv:**

seller_id : *Unique Id of the seller registered*
seller_zip_code_prefix : *Zip Code of the location of the seller.*
seller_city : *Name of the City of the seller.*
seller_state : *State Code (Ex- sao paulo-SP)*

**order_items.csv**:

order_id: *A unique id of order made by the consumers.*
order_item_id: *A Unique id given to each item ordered in the order.
product_id: A unique id given to each product available on the site.*
seller_id: *Unique Id of the seller registered in Target.*
shipping_limit_date: *The date before which shipping of the ordered product must be completed.*
price: *Actual price of the products ordered.*
freight_value: *Price rate at which a product is delivered from one point to another.*

**geolocations.csv**:
geolocation_zip_code_prefix: *first 5 digits of zip code*
geolocation_lat: *latitude*
geolocation_lng: *longitude*
geolocation_city: *city name*
geolocation_state: *state*

**payments.csv:**
order_id: *A unique id of order made by the consumers.*
payment_sequential: *sequences of the payments made in case of EMI.*
payment_type: *mode of payment used.(Ex-Credit Card)*
payment_installments: *number of installments in case of EMI purchase.*
payment_value: *Total amount paid for the purchase order.*


**orders.csv**:
order_id: *A unique id of order made by the consumers.*
customer_id : *Id of the consumer who made the purchase.*
order_status: *status of the order made i.e delivered, shipped etc.*
order_purchase_timestamp: *Timestamp of the purchase.*
order_delivered_carrier_date: *delivery date at which carrier made the delivery.*
order_delivered_customer_date: *date at which customer got the product.*
order_estimated_delivery_date: *estimated delivery date of the products.*

**reviews.csv**:
review_id: *Id of the review given on the product ordered by the order id.*
order_id: *A unique id of order made by the consumers.*
review_score: *review score given by the customer for each order on the scale of 1–5.*
review_comment_title: *Title of the review*
review_comment_message: *Review comments posted by the consumer for each order.*
review_creation_date: *Timestamp of the review when it is created.*
review_answer_timestamp: *Timestamp of the review answered.*

**products.csv**:
product_id: *A unique identifier for the proposed project.*
product_category_name: *Name of the product category*
product_name_lenght: *length of the string which specifies the name given to the products ordered.*
product_description_lenght: *length of the description written for each product ordered on the site.*
product_photos_qty: *Number of photos of each product ordered available on the shopping portal.*
product_weight_g: *Weight of the products ordered in grams.*
product_length_cm: *Length of the products ordered in centimeters.*
product_height_cm: *Height of the products ordered in centimeters.*
product_width_cm: *width of the product ordered in centimeters.*
