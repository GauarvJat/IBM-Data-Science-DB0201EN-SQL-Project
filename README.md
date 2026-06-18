# Chicago Data Analysis: SQL & Python Project

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Project Overview
This project is a comprehensive data analysis exercise, forming the final project for the **IBM Databases and SQL for Data Science** course. It demonstrates the use of Python and SQL to analyze real-world public datasets from Chicago, focusing on crime, education, and socioeconomic indicators.

The main goal is to showcase skills in:
- **ETL Pipelines**: Loading CSV data into relational databases (SQLite and IBM Db2).
- **Advanced SQL**: Writing and executing complex queries (e.g., sub-queries, aggregate functions, joins) to solve specific business problems.
- **Python Integration**: Using Jupyter Notebooks with libraries like Pandas and ipython-sql to orchestrate the entire workflow.

## Datasets Used
The analysis uses three datasets from the City of Chicago Data Portal:
- **Census Data**: Socioeconomic indicators and hardship index per community area.
- **Public Schools Data**: Performance and safety metrics for Chicago Public Schools.
- **Crime Data**: Detailed records of crimes reported in Chicago from 2001 to present.

## Repository Structure
├── data/

│ ├── ChicagoCensusData.csv

│ ├── ChicagoCrimeData.csv

│ └── ChicagoPublicSchools.csv

├── Working_with_SQLite.ipynb

├── Working_with_Db2.ipynb

├── Final_Assignment_SQLite.ipynb

├── requirements.txt

└── README.md

## Key Findings and Questions Addressed
The analysis answered several key questions:
- **Crime Analysis**: Identified the community areas with the highest crime rates and the types of crimes most often recorded at schools.
- **Education Insights**: Analyzed the relationship between school safety scores, student attendance, and school type.
- **Socioeconomic Correlation**: Found associations between poverty levels, hardship index, and college enrollment rates across different community areas.

## Technologies Used

Python: The core programming language.

Pandas: For data ingestion and manipulation.

SQLite3 & SQLAlchemy: For database creation and connection.

Jupyter Notebooks: For an interactive and reproducible analysis environment.

IBM Db2: To demonstrate cloud database capabilities.
