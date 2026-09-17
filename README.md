# FORESIGHT

## AI-Powered Demand & Inventory Intelligence Platform

FORESIGHT is an AI-powered retail intelligence platform designed to support demand forecasting, inventory risk analysis, and data-driven inventory decision-making.

## Project Overview

Retail businesses need to maintain the right balance between product availability and inventory levels. Overestimating demand can lead to overstock, while underestimating demand can increase the risk of stockouts.

FORESIGHT aims to address these challenges by combining demand forecasting with inventory intelligence and an interactive analytics dashboard.

## Objectives

- Forecast product-level demand using historical retail data.
- Identify potential stockout and overstock risks.
- Provide actionable inventory insights.
- Support data-driven inventory planning.
- Present important business insights through an interactive dashboard.

## Key Features

- Retail demand forecasting
- SKU-level analysis
- Inventory risk identification
- Historical demand analysis
- Category and store-level analytics
- Interactive dashboard
- Data-driven inventory recommendations

## Dataset

The project uses a retail store inventory dataset containing daily records across multiple stores and products.

The dataset includes information such as:

- Date
- Store ID
- Product ID
- Category
- Region
- Inventory Level
- Units Sold
- Units Ordered
- Price
- Discount
- Weather Condition
- Holiday/Promotion
- Competitor Pricing
- Seasonality

## Data Preparation

The data preparation pipeline includes:

1. Data quality and consistency checks
2. Date-based train, validation, and test splitting
3. Calendar feature creation
4. Store-product level lag features
5. Rolling demand features
6. Numerical and categorical feature preprocessing
7. Preparation of model-ready datasets

## Project Structure

```text
FORESIGHT/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── models/
├── outputs/
├── src/
├── dashboard/
├── README.md
└── .gitignore