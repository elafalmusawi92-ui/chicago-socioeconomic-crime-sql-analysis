# chicago-socioeconomic-crime-sql-analysis
SQL and Python (SQLite) analysis of Chicago census socioeconomic indicators, public school performance, and crime datasets.
# Chicago Socioeconomic, Public Schools & Crime SQL Analysis

## Overview
Loaded and queried three public datasets from the City of Chicago Data Portal—**Socioeconomic Indicators (2008–2012)**, **Chicago Public Schools (2011–2012)**, and **Chicago Crime Data**—using Python (`sqlite3`, `pandas`) and SQL (`ipython-sql`) to examine correlations between community hardship, school safety, and crime incidents.

## Key Analytical Findings
* **Crime Volume & Hotspots:** Analyzed 533 recorded crime incidents across Chicago community areas, identifying **Austin (Community Area 25)** as having the highest volume of reported incidents.
* **Socioeconomic Hardship:** Identified **Riverdale** as having the highest hardship index in the city, alongside four community areas with per capita income below $11,000 (West Garfield Park, South Lawndale, Fuller Park, and Riverdale).
* **School Safety & Incidents:** Evaluated average school safety scores across Elementary (~49.5), Middle (48.0), and High Schools (~49.6), and isolated specific crime categories occurring on school grounds.

## Tools & SQL Techniques Used
* **Python:** `pandas`, `sqlite3`, `ipython-sql`
* **SQL:** Relational database table creation (`to_sql`), subqueries, aggregate functions (`COUNT`, `AVG`, `MAX`), pattern matching (`LIKE`, `instr`), `DISTINCT`, `GROUP BY`, and multi-condition filtering.
