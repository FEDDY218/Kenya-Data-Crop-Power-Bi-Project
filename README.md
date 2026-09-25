# Kenya-Data-Crop-Power-Bi-Project
A Power Bi project of analysis on Kenya Crop Dataset.
# Kenya Agricultural Performance Dashboard

## Overview

This project analyzes agricultural data from 500 smallholder farmers across Kenya using Power BI, Power Query, and DAX.

The goal is to understand crop and county performance, profitability, farming practices, and revenue trends over time.

## Data Cleaning

The dataset was cleaned using Power Query by:

* Replacing `Error`, `N/A`, and blank categorical values with `Unknown`
* Correcting data types for dates and numeric fields
* Handling missing numeric values as `null`
* Preserving negative profit values as genuine losses
* Standardizing inconsistent categorical values

## Analysis

The dashboard covers:

* Total Revenue, Profit, Yield, and Farmers
* Revenue and profit by crop and county
* Profit per acre
* Irrigation, fertilizer, and pest-control analysis
* Revenue trends over time
* Interactive filters for county, crop, season, and year/month

A dedicated Date Table was created for time-intelligence analysis, and DAX was used for mathematical, statistical, logical, text, filter-context, and time-intelligence calculations.

## Key Insights

* Crop Performance:Crop Performance: Some crops generate higher total revenue and profit than others, while profit per acre highlights which crops make better use of available farmland.
* County Performance: Agricultural performance varies across counties, with differences in revenue and profit indicating that location can influence overall farm performance.
* Farming Practices: Farming Practices: Profitability differs across farming practices, suggesting that irrigation, fertilizer use, and pest-control methods may be associated with differences in farm profitability.

## Tools

**Power BI | Power Query | DAX | Excel**

## Files

* `Kenya_Agricultural_Dashboard.pbix` — Power BI report
* `DAX_Answer_Sheet.pdf` — DAX calculations and results
