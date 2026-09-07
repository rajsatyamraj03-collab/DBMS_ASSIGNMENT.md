
-- Create Database
CREATE DATABASE Electroshop;

-- Use Database
USE Electroshop;

-- Create Products Table
CREATE TABLE products (
    id INT AUTO_INCREMENT PRIMARY KEY,
    product_name VARCHAR(100) NOT NULL,
    sku VARCHAR(50) UNIQUE,
    category VARCHAR(50),
    price DECIMAL(10,2) NOT NULL,
    stock_quantity INT DEFAULT 0
);


Now the key identification:---

id--> primary key 
product_name--> varchar
sku--> varchar
category --varchar
price--> decimal
stock--> default case 

