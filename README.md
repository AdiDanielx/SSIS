# SSIS Data Integration Project

## Overview
This repository contains an SSIS project developed for educational purposes in a course on data warehousing and business intelligence. The project includes multiple DTSX packages designed to perform specific data transformations, loads, and to simulate ETL processes for a fitness club application.

## Features
Each package in the project corresponds to a question in the exercise, designed to address specific data warehousing challenges:

### Package.dtsx (Question 1)
- Builds the original database structure and populates it with random data.
- Demonstrates basic ETL functionalities and initial data loading techniques.

### Package1.dtsx (Question 2)
- Constructs a data warehouse schema from the original database.
- Implements data extraction and transformation strategies suitable for analytical processing.

### question7and9.dtsx (Questions 7 and 9)
- For Question 7: This package deals with the design considerations of slowly changing dimensions, particularly focusing on whether to use Type 1 or Type 2 SCD for user and exercise dimensions.
- For Question 9: Focuses on integrating new financial performance indicators into the data warehouse, explaining calculation methods for fully-additive facts and updating the DW accordingly.

## Prerequisites
- Microsoft SQL Server
- SQL Server Data Tools (SSDT) for Visual Studio

## Setup and Execution
1. Clone the repository to your local machine.
2. Open the `Ass_1.sln` file in Visual Studio with SQL Server Data Tools installed.
3. Configure the connection manager (`DESKTOP-HQGJ1AV_SQLEXPRESS.Ass1.conmgr`) with your SQL Server instance details.
4. Build the project to ensure all dependencies are correctly set up.
5. Execute the SSIS packages individually by right-clicking on each `.dtsx` file and selecting 'Execute Package'.

## Configuration
Ensure that the connection strings in the `DESKTOP-HQGJ1AV_SQLEXPRESS.Ass1.conmgr` file are correctly configured to match your SQL Server environment settings.

