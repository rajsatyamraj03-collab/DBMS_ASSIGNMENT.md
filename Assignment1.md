
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
    date_added DATE DEFAULT (CURRENT_DATE)
);


Now the key identification:---

id--> primary key 
product_name--> varchar
sku--> varchar
category --varchar
price--> decimal
stock--> default case 

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/0dde1b27-8930-4142-a7aa-1c6ae967ebbb" />
