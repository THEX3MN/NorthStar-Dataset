# NorthStar Urban Mobility Data Analytics & NoSQL Database Project

An integrated academic data analytics and database development project based on the **NorthStar Urban Mobility and Logistics** case study. The project investigates operational inefficiencies across transport, delivery, warehouse, customer service, and smart-city mobility operations using Python, SQL in R, R analytics, and MongoDB.

The repository follows the original project workflow used for academic submission, moving from raw data processing to structured SQL analysis, statistical analytics, and NoSQL database development.

## Project Overview

NorthStar Urban Mobility and Logistics is a regional organisation operating across multiple UK cities. The organisation manages public shuttle services, last-mile delivery, warehouse dispatch operations, electric vehicle charging hubs, route-planning systems, and a mobile customer platform.

The company faces several operational and analytical challenges, including:

* Increasing customer complaints
* Delayed journeys and missed delivery windows
* Rising vehicle downtime
* Inconsistent performance across city zones
* Fragmented data across multiple internal systems
* Difficulty connecting customer complaints, journeys, deliveries, driver incidents, and service exceptions
* Need for a scalable NoSQL solution for flexible and nested operational records

This project analyses the available data, identifies key operational issues, and designs a MongoDB-based NoSQL structure to support improved service tracking and decision-making.

## Project Objectives

The main objectives of this project are to:

* Process and clean raw operational datasets
* Prepare cleaned datasets for further analysis
* Use SQL within R to query structured operational data
* Apply R analytics to identify trends, relationships, and service performance patterns
* Explore operational issues across zones, hubs, customers, deliveries, and service events
* Design and implement a MongoDB document-based database structure
* Model nested service case records using MongoDB
* Demonstrate how structured and semi-structured data can support better operational decision-making

## Technologies Used

* Python
* Pandas
* R
* SQL in R
* MongoDB Atlas
* PyMongo
* Google Colab
* Jupyter Notebooks
* Data Cleaning
* Data Analysis
* Data Visualisation
* NoSQL Document Modelling
* CRUD Operations
* Indexing

## Project Workflow

### 1. Python Data Processing

The first notebook focuses on preparing the dataset for analysis. It includes:

* Loading raw datasets
* Previewing dataset structures
* Checking missing values
* Checking duplicate records
* Validating relationships between datasets
* Cleaning and preparing data
* Exporting cleaned datasets
* Producing selected operational visualisations

### 2. SQL in R

The second notebook applies SQL queries within R to explore structured data. It includes:

* Loading cleaned datasets into R
* Running SQL queries on operational data
* Producing table summaries
* Creating joined operational views
* Analysing zone-level performance
* Exploring relationships between customers, orders, deliveries, and service activity

### 3. R Analytics

The third notebook focuses on analytical interpretation and visualisation. It includes:

* Grouped operational analysis
* Service performance summaries
* Zone-based comparisons
* Correlation analysis
* Visualisations to support business interpretation
* Identification of operational patterns and performance issues

### 4. MongoDB Development

The fourth notebook focuses on NoSQL database design and implementation. It includes:

* Connecting to MongoDB Atlas
* Creating MongoDB collections
* Designing nested document structures
* Modelling service case records
* Inserting and querying documents
* Demonstrating CRUD operations
* Creating indexes to support query performance

## Screenshots and Selected Outputs

The screenshots below show selected previews from the project notebooks. Some notebook outputs are long, so only the most relevant visible sections are shown in the README for readability. Full code, outputs, and analysis are available inside the notebook files.

### Python Data Processing

#### Raw Dataset Preview

![Python Raw Dataset Preview](Screenshots/Python%20raw%20dataset%20preview.png)

#### Missing Values Summary

![Python Missing Values Summary](Screenshots/Python%20missing%20values%20summary%20preview.png)

#### Relationship Checks

![Python Relationship Checks](Screenshots/Python%20relationships%20check.png)

#### Cleaned Dataset Summary

![Python Cleaned Dataset Summary](Screenshots/Python%20cleaned%20dataset%20summary.png)

#### Delay Rate by Zone

![Python Delay Rate by Zone](Screenshots/Python%20delay%20rate%20by%20zone.png)

### SQL in R

#### SQL Row Count Preview

![SQL Row Count Preview](Screenshots/SQL%20row%20count%20preview.png)

#### SQL Joined Operational View Preview

![SQL Joined Operational View Preview](Screenshots/SQL%20joined%20operational%20view%20preview.png)

#### SQL Zone Performance Summary

![SQL Zone Performance Summary](Screenshots/SQL%20zone%20performance%20summary.png)

### R Analytics

#### Grouped Analysis Summary

![R Grouped Analysis Summary](Screenshots/R%20grouped%20analysis%20summary%20preview.png)

#### Correlation Analysis Output

![R Correlation Analysis Output](Screenshots/R%20correlation%20analysis%20output%20preview.png)

#### Deliveries by Zone Chart

![R Deliveries by Zone](Screenshots/R%20deliveries%20by%20zone.png)

### MongoDB Development

#### MongoDB Service Case Document

![MongoDB Service Case Document](Screenshots/MongoDB%20service%20case%20document%20output%20preview.png)

## MongoDB Security Note

The MongoDB Atlas connection string has been replaced with a placeholder for security purposes.

To run the MongoDB notebook, users must replace the placeholder connection string with their own MongoDB Atlas connection string:

```python
client = MongoClient("YOUR_MONGODB_ATLAS_CONNECTION_STRING")
```

Real database credentials should not be committed to a public GitHub repository.

## Key Skills Demonstrated

This project demonstrates practical experience in:

* Python data processing
* Data cleaning and preparation
* Relationship validation across datasets
* SQL querying and structured data analysis
* R-based analytics and visualisation
* Operational performance analysis
* MongoDB Atlas database development
* NoSQL document modelling
* Nested document design
* CRUD operations
* Index creation
* Data-driven business problem analysis

## Learning Outcomes

This project helped strengthen my understanding of:

* Working with fragmented operational datasets
* Preparing raw data for structured analysis
* Combining Python, SQL, R, and MongoDB in one analytical workflow
* Using SQL to explore business operations
* Applying R analytics to identify trends and relationships
* Designing NoSQL document structures for complex service records
* Understanding when document databases are useful for nested and evolving data
* Supporting business decision-making through integrated data analysis

## Future Improvements

* Add more advanced predictive analysis for service delays and failures
* Build an interactive dashboard for operational monitoring
* Expand MongoDB collections for drivers, hubs, vehicles, complaints, and service events
* Apply more advanced indexing strategies in MongoDB
* Add automated reporting for key performance indicators
* Develop a combined dashboard using Python or BI tools
* Add API-based access to MongoDB service case records
