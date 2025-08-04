# Project Structure

## Project Overview

This Power BI dashboard analyzes customer behavior, demographics and churn patterns for a fictional bank.The goal is to understand who the customers are why are leaving and how to impprove customer retention rate using interactve and dynamic visualizations.
## Data Preparation

Performed in Power query editor:
* Removed nulls and inconsistencies
* Applied data types
* Cleaned and standardized feilds
## Data modeling

Created a star schema in the model view:
* Relationships were built between the Fact tables and dimension tables by using primary key columns.
## Dashboard

## Page 1: Customer Demographics Overview

Visualizing customer profiles and distributions.



## Page 2: Customer Churn Analysis

Identifying churn patterns, trends, and drivers.

## Bookmark Navigation

Purpose: Improve user experience and enable navigation like an app.
 Bookmarks Used:
* Customer_Overview
* Churn_Analysis

## Buttons added to each page:

“Customer Overview” → linked to the Customer_Overview bookmark
“Churn Analysis” → linked to the Churn_Analysis bookmark

## Goals Achieved

* Clean and structured model with relationships
*Clear, interactive dashboards
* Bookmark-based navigation
* Business-friendly insights into customer churn


## Future Enhancements

* Add a tooltip page for customer-level detail
* Integrate ML churn prediction model
*Publish to Power BI Service with row-level security (RLS)
