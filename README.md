# University Academic Performance Data Warehouse

## Overview

This project, developed for the Information Systems II course, is a comprehensive Data Warehouse and Business Intelligence system designed to analyze and monitor the academic performance of university students. The primary goal is to provide university management with strategic insights to improve teaching quality, enhance student success, and optimize resource allocation.

The system processes and integrates data from various sources to build a robust Data Warehouse using a star schema. Interactive dashboards and reports were created using Power BI to visualize key performance indicators (KPIs) and facilitate data-driven decision-making.

This repository is divided into two main parts:
* **Part 1: Research Report** - A theoretical exploration of "The Use of Python for Data Analysis."
* **Part 2: Practical Implementation** - The development of the Data Warehouse, from data modeling and ETL simulation to the final BI dashboards.

## Key Features

* **Dimensional Modeling**: Designed and implemented a star schema to effectively store and query academic data. The model includes detailed dimensions for students, courses, subjects, time, and financial status.
* **ETL Process Simulation**: Developed procedures to simulate the Extraction, Transformation, and Loading (ETL) of data from disparate sources (relational databases and CSV files) into the Data Warehouse.
* **In-depth Academic Analysis**: The system allows for a multifaceted analysis of student performance, considering variables such as:
    * Socioeconomic and demographic data.
    * Enrollment status (pending, completed).
    * Financial situation (tuition fees in arrears, financial aid).
    * Attendance type (full-time, part-time).
* **Strategic Dashboards**: Created interactive and intuitive dashboards in Power BI that provide a clear overview of academic trends and allow for detailed drill-down analysis.
* **Business Insights**: The solution is built to answer critical business questions, such as identifying at-risk students, determining the most profitable courses, and discovering patterns that influence academic success or failure.

## Technologies Used

* **Database**: SQL Server
* **Business Intelligence**: Power BI, Microsoft Analysis Services
* **Data Modeling**: Star Schema
* **Data Integration**: ETL (Extraction, Transformation, Loading) simulation

## Project Structure

The repository contains all the necessary components to understand and replicate the project:

* **`/Parte 1/`**: Contains the research report and presentation slides on using Python for data analysis.
* **`/Parte 2/`**: Includes all assets for the practical implementation:
    * `Create.sql`: SQL script to create the database schema.
    * `Dados Gerados por tabelas/`: A collection of SQL scripts with synthetic data for populating the database.
    * `Modelo Conceptual.png` & `Modelo Fisco.png`: Images of the conceptual and physical data models.
    * `tpbi.pbix`: The Power BI project file with all the dashboards and reports.
    * `TpCuboVS/`: The Visual Studio project for the Analysis Services cube.
    * `*.pdf`: The final report detailing all the choices and steps taken during the project development.

This project demonstrates a strong understanding of Data Warehousing principles, from backend database design and data integration to frontend business intelligence and data visualization. It showcases the ability to translate a business need into a complete, functional, and insightful technical solution.
