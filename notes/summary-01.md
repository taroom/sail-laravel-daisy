# NearFood

digunakan untuk mencari makanan terdekat

## entities

### merchant_premium_orders
- id
- id_merchant
- order_at
- order

### merchants
- id
- name
- photo
- address
- is_online_reservation
- coord_latitude
- coord_longitude

### merchant_images
- id
- merchant_id
- image
- is_primary
- description

### junction_merchant_categories
- id_merchant
- id_category

### merchant_categories
- id
- label

### items
- id
- name
- photo
- price
- description

### item_images
- id
- item_id
- image
- is_primary
- description

### junction_item_categories
### item_categories