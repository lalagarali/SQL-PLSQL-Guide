# SQL-PLSQL-Guide

## 📚 Table of Contents
1. [Introduction](#introduction)
2. [Oracle SQL: Basic Elements](#oracle-sql-basic-elements)

## Introduction

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

**Data Types**

| **Data Type** | **Description**     |
|---------------|---------------------|
| CHAR          | Fixed-length character data.|
| VARCHAR2      | Variable-length character data.  |
| NCHAR         | Fixed-length Unicode character data |
| NVARCHAR2     | Variable-length Unicode character data.|
| CLOB          | Character large object for large text storage.      |
| NCLOB         | Unicode CLOB data type.                             |
| NUMBER        | Numeric data type.         |
| INTEGER       | Smaller version of NUMBER (38).                     |
| DECIMAL       | Fixed-point numbers (e.g., DECIMAL(10,2)).           |
| FLOAT         | Floating-point numbers.                              |
| BINARY_FLOAT  | Oracle-specific FLOAT.                      |
| BINARY_DOUBLE | Oracle-specific DOUBLE.                     |
| DATE          | Date and time storage.                              |
| TIMESTAMP     | Date and time with fractional seconds.               |
| TIMESTAMP TZ  | Date, time, and time zone info.                      |
| INTERVAL YEAR-MONTH | Interval between two dates (years and months). |
| INTERVAL DAY-SECOND | Interval between two dates (days and seconds). |
| RAW           | Used to store binary data (e.g., BLOB, image).       |
| LONG RAW      | Deprecated; for large binary data.                   |
| BLOB          | Binary Large Object (large binary data).             |
| BFILE         | External file storage.                               |
| LONG          | Deprecated; large character data (up to 2 GB).       |
| ROWID         | Unique row ID of a table.                            |
| UROWID        | Universal Row ID for partitioned tables.             |
| XMLTYPE       | Stores XML data.                                     |
| ANYTYPE       | Generic data type for any type of data.              |
| ANYDATA       | Stores any type of data dynamically.                 |

SQL Table Creation with All Oracle Data Types

The following SQL script creates a table named all_oracle_data_types that includes various Oracle SQL data types, with realistic column names and example values.

```sql
CREATE TABLE all_oracle_data_types (
    customer_name VARCHAR2(50),  -- Customer's full name
    gender CHAR(1),  -- Gender ('M' for Male, 'F' for Female)
    customer_id NUMBER,  -- Unique customer identifier
    age INTEGER,  -- Age of the customer
    balance FLOAT,  -- Account balance
    annual_salary DOUBLE PRECISION,  -- Annual salary
    join_date DATE,  -- Date when the customer joined
    last_purchase TIMESTAMP,  -- Last purchase timestamp
    time_difference INTERVAL DAY TO SECOND,  -- Time interval example
    bio CLOB,  -- Large text data (e.g., biography)
    profile_picture BLOB,  -- Binary data (e.g., profile picture)
    transaction_id RAW(16),  -- Unique transaction ID
    description LONG,  -- Long text description (deprecated, but still supported)
    country_code NCHAR(5),  -- Country code (Unicode)
    preferred_language NVARCHAR2(20),  -- Preferred language (Unicode)
    customer_data XMLTYPE,  -- XML formatted customer data
    is_active BOOLEAN,  -- Boolean value indicating active status (PL/SQL only)
    height BINARY_FLOAT,  -- Floating-point value (32-bit)
    weight BINARY_DOUBLE,  -- Floating-point value (64-bit)
    row_id UROWID  -- Universal row ID
);
```

• Data Type Comparison Rules
• Literals
• Format Models
• Nulls
• Comments
• Database Objects
• Database Object Names and Qualifiers
• Syntax for Schema Objects and Parts in SQL Statements








