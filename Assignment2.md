

INSERT INTO products (product_name, sku, category, price, stock_quantity, date_added)
VALUES 
('Neo-Pro Laptop',       'LTOP-NEO-01',  'Electronics', 1299.99, 15,  '2026-01-15'),
('AeroBuds Wireless',    'AU-AERO-55',   'Audio',         89.95, 120, '2026-05-20'),
('SoundWave Soundbar',   'AU-SNDW-09',   'Audio',        199.99, 45,  '2026-07-10'),
('SmartSync Watch',      'WEAR-SYNC-02', 'Wearables',    249.50, 0,   '2026-08-01'),
('MaxCharge Powerbank',  'ACC-MAX-12',   'Electronics',   39.99, 250, '2026-09-01');


 SET SQL_SAFE_UPDATES=0;

 UPDATE products
SET price = price * 5/100
WHERE category = 'Electronics';


 DELETE FROM products
WHERE stock_quantity = 0;

 <img width="3360" height="2100" alt="image" src="https://github.com/user-attachments/assets/4eec13c4-c84e-425b-8a82-fa0ececc44ac" />
