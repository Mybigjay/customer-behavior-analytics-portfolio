# Customer Shopping Behavior Analytics

An end-to-end data analytics portfolio project analyzing 3,900 retail transactions to uncover revenue drivers, customer segmentation, discount impacts, and subscription trends.

## Tech Stack
* **Python (pandas, SQLAlchemy):** Data cleaning, exploratory data analysis (EDA), and database ingestion.
* **PostgreSQL:** Relational storage and SQL querying to answer core business questions.
* **Power BI Desktop:** Interactive executive dashboard for visualizing KPIs, customer demographics, and purchasing patterns.

## Project Workflow
1. **Data Preparation (Python):** Cleaned raw CSV data, handled missing review ratings, standardized column names, and loaded the dataset into PostgreSQL.
2. **Business Analysis (SQL):** Wrote queries to evaluate revenue by gender and age group, top-rated products, shipping type preferences, and repeat buyer subscription rates.
3. **Visualization (Power BI):** Connected Power BI directly to PostgreSQL to build dynamic DAX measures and interactive visuals.

## Repository Structure
* `JupyterProject/customer_shopping_behavior.ipynb` — Jupyter Notebook containing data cleaning and PostgreSQL upload scripts.
* `JupyterProject/customer_shopping_behavior.csv` — Retail transaction dataset.
* `Customer behaviour Dashboard.pbix` — Interactive Power BI report file.

## How to Use
1. Clone this repository and open `Customer behaviour Dashboard.pbix` in **Power BI Desktop** to explore the interactive visuals.
2. Review `customer_shopping_behavior.ipynb` in Jupyter Notebook or PyCharm to inspect the data engineering pipeline.
