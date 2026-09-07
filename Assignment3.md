SELECT * FROM products WHERE price BETWEEN 50.00 AND 300.00;
SELECT * FROM products WHERE category IN ('Audio', 'Wearables');

SELECT * FROM products WHERE stock_quantity >= 50 ORDER BY stock_quantity DESC;

SELECT * FROM products WHERE product_name LIKE 'Aero%';

SELECT * FROM products WHERE sku LIKE '%-MAX-%';

SELECT * FROM products WHERE sku LIKE '__-%';
