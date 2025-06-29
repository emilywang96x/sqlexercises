# sqlexercises
# TFL Journeys SQL Analysis – DataCamp Project

This project contains SQL queries written as part of a DataCamp exercise analyzing Transport for London (TFL) journey data. The goal was to explore and summarize trends in transportation usage across different journey types, with a focus on identifying popular and less-used services.

## 📊 Project Overview

The dataset used contains millions of journeys categorized by journey type, year, and month. The analysis includes:

1. **Most Popular Transport Types**  
   Aggregates total journeys by transport type to determine which services are most used.

2. **Emirates Airline Popularity**  
   Filters and ranks the top 5 months with the highest usage of the 'Emirates Airline' journey type.

3. **Least Popular Years for Tube (Underground & DLR)**  
   Identifies the five least busy years for the London Underground & DLR combined, based on total journey count.

## 🛠️ SQL Concepts Used

- `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`, `LIMIT`
- Aggregate functions like `SUM()` and `ROUND()`
- Filtering and sorting
- Basic subsetting of data based on conditions

## 📁 File(s) Included

- `tfl_journeys_analysis.sql` — Contains the SQL queries listed above.

## 📌 Notes

- The data was queried from the `TFL.JOURNEYS` table as provided in the DataCamp SQL environment.
- Null values in journey counts were handled by filtering out rows using `WHERE JOURNEYS_MILLIONS IS NOT NULL`.

## 📚 Source

This project was completed as part of a DataCamp course on SQL for data analysis.
