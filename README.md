# E.Commerce
# Project Overview
The project aims to create a relational database based on the contents of the provided dataset, Sample-Superstore.csv. 

* The primary objectives include:

Designing an Entity-Relationship Diagram (ERD) to model the database schema.
Implementing the relational database using SQLite as the Relational Database Management System (RDBMS).
Conducting Exploratory Data Analysis (EDA) to gain insights into the dataset.
Cluster customers according to their purchasing pattern.
# Folder Structure
* README.md
* Sample-Superstore.csv
* DB_creation.ipynb
* Data_Conversion.ipynb
* EDA.ipynb
* Clustering.ipynb
* SuperstoreDB: - VS_GROUP_DataBase.db - VS_GROUP_DataBase.sqbpro - VS_GROUP__ERD.png
* SuperstoreTables: - address.csv - orders.csv - products.csv - customers.csv - orders_details.csv
* Clustered: - clustered_data.csv


# Entity-Relationship Diagram (ERD)
The ERD was created using dbdiagram.io and is visualized in the attached image file: VS_GROUP__ERD.png.

# Data Transfer and Preparation
The process involves transferring data from the initial CSV file to the database and ensuring data integrity and consistency. This includes:

* Initial exploration of the Sample-Superstore.csv file to understand its structure and contents.
* Data conversion and formatting as necessary to align with database requirements.
* Partitioning the dataset into separate tables based on relevant topics, ensuring each table has unique primary keys and eliminating unnecessary duplicated data. Ultimately ensuring that it passes forms of normalization.
* Saving the partitioned data as individual CSV files for convenience and later use.
* Saving the data in a SQLite database.
* Testing the database by performing queries.
# EDA and Clustering
* Explore the e-commerce dataset focusing on orders, sales, profit, customers and typical e-commerce KPIs.
* Cluster the customers by purchasing patterns using 3 parameters: Monetary (amount of money spent), Frequency (how frequently the customer bought something) and Recency (how many days has passed from today to their last purchase).
## VS_GROUP_DataBase.sqbpro
This is a set of queries aimed at solving specific exercises based on Epic 4 from the Code Academy Berlin LMS. The queries are designed to extract insights and perform analysis on the Superstore database.
# Notebooks Overview
## Data_Conversion.ipynb
This notebook serves as the initial step in the data preparation process. Here's an overview of the tasks performed:

* Load the dataset (Sample-Superstore.csv) as a CSV file.
* Conduct an initial examination of the dataset to understand its structure and contents.
* Perform data conversion and transformation as necessary to prepare it for database insertion.
* Split the dataset into separate tables according to predefined topics, ensuring each table has a unique primary key and eliminating redundant data.
* Save the partitioned data as individual CSV files for future reference and use.
## DB_creation.ipynb
This notebook focuses on the creation of the Superstore database (VS_GROUP_DataBase.db) and populating it with data extracted from the CSV files generated in the Data_Conversion.ipynb notebook. The key tasks performed in this notebook include:

* Creating the SQLite database VS_GROUP_DataBase.db 
* Importing the structured data from the CSV files generated in the Data_Conversion.ipynb notebook.
* Ensuring data integrity and consistency during the database population process.



## EDA.ipynb
This notebook focuses on the exploratory data analysis with focus on insights relevant for e-commerce. Some relevant e-commerce KPIs are included. The data is visualized using plotly express.

## Clustering.ipynb
In this notebook the customers get clustered by purchasing patterns using 3 parameters: Monetary (amount of money spent), Frequency (how frequently the customer bought something) and Recency (how many days has passed from today to their last purchase). The results are further exported to clustered_data.csv.


For a comprehensive overview, please check out the [project presentation](https://docs.google.com/presentation/d/189jkZp9nHZgpW0Cbg1WBahSjS-CWcn9BALe9Of76EP0/edit#slide=id.g2df3dbcb3fd_1_29) and [Tableau Dashboard](https://public.tableau.com/app/profile/godwin.oti5506/viz/VSGROUPTABLEAU/ProfitSalesDashboard).
