# DWBI Practical
![dw](https://github.com/Meriyan99/DWBI_Practical/assets/128514985/941665ac-83db-426d-8797-e03f90d8c07d)

#### This data warehousing solution is related to the 3rd Year 1st Semester DWBI(Data Warehousing and Business Intelligence) Module's Practical series. This project is centered around providing a robust and efficient data warehouse solution tailored specifically for retail service. The main objective is to organize, store, and manage large volumes of data from various sources to facilitate data analysis and decision-making processes for the retail domain. This has up to the creation of a Data Warehouse solution.

## Solution Architecture

![archi](https://github.com/Meriyan99/DWBI_Practical/assets/128514985/21c70905-7001-4e45-9218-c99bc5d78bc8)

## Schema Design
#### This Data Warehouse follows a Snowflake Schema Since all the dimensions are not directly connected with the fact table.

![dwbi_schema drawio](https://github.com/Meriyan99/DWBI_Practical/assets/128514985/e636a906-6901-4919-bd2c-9dde49089ccb)

## ETL Development
### Load data from Sources to Staging Database

![retail_build_2](https://github.com/Meriyan99/DWBI_Practical/assets/128514985/b3ae0930-49f8-4745-af54-4d17910c6447)

### Load data from Staging database to Data Warehouse

![retail_load_2](https://github.com/Meriyan99/DWBI_Practical/assets/128514985/68827aa7-63cc-4bc6-953c-5d14b56a48d4)

## Tools Used in this Project
1. Microsoft SQL Server
2. Visual Studio 2022 (SSIS)
3. Microsoft Excel
