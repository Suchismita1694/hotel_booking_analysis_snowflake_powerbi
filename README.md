# Hotel Booking Analysis | Snowflake & Power BI

## Project Overview

This project focuses on analyzing hotel booking data using Snowflake and Power BI. The objective is to transform raw booking data into meaningful business insights by performing data cleaning, SQL transformations, KPI calculations, and interactive dashboard development.

The project follows a layered data warehouse architecture (Bronze, Silver, and Gold) in Snowflake, with Power BI used for data visualization and reporting.

## Tools & Technologies

- **Snowflake:** Cloud data warehousing, data storage and SQL transformations.
- **SQL:** Data cleaning, data validation, aggregations and KPI calculations.
- **Power BI:** Interactive dashboard development and data visualization.
- **DAX:** Calculated columns and measures for KPI reporting.
- **GitHub:** Project documentation and version control.

## Data Pipeline & Architecture

The project follows a Medallion Architecture:

1. **Bronze Layer:** Loaded raw hotel booking data into Snowflake.
2. **Silver Layer:** Performed data cleaning, handled missing values, validated data types, and addressed data quality issues.
3. **Gold Layer:** Created clean analytical tables and aggregated datasets for reporting.

## SQL Analysis & Transformations

SQL was used to perform:

- Data quality checks and validation.
- Handling NULL and invalid values.
- Data type conversions and data cleaning.
- Revenue and booking aggregations.
- Daily booking and revenue analysis.
- Hotel city-wise revenue analysis.
- Business KPI calculations.

## Key Performance Indicators (KPIs)

The following KPIs were developed:

- Total Revenue (USD)
- Total Guests
- Total Bookings
- Average Booking Amount

## Power BI Dashboard

An interactive dashboard was developed to analyze hotel booking performance.

### Dashboard Highlights

- **Executive Overview:** Total revenue, guests, bookings and average booking amount.
- **Monthly Revenue Analysis:** Monthly revenue trends.
- **Monthly Booking Analysis:** Booking trends over time.
- **City-wise Revenue Analysis:** Top-performing cities by revenue.
- **Booking Status Analysis:** Confirmed, cancelled and no-show bookings.
- **Booking Type Analysis:** Standard, Deluxe and Suite bookings.

## Key Insights

The dashboard enables business users to:

- Monitor overall booking and revenue performance.
- Identify monthly revenue and booking trends.
- Compare hotel performance across cities.
- Understand booking status distribution.
- Analyze booking preferences by room type.

 <img width="750" height="422" alt="image" src="https://github.com/user-attachments/assets/efd13fa2-96fc-4a9e-b7c9-9518b274b1f7" />


## Repository Structure

- `Hotel_Booking_Analysis.pbix` – Power BI dashboard.
- `KPI's in SQL` – SQL queries for KPI calculations and visualizations.
- `hotel_bookings_raw.csv` – Raw hotel booking dataset.
- `snowflake-Data processing` – Snowflake data processing and transformation scripts.

## Project Outcome

This project demonstrates an end-to-end data analytics workflow, from raw data ingestion and transformation in Snowflake to business intelligence reporting in Power BI.

It showcases practical experience in SQL, cloud data warehousing, data quality management, data modeling, DAX and dashboard development.
