PROJECT OVERVIEW

This repository contains the full analytics and database solution for the NorthStar Urban Mobility and Logistics case study. The project investigates operational performance, delivery efficiency, customer satisfaction, and digital platform reliability across multiple UK cities.

The analysis integrates multiple tools:

Python – for data cleaning, preprocessing, and feature engineering.

SQL in R – for structured queries, aggregation, and KPI summarisation.

R Analytics – for statistical analysis, grouped summaries, and visualisation.

MongoDB Atlas – for nested, flexible service-case database design and operational querying.

The project identifies operational hotspots, customer satisfaction issues, and resource performance gaps, while providing actionable recommendations based on the findings.

REPOSITORY STRUCTURE

NorthStar Dataset (Cleaned) - Contains the cleaned CSV datasets used for all analysis.

NorthStar Dataset (Raw) - Original, unprocessed CSV datasets for reference.

1 - Python Data Processing.ipynb - Notebook for cleaning, validating, and feature engineering the datasets in Python. Creates operational flags, performance indicators, and exploratory charts.

2 - SQL in R.ipynb - Notebook demonstrating SQL queries within R to generate hub, zone, service type, driver, vehicle, and customer performance summaries. Produces reusable KPI tables.

3 - R Analytics.ipynb - Notebook performing statistical analysis, grouped summaries, and visualisations. Highlights patterns in operational performance, customer satisfaction, and app-event success/failure.

4 - MongoDB Development.ipynb - Notebook using PyMongo to create and query a MongoDB Atlas database. Implements nested service-case documents integrating complaints, customers, orders, and app events. Demonstrates CRUD operations and indexing.

KEY FEATURES

Integrated Data Analysis: Combines structured and semi-structured datasets for operational and customer insights.

Python Processing: Handles cleaning, validation, feature engineering, and exploratory visualisations.

SQL in R: Produces management-level KPI tables using joins, filtering, grouping, and aggregation.

R Analytics: Generates descriptive statistics, grouped summaries, correlations, and visualisations to interpret operational and customer patterns.

MongoDB Service-Case Design: Implements a flexible, nested document structure for integrated operational case tracking.

Optimisation and Reusability: Pre-aggregated tables, reusable feature flags, grouped summaries, and indexed service-case documents improve efficiency and interpretability.

USAGE INSTRUCTIONS

1. Clone the repository.
   
2. Upload datasets from NorthStar Dataset (Cleaned) to your working environment.
   
3. Execute notebooks in order:
   
   1 - Python Data Processing.ipynb
  
   2 - SQL in R.ipynb
  
   3 - R Analytics.ipynb
  
   4 - MongoDB Development.ipynb

4. Ensure all necessary packages/libraries are installed:
   
Python: pandas, numpy, matplotlib, seaborn

R: tidyverse, dplyr, tibble, sqldf, ggplot2

MongoDB: pymongo, MongoDB Atlas connection string
