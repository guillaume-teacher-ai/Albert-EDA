# E-commerce Sales Analysis — Student Brief

## Context

You are part of the data analytics team of a European e-commerce company. Management has provided an extract of recent order-line data covering a six-month reporting window.

## Management question

> Based on the last six months of sales, which products, customers and markets should we focus our efforts on? What role do promotions play?

## Dataset

The file `ecommerce_raw.csv` contains one row per **order line**, not necessarily one row per complete order.

| Column | Neutral description |
| --- | --- |
| `order_line_id` | Identifier of the order line |
| `order_id` | Identifier of the order to which the line belongs |
| `order_date` | Recorded order date |
| `customer_id` | Anonymous customer identifier |
| `customer_segment` | Commercial customer segment |
| `country` | Market associated with the order |
| `acquisition_channel` | Channel credited with customer acquisition |
| `product_category` | Recorded product category |
| `product_id` | Synthetic product identifier |
| `quantity` | Recorded quantity for the line |
| `unit_price` | Unit price in the recorded currency |
| `currency` | Currency of monetary fields |
| `discount_pct` | Discount percentage applied to the line |
| `shipping_cost` | Shipping cost recorded for the line |
| `returned` | Whether the line is recorded as returned |
| `payment_status` | Recorded payment status |

## Task

Produce **three business recommendations** supported by evidence from the dataset. Your analysis should address products, customers and/or markets, and it should comment on the role of promotions.

You may use an AI assistant to accelerate your work. Treat any AI-generated result as an analytical hypothesis that you remain responsible for checking, interpreting and defending.

Be ready to explain:

- the metric used for each recommendation;
- the population and time period covered;
- the main limitations of your evidence;
- what you would verify before management acts on the recommendation.
