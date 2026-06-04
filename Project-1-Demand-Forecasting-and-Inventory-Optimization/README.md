# End-to-End Demand Forecasting and Inventory Optimization System

## Overview

This project combines demand forecasting and inventory optimization into a single supply chain decision-support system. The project uses historical sales data to forecast future demand and applies inventory control techniques to determine optimal inventory policies.

## Business Problem

Organizations must balance inventory availability against inventory carrying costs. Poor forecasting can lead to stockouts, excess inventory, and increased operational costs.

This project addresses both challenges by integrating demand forecasting with inventory optimization.

## Dataset 1: Milk Sales Data

### Analysis Performed
- Average Demand Calculation
- Daily Demand Analysis
- Annual Demand Calculation
- Standard Deviation Analysis
- Economic Order Quantity (EOQ)
- Safety Stock Calculation
- Reorder Point (ROP)
- Inventory Cost Analysis

### Inventory Simulation
A reorder policy simulation was developed to evaluate inventory performance under changing demand conditions.

### Key Outputs
- Optimal EOQ
- Safety Stock Level
- Reorder Point
- Inventory Cost Before EOQ Optimization
- Inventory Cost After EOQ Optimization
- Cost Savings Calculation

### Visualizations
- Actual vs Forecast Demand Line Chart
- Inventory Cost Comparison Bar Chart
- Inventory Simulation Results

## Dataset 2: Smartphone Sales and Production Data

Period Covered:
December 2023 – November 2025

### Forecasting Method
- Power Trend Forecasting

### Forecast Accuracy
- MAPE: 2.48%

### Key Outputs
- Future Sales Forecast
- Forecast Accuracy Evaluation
- Demand Trend Analysis

### Visualizations
- Actual vs Forecasted Sales Line Chart

## Tools Used
- Python
- Excel
- Power BI

## Project Structure

data/
- Milk Sales Data.xlsx
- Smartphone Sales and Production Data.xlsx

notebooks/
- Inventory Optimization.ipynb
- Smartphone Sales Forecasting.ipynb

powerbi/
- Dashboard files

## Business Value
This project demonstrates how forecasting and inventory optimization can be integrated to improve inventory availability, reduce operating costs, and support data-driven supply chain planning.
