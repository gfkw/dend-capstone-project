# Capstone Project

The purpose of the data engineering capstone project is to give you a chance to combine what you've learned throughout the program. This project will be an important part of your portfolio that will help you achieve your data engineering-related career goals. In this project, you can choose to complete the project provided for you, or define the scope and data for a project of your own design. Either way, you'll be expected to go through the same steps outlined below.

## Scope the Project and Gather Data



### Prerequisites


Tables must be created in Redshift before executing the DAG workflow. The create tables statements can be found in:

`create_tables.sql`

## Data Sources



## Data Quality Checks

In order to ensure the tables were properly loaded, a data quality checking is performed to count the total records each table has. If a table has no rows then the workflow will fail and throw an error message.

## Scripts Usage

* `create_tables.sql` - Contains the DDL for all tables used in this projecs


## Built With

* [Python 3.6.2](https://www.python.org/downloads/release/python-363/) - Used to code DAG's and its dependecies
* [Apache Airflow 1.10.2](https://airflow.apache.org/) - Workflows platform

## Authors

* **Guilherme Furukawa** - *Initial work* - Udacity student

