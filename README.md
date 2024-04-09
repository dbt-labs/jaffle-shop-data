# 🥪Jaffle Shop Data 💾

This repo contains a sample of data generated via the [`jaffle-shop-generator`](https://github.com/dbt-labs/jaffle-shop-generator) that powers the [Jaffle Shop](https://github.com/dbt-labs/jaffle-shop) dbt tutorial project.

It's a 1 year sample spanning from 2016 to 2017, and includes the following tables:

- `raw_customers`: customers who have placed orders
- `raw_orders`: orders placed by customers for food and drinks
- `raw_items`: the individual items that make up an order
- `raw_products`: the products that are available to order
- `raw_stores`: the stores where orders are placed
- `raw_supplies`: the supplies that are used to make products

## Usage

You can clone this repo or download it as a zip file. The data is all CSVs for easy use in dbt. If you're using it with the Jaffle Shop project, just place the CSVs in the `seeds` directory of your dbt project or create a folder called `jaffle-data`, which that project also scans for seed files. More detailed instructions are in the [`jaffle-shop`](https://github.com/dbt-labs/jaffle-shop) repo.
