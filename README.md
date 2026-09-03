# SQL-World-Layoffs-Analysis-
Cleaned and standardized a layoffs dataset using SQL by handling duplicates, missing values, inconsistent categories, and date formats, then performed exploratory analysis across companies, industries, locations, and time periods using aggregations, CTEs, ranking, and window functions.

# SQL Data Cleaning & Exploratory Analysis – World Layoffs Dataset

## Overview

This project uses SQL to clean, standardize, and explore a layoffs dataset.

The project is divided into two stages:

1. Data Cleaning
2. Exploratory Data Analysis

## Data Cleaning

The raw dataset was prepared by:

- Identifying and removing duplicate records
- Handling missing and blank values
- Standardizing inconsistent categories
- Cleaning country values
- Converting date fields into proper date format
- Removing records that were not useful for analysis

## Exploratory Data Analysis

The cleaned dataset was analyzed to explore layoffs across:

- Companies
- Locations
- Countries
- Industries
- Company stages
- Years

The analysis also included company rankings by year and cumulative layoffs over time.

## SQL Concepts Used

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- Aggregate Functions
- JOIN
- CTEs
- ROW_NUMBER()
- DENSE_RANK()
- Window Functions
- Date Functions
- UPDATE
- DELETE
- NULL Handling

## Project Structure

```text
01_Data_Cleaning.sql
02_Exploratory_Analysis.sql
