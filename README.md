# US-Agricultural-Department


# SQLite Database Project

## Overview
This project contains an SQLite database (`hello.sqlite`) created and managed using **DBeaver**. The database includes multiple tables and structured data for analysis.

## Steps Taken
1. Created an SQLite database (`hello.sqlite`).
2. Designed and created tables using **DBeaver**.
3. Inserted sample data and performed queries.
4. Exported the database and uploaded it to GitHub.

## Files Included
- `hello.sqlite` - The SQLite database file.
- `schema.sql` (optional) - Contains table structures.
- `exported_data.csv` (optional) - Sample exported data from tables.

## How to Use
1. Open the `hello.sqlite` file using **DBeaver** or any SQLite-compatible tool.
2. Run queries or explore the data.

Create Tables:

CREATE TABLE cheese_production (
    Year INTEGER,
    Period TEXT,
    Geo_Level TEXT,
    State_ANSI INTEGER,
    Commodity_ID INTEGER,
    Domain TEXT,
    Value INTEGER
);


CREATE TABLE honey_production (
    Year INTEGER,
    Geo_Level TEXT,
    State_ANSI INTEGER,
    Commodity_ID INTEGER,
    Value INTEGER
);

