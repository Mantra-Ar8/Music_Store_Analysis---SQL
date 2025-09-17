# Music_Store_Analysis - SQL
SQL project analyzing a music store dataset using PostgreSQL, including schema design, queries, and business insights.

# Project Overview

- This project is an SQL-based analysis of a music store database.
- It demonstrates the use of PostgreSQL / SQL queries to extract insights from a music store dataset.

# The project includes easy, moderate, and advanced queries that cover:
- Customer spending analysis
- Popular tracks, artists, and genres
- Invoice and order analysis
- Top customers and top-selling artists
- Database Schema

# The database consists of the following tables:

- **Customer** – customer_id, first_name, last_name, email, country, city

- **Invoice** – invoice_id, customer_id, invoice_date, billing_country, total

- **InvoiceLine** – invoice_line_id, invoice_id, track_id, unit_price, quantity

- **Track** – track_id, name, album_id, genre_id, milliseconds

- **Album** – album_id, title, artist_id

- **Artist** – artist_id, name

- **Genre** – genre_id, name

- **Employee** – employee_id, first_name, last_name, title


### Technologies Used

- SQL / PostgreSQL

- Database Analysis

- Data Aggregation


## Outcome / Insights:
- Top-Spending Customers: Identified the highest-spending customers, useful for loyalty programs and targeted promotions.

- Revenue by City and Country: Determined which cities and countries generate the most revenue, and expansion decisions.

- Popular Music Genres: Found the most popular genres in different regions, guiding inventory planning and playlist curation.

- Top Artists and Tracks: Identified artists and tracks with the highest sales, useful for promotion.

- Customer Preferences & Behavior: Analyzed customer preferences by genre and artist to enable personalized recommendations.

- Business Decisions & Strategy: Data-driven insights to support decisions on pricing, promotions, and product offerings.
