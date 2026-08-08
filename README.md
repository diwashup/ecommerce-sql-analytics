# E-Commerce Sales & Customer Analytics Using PostgreSQL

An end-to-end SQL portfolio project analyzing e-commerce sales, customers, products, profitability, payments, discounts, and customer behavior using PostgreSQL/Supabase.

## Objectives
- Build and validate a relational database
- Define business KPIs
- Analyze monthly revenue and MoM growth
- Analyze customer value and repeat behavior
- Evaluate products, categories, and profitability
- Analyze payment performance and discounts
- Apply CTEs and SQL window functions
- Translate SQL results into business insights

## Dataset
Six relational tables: `customers`, `categories`, `products`, `orders`, `order_items`, and `payments`.

Approximate rows: customers 600; categories 7; products 126; orders 3,500; order_items ~6,000; payments 3,500.

## Key Results
| KPI | Result |
|---|---:|
| Completed Orders | 3,162 |
| Active Customers | 597 |
| Units Sold | 6,940 |
| Total Revenue | $900,428.15 |
| Average Order Value | $284.77 |
| Gross Profit | $280,688.66 |
| Profit Margin | 31.17% |

## Revenue Highlights
- Highest monthly revenue: **September 2024 — $48,113.23**
- Lowest monthly revenue: **May 2024 — $26,576.59**
- Highest MoM growth: **September 2024 — +33.66%**
- Largest MoM decline: **October 2024 — -28.86%**
- December 2025: **$45,577.40**, +29.92% MoM

## SQL Skills
PostgreSQL, joins, aggregations, CTEs, CASE, conditional aggregation, date functions, `LAG()`, `RANK()`, `DENSE_RANK()`, window functions, KPI calculations, data-quality validation, profitability analysis.

## Project Structure
```text
ecommerce-sql-analytics/
├── README.md
├── data/README.md
├── sql/ (19 analysis/setup scripts)
└── insights/business_insights.md
```

## Reproduction
1. Create a PostgreSQL/Supabase database.
2. Run `sql/01_database_setup.sql`.
3. Load the six source tables.
4. Run the analysis scripts in `sql/`.
5. Review `insights/business_insights.md`.


## Author
**Diwash Upadhyaya** — Data Analyst Portfolio Project
