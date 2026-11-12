# BlinkIT-Grocery-Analysis
A business intelligence project that explores grocery item sales and outlet characteristics using Excel as the source dataset and Microsoft Power BI for interactive reporting.

# Project Overview
This project analyzes a BlinkIT grocery dataset containing item-level and outlet-level information. The dataset includes product categories, item fat content, item visibility, item weight, sales, ratings, outlet establishment year, outlet size, outlet location tier, and outlet type.

The Excel workbook is used as the source dataset, and the Power BI report provides an interactive way to explore the data. The purpose of the project is to organize the available information into meaningful views that can support the understanding of grocery sales performance and outlet characteristics.
Problem Statement
Retail businesses generate data across products, categories, and store locations. However, raw spreadsheets containing thousands of records can make it difficult to understand sales performance, compare product categories, identify differences between outlet types, and evaluate other business patterns.

The challenge addressed by this project is to transform the supplied BlinkIT grocery dataset into an organized and interactive Power BI report. The analysis focuses on exploring how sales are distributed across item types and outlet characteristics, while also examining product attributes such as fat content, visibility, weight, and rating.

Problem to solve: How can the available grocery sales and outlet data be analyzed and presented in a clear, interactive dashboard so that users can explore sales patterns, compare outlet segments, and make better-informed business decisions?

# Business Context
For a grocery retail business, understanding sales across product categories and outlet segments can help with business review and planning. Product attributes and outlet characteristics provide additional dimensions for exploring the dataset.

This project uses the fields available in the supplied workbook to support descriptive analysis. It does not claim to measure profitability, customer behavior, inventory turnover, or causes of sales performance because those measures and supporting data are not provided in the workbook.

# Project Objectives
1. Analyze the overall distribution of sales in the supplied dataset.
2. Compare sales across different item types.
3. Explore sales across outlet types, outlet sizes, and outlet location tiers.
4. Examine the distribution of items by fat-content category.
5. Explore item visibility and item weight as product-related attributes.
6. Review the available item ratings.
7. Present the analysis in an interactive Power BI dashboard.
8. Make the dataset and report easy to understand and reproduce.

# Data preparation recommendations
1. Standardize LF and low fat as Low Fat.
2. Standardize reg as Regular.
3. Decide how missing item weights should be handled and document the decision.
4. Keep item and outlet identifiers as categorical fields.
5. Confirm units and definitions from the original dataset source before assigning a currency or weight unit.

# Methodology and Workflow
The project follows this general workflow:
1. Data collection: Use the supplied BlinkIT grocery Excel workbook.
2. Data understanding: Review the columns, data types, categories, and missing values.
3. Data preparation: Standardize inconsistent category labels and decide how to handle missing values where needed.
4. Data modeling: Load the prepared data into Power BI and configure fields for analysis.
5. Data analysis: Compare sales and product/outlet attributes using suitable aggregations.
6. Data visualization: Present the analysis through charts, tables, cards, and filters as applicable in the report.
7. Validation: Check totals, category labels, and visual results against the source data.
8. Documentation: Record the dataset details, project purpose, and instructions in this repository.
