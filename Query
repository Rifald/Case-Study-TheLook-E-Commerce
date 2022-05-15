SELECT o.order_id, o.status, 
gender,
o.created_at,
oi.sale_price,
p.category
FROM `bigquery-public-data.thelook_ecommerce.orders` o 
LEFT JOIN `bigquery-public-data.thelook_ecommerce.order_items` oi ON o.order_id = oi.order_id
LEFT JOIN `bigquery-public-data.thelook_ecommerce.products` p ON oi.product_id = p.id;
