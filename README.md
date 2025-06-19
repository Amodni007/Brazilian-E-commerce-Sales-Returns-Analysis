# Brazilian-E-commerce-Sales-Returns-Analysis
This project analyzes customer orders, product performance, returns, and delivery metrics using the Brazilian Olist e-commerce dataset. It combines SQL, Python, and Power BI to clean data, uncover trends, identify high-return products, and provide insights for improving customer experience and reducing revenue loss.

---

### 📦 Raw Datasets Added to `/data`:

| Filename                                | Description |
|-----------------------------------------|-------------|
| `olist_orders_dataset.xlsx`             | Order-level metadata including customer ID, purchase date, and status |
| `olist_order_items_dataset.xlsx`        | Products sold per order (product ID, seller ID, price, freight) |
| `olist_products_dataset.xlsx`           | Product category, weight, dimensions |
| `olist_order_reviews_dataset.xlsx`      | Review scores, titles, and comments per order |
| `olist_order_payments_dataset.xlsx`     | Payment method and amount |
| `olist_customers_dataset.xlsx`          | Customer location and zip code |
| `olist_sellers_dataset.xlsx`            | Seller location and zip code |
| `olist_geolocation_dataset.xlsx`        | Mapping of zip code prefixes to latitude and longitude |
| `product_category_name_translation.xlsx`| Portuguese-to-English mapping of product category names |

---

### 🛠️ Tools Planned:
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **SQL** (for data transformation and KPIs)
- **Power BI** (for dashboards and insights)


### ✅ Objective:
To explore and understand the structure, contents, and relationships within each dataset using Microsoft Excel before performing any analysis.

---
### 📦 Datasets Explored (Located in `/data/`):

| File | Description |
|------|-------------|
| `olist_orders_dataset.xlsx` | Order metadata including customer ID, status, and timestamps |
| `olist_order_items_dataset.xlsx` | Individual items purchased in each order with product and seller info |
| `olist_products_dataset.xlsx` | Product categories, physical dimensions, and weights |
| `olist_order_reviews_dataset.xlsx` | Review scores and customer comments per order |
| `olist_order_payments_dataset.xlsx` | Payment method and transaction values |
| `olist_customers_dataset.xlsx` | Customer location (zip code, city, state) |
| `olist_sellers_dataset.xlsx` | Seller location data |
| `product_category_name_translation.xlsx` | Maps Portuguese category names to English |

---

### 🧩 Key Activities:

- Opened and explored each dataset in Excel
- Identified important columns, foreign keys (like `order_id`, `customer_id`, `product_id`)
- Analyzed value distributions using filters and PivotTables
- Noted missing values and data quality issues
- Documented structure and key insights for each table

---

### 📒 Output Created:

- 📝 Excel Summary Workbook:  
  `outputs/data_exploration_notes.xlsx`  
  Includes sample previews, observations, and analysis notes for:
  - `orders`
  - `order_items`
  - `products`
  - `reviews`
  - `payments`
  - `summary_notes` (manual observations)

---

### 🧠 Learnings:

- Orders can have multiple items, creating a one-to-many relationship
- Some product attributes like weight and dimensions are missing or zero
- Review scores range from 1 to 5 and can be used for customer satisfaction analysis
- Multiple payment types per order possible (some split payments)
- Product categories are in Portuguese and need translation for analysis

---






---
