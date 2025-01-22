# SQL-PLSQL-Guide

## 📚 Table of Contents
1. [Introduction](#introduction)
2. [Oracle SQL: Basic Elements](#oracle-sql-basic-elements)

### 1. Introduction

**What is Data?**

![image](https://github.com/user-attachments/assets/92a6b470-d97c-416a-85a3-dc5c945b202b)

**Data** is raw facts or figures.

**Information** is processed data that is meaningful.

**Knowledge** is understanding gained from information.

**What is dataset?** A dataset is a collection of related data organized in a structured format, often in rows and columns, like a table.

![image](https://raw.githubusercontent.com/lalagarali/SQL-PLSQL-Guide/refs/heads/main/43E5890B-0DB1-439D-B26C-91716842BD82.png)

**What is Big Data?** Big data is a term used to describe extremely large datasets that are difficult to store, process, and analyze using traditional methods due to their size, speed, and variety.

![image](https://raw.githubusercontent.com/lalagarali/SQL-PLSQL-Guide/refs/heads/main/IMG_6041.jpeg)

**What is Database?**

**Database**: Stores structured data for daily transactions and operations.

**Data Lake**: A large, raw data storage system that holds unstructured and structured data.

**Data Mart**: A smaller, focused version of a data warehouse, tailored to specific business needs.

**Data Warehouse**: A central repository for integrated, structured data designed for analysis and reporting.

![image](https://raw.githubusercontent.com/lalagarali/SQL-PLSQL-Guide/refs/heads/main/IMG_6046.jpeg)

**What is SQL?** SQL (Structured Query Language) is the standard language used for managing and manipulating databases.

![image](https://github.com/user-attachments/assets/ba989f99-6e85-4813-9cf5-d4dbfca66532)

**What is PL/SQL?** PL/SQL (Procedural Language/SQL) is an extension of SQL used for writing complex queries and procedures, adding procedural logic to SQL.

![image](https://github.com/user-attachments/assets/3f1e3e40-2758-4960-9d79-2d6c788b9f58)

## Oracle SQL: Basic Elements

• **Data Types**

| **Data Type**  | **Description**                                                                                                          |
|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| CHAR                             | Fixed-length character data type (1-2000 characters).                                                                    |
| VARCHAR2                         | Variable-length character data type (1-4000 characters).                                                                  |
| NCHAR                            | Fixed-length Unicode character data type (1-2000 characters).                                                            |
| NVARCHAR2                        | Variable-length Unicode character data type (1-4000 characters).                                                          |
| CLOB                             | Character large object data type for storing large text data.                                                             |
| NCLOB                            | Unicode character large object data type (Unicode version of CLOB).                                                       |
| NUMBER                           | Numeric data type (for both integer and floating-point numbers).                                                           |
| INTEGER                          | Integer data type (a smaller version of NUMBER(38)).                                                                       |
| DECIMAL                          | Used for fixed-point numbers (e.g., DECIMAL(10,2)).                                                                        |
| FLOAT                            | Numeric data type for floating-point numbers.                                                                             |
| BINARY_FLOAT                     | Oracle-specific implementation of the FLOAT data type (4-byte representation).                                            |
| BINARY_DOUBLE                    | Oracle-specific implementation of the DOUBLE data type (8-byte representation).                                          |
| DATE                             | Stores date and time data (from January 1, 4712 BC).                                                                       |
| TIMESTAMP                        | Date and time data with precision up to fractional seconds.                                                                |
| TIMESTAMP WITH TIME ZONE         | Stores date, time, and time zone information.                                                                              |
| TIMESTAMP WITH LOCAL TIME ZONE   | Stores date, time, and local time zone information.                                                                       |
| INTERVAL YEAR TO MONTH           | Stores the interval between two dates in terms of years and months.                                                        |
| INTERVAL DAY TO SECOND           | Stores the interval between two dates in terms of days and seconds.                                                        |
| RAW                              | Used to store binary data (e.g., BLOB or image data).                                                                     |
| LONG RAW                         | Used to store large binary data, but is deprecated in newer implementations.                                               |
| BLOB                             | Binary Large Object (for storing large binary data such as images and audio files).                                       |
| BFILE                            | Used to store external files in the file system.                                                                           |
| LONG                             | Deprecated, used to store large amounts of character data (up to 2 GB).                                                   |
| ROWID                            | Stores the unique row ID of a table (internal Oracle representation of a row).                                            |
| UROWID                           | Universal Row ID for ROWID in cluster and partitioned tables.                                                             |
| XMLTYPE                          | Used to store XML data.                                                                                                   |
| ANYTYPE                          | Used to store any type of data (a generic data type).                                                                     |
| ANYDATA                          | Used to store data of any type, allows for dynamic handling of different data types.                                      |


• Data Type Comparison Rules
• Literals
• Format Models
• Nulls
• Comments
• Database Objects
• Database Object Names and Qualifiers
• Syntax for Schema Objects and Parts in SQL Statements








