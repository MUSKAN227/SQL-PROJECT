# 🎵 Music Store Data Analysis

## 📌 Project Overview

This project explores a music store's database using advanced SQL queries to uncover business insights across customer behavior, sales performance, and genre preferences. The dataset mimics a real-world relational schema with tables like `customer`, `invoice`, `invoice_line`, `track`, `album`, `genre`, and `artist`.

## 📊 Objectives & Insights

- **Customer Insights**  
  - Identify the highest-paying customers globally and per country  
  - Track genre preferences by location  
  - Discover cities with maximum revenue for promotional opportunities  

- **Sales Trends**  
  - Pinpoint top countries by invoice count  
  - Extract highest-value invoices and spending patterns  

- **Genre & Artist Performance**  
  - Determine top 10 artists by number of Rock songs  
  - Highlight popular genres by purchase volume per country  

- **Content Analysis**  
  - List all tracks longer than the average duration  
  - Find customers who listen to Rock music  

## 🧠 Techniques Used

- Subqueries and aggregations (`SUM`, `COUNT`, `AVG`)  
- Common Table Expressions (CTEs)  
- Window functions (`ROW_NUMBER()`)  
- Joins across multiple tables  
- Recursive patterns for advanced grouping

## 📁 Files Included

- `music_store_analysis.sql` — Contains all queries used for the analysis  
- `README.md` — This file

## 🛠️ Tools & Stack

- PostgreSQL (or SQLite/MySQL-compatible SQL)  
- Can be extended into Power BI or Excel for dashboarding  
- Suitable for integration with Python-based ETL pipelines

## ✨ Highlights

- Handles edge cases like tied top spenders per country  
- Uses genre-based filtering to analyze listener preferences  
- Offers query logic for promotional targeting and business strategy
