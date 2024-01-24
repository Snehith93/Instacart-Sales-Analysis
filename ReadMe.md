
# Instacart SQL Analysis Project

## Overview
This project involves analyzing the Instacart dataset using SQL queries to uncover insights into customer purchasing patterns. The analysis is conducted using DB Browser for SQLite, focusing on aspects such as most ordered products, order timings, and customer preferences.

## Dataset
The dataset is structured into the following tables with the respective columns:

- `aisles`: Contains aisles information.
  - `aisle_id`
  - `aisle`

- `departments`: Contains department information.
  - `department_id`
  - `department`

- `order_products__prior`: Contains previous order details.
  - `order_id`
  - `product_id`
  - `add_to_cart_order`
  - `reordered`

- `orders`: Contains order information.
  - `order_id`
  - `user_id`
  - `eval_set`
  - `order_number`
  - `order_dow` (day of week)
  - `order_hour_of_day`
  - `days_since_prior_order`

- `products`: Contains product details.
  - `product_id`
  - `product_name`
  - `aisle_id`
  - `department_id`

## Key Queries
This project includes several key SQL queries used for the analysis, such as:

1. Identifying the most frequently ordered products.
2. Analyzing the busiest hours of the day for orders.
3. Determining the top products ordered from each department.
4. Finding the least ordered products overall.
5. Calculating order frequencies based on 'days_since_prior_order'.

## Tools Used
- DB Browser for SQLite: A high-quality, visual, open-source tool to create, design, and edit database files compatible with SQLite.

## How to Use
1. Clone the repository or download the SQL database file (`Instacart_SQL.db`).
2. Open the database file using DB Browser for SQLite.
3. Execute the provided SQL queries to explore the dataset and gain insights.

## Contributing
Feel free to fork this project, submit pull requests, or send suggestions to improve the queries or add new analyses.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgements
- Instacart for providing the dataset.
- Contributors and maintainers of DB Browser for SQLite.
