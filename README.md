
# SQL Music Database Analysis

This project showcases a structured SQL-based analysis on a PostgreSQL music database, aimed at deriving meaningful business insights from transactional data. The dataset simulates a digital music store, including customers, invoices, employees, artists, tracks, and related entities.

## Project Overview

**Objective:**  
To identify trends, behaviors, and opportunities within a music sales environment using SQL queries for business reporting and customer insights.

**Tools & Technologies:**  
- PostgreSQL
- pgAdmin 4
- SQL
- GitHub

## Analysis and Schema Overview

The SQL analysis addresses key business questions across customer behavior, financial performance, and content trends:

- Identified the most senior employee based on job title hierarchy.
- Analyzed invoice volumes by country to uncover high-performing markets.
- Ranked cities and customers based on total revenue contribution.
- Profiled Rock music listeners by joining invoice, track, and customer data.
- Discovered the most prolific artists in the Rock genre.
- Listed tracks exceeding average duration for targeted promotions.
- Calculated customer-level spending on the top-selling artist.
- Determined the most purchased music genre by country.
- Highlighted top-spending customers in each country for strategic outreach.

> All SQL queries are maintained in a separate file (`MusicStoreAnalysis.sql`) for organized reference and reuse.

The underlying schema follows a normalized relational structure, including core entities such as `Customer`, `Invoice`, `Invoice Line`, `Track`, `Album`, `Artist`, `Genre`, `Employee`, and `Playlist`. A visual Entity-Relationship Diagram (ERD) is included (`MusicStore.png`) to represent the table relationships, including manually defined foreign keys to reflect intended data connections.

## Highlights

- Demonstrates business-focused SQL query development.
- Leverages joins, aggregations, CTEs, and window functions.
- Covers real-world use cases such as customer segmentation, sales analysis, and content performance tracking.
- Structured for future integration with visualization tools like Power BI or Tableau.

## Credits
- Schema based on a commonly used music store dataset for SQL tutorials
