
## Pie Bakery Performance Analysis

# Bakery Analytics Dashboard Project

## Overview
This project focuses on analyzing and visualizing revenue trends in the bakery industry using Power BI. The dashboard provides comprehensive insights into sales patterns, order types, pie preferences, and revenue metrics to optimize business operations.

## Problem Statement
In the bakery industry, understanding revenue trends and optimizing operations is crucial for success. This project analyzes various aspects of bakery operations including:
- Order types analysis
- Organic vs. non-organic products
- Pie flavor preferences
- Different pie types performance
- Transaction patterns and revenue trends

## Objectives
- Analyze and visualize revenue trends across different dimensions
- Create comprehensive DAX measures for business metrics
- Implement effective data modeling
- Develop interactive visualizations for better decision-making

## Dataset Structure
The project utilizes the following dimension and fact tables:
1. **Dim_OrderTypes** - Order classification information
2. **Dim_Organic** - Organic status of products
3. **Dim_PieFlavor** - Available pie flavors
4. **Dim_PieTypes** - Types of pies offered
5. **FactTable** - Transaction and sales data

## Technical Implementation

### DAX Calendar Table
Created a custom calendar table with the following columns:
- Date
- Year
- Month
- Month Number
- Quarter
- Weekdays
- Week Number

### Key DAX Measures
- Total Revenue
- Average Revenue
- Total Orders
- Total Transactions
- Year-over-Year Revenue Comparison (2020-2021)
- Last Transaction Date

### Visualizations

#### Dashboard Components
1. **Stacked Area Chart**
   - Shows cumulative revenue over time
   - Helps identify trends and patterns

2. **Column Chart**
   - Displays total revenue by quarters
   - Facilitates quarterly performance analysis

3. **Ribbon Chart**
   - Visualizes total revenue by weekday
   - Identifies peak sales days

4. **Interactive Elements**
   - Slicer for Pre-order/In-store purchase filtering
   - Dynamic table showing:
     - Slice/Whole pie prices
     - Order means
     - Total orders
     - Total revenue

5. **KPI Cards**
   - Total Transactions
   - Total Orders
   - Total Revenue
   - Average Revenue
   - Last Transaction Date
   - 2020 Revenue
   - 2021 Revenue

## Data Model
- Implemented star schema design
- Created relationships between dimension tables and fact table
- Optimized for efficient query performance