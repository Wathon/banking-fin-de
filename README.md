# Project Name: Fintech SSIS Project

## Overview

This SSIS project extracts data from various sources, transforms it, and loads it into a centralized data warehouse.

## Packages

### Package 1: Data Importing

This package extracts sales data from a flat file source and loads it into a SQL Server database. The package includes the following components:

-   Flat File Source: Reads data from a CSV files from FlatFileData directory (note: need to configure in SSIS variables)
-   Data Conversion & Derived: Converts data types from string to appropriate data types for the target database
-   OLE DB Destination: Loads data into a SQL Server table

## Data Mapping
![Mapping](diagram/DWLoan.png)

## Data Dictionary
![Data Dictionary1](diagram/Data%20dictionary-1.png)
![Data Dictionary1](diagram/Data%20dictionary-2.png)
![Data Dictionary1](diagram/Data%20dictionary-3.png)


## Sample Run Project Overview
![complete](diagram/complete.png)