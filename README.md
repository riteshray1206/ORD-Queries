Overview:-
This project involves designing a database schema for handling transactional data. The database includes tables for customers, orders, products, and order_items. Additionally, it involves writing SQL queries to perform data analysis. 

Database Schema:-  
Tables: customers customer_id (Primary Key) first_name last_name email orders order_id (Primary Key) customer_id (Foreign Key) order_date products product_id (Primary Key) product_name price order_items order_item_id (Primary Key) order_id (Foreign Key) product_id (Foreign Key) quantity price

SQL Queries:-  
Queries Included: Total Number of Orders by Each Customer 
List of Products Never Ordered 
Customer Who Spent the Most in the Last Month

Files:-  
schema.sql: SQL script for creating the tables. 
queries.sql: SQL queries for data analysis.
