# Database-Course-Documentation

## Table Of Contents
- [1. Flat File Systems vs. Relational Databases](#1-flat-file-systems-vs-relational-databases)
- [2. DBMS Advantages – Mind Map](#2-dbms-advantages---mind-map)
- [3. Roles in a Database System](#3-roles-in-a-database-system)
- [4. Types of Databases](#4-types-of-databases)
- [5. Cloud Storage and Databases](#5-cloud-storage-and-databases)

## 1. Flat File Systems vs. Relational Databases

| Feature         | Flat File System                        | Relational Database                                 |
|:---------------:|:---------------------------------------:|:---------------------------------------------------:|
| **Structure**   | Plain text like .txt and .csv           | Tables with columns and rows                        |
| **Redundancy**  | High, data is often repeated            | Low, data is normalized to reduce redundancy        |
| **Relationships** | Not supported                         | Supported through foreign keys and relationships    |
| **Example Use** | Config files, Excel (.csv) spreadsheets | Banking systems, Oracle, MySQL                      |
| **Drawbacks**   | Inefficient data management             | Complex setup and requires DBMS software to maintain|

## 2. DBMS Advantages - Mind Map
This MindMap illustrates a visual representation of the advantages of using a Database Management System and includes short points of each advantage.

<img width="2008" height="820" alt="Advantages of Using a DBMS" src="https://github.com/user-attachments/assets/183536e7-e337-48d5-9f53-5e0f245512d6" />

## 3. Roles in a Database System
| Role                             | Description                                              |
| -------------------------------- | -------------------------------------------------------- |
| **System Analyst**               | Gathers requirements from users, communicates with stakeholders, and designs database workflows.                |
| **Database Designer**            | Designs the structure of the database by creating a detailed database model schema.                   |
| **Database Developer**           | Implements and maintains a database by writing SQL queries, adding logic and triggers for data retrieval and manipulation. |
| **Database Administrator (DBA)** | Manages and monitors performance, access control, security, and maintenance of a database.          |
| **Application Developer**        | Develops applications or a user-friendly interface that users use to interact with the database.     |
| **BI Developer**                 | Creates reports, dashboards, and data analytics for stakeholders to view and make decisions based on the insights.        |


## 4. Types of Databases
### Relational vs Non-Relational:
| **Type**            | **Description**                                             | **Examples**                         |
|---------------------|-------------------------------------------------------------|--------------------------------------|
| **Relational**      | Is structured, tabular, and SQL-based.                      | MySQL, Oracle, PostgreSQL            |
| **Non-Relational**  | Document/Key-Value, flexible schema.                        | MongoDB, Cassandra                   |


### Centralized vs Distributed vs Cloud:
| **Type**       | **Description**                                                                                                                   | **Use Cases**                                                   |
|----------------|-----------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------|
| **Centralized**| Has a single location/server. Users access the database through one point.                                                        | Small businesses, departmental applications                     |
| **Distributed**| Has many locations/servers using nodes that hold the same or different data according to geographical location (RAID concept).    | Global enterprise systems, real-time applications (Google Maps) |
| **Cloud**      | Cloud storage is hosted on online hosting platforms like AWS and are managed as a DbaaS by the hosting platform.                  | Startups, backup databases, educational systems                 |


## 5. Cloud Storage and Databases
