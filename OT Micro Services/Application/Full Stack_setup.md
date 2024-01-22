# OT Microservices Full Stack Setup Guide

| **Author** | **Created On** | **Last Updated** | **Document Version** |
| ---------- | -------------- | ---------------- | -------------------- |
| **Shreya Jaiswal** | 14-01-2024 | 22-01-2024 | V1 |
| **Parasharam Desai** | 14-01-2024 | 22-01-2024 | V1 |

*** 
# Table Of Content

### 1. [Introduction](#Introduction)

### 2. [Prerequisites](#Prerequisites)

### 3. [System Requirements](#System-Requirements)

### 4. [Dependencies](#Dependencies)

### 5. [Ports](#Ports)                                                                 

### 6. [Architecture](#Architecture)

### 7. [Full Stack Setup](#Full-Stack-Setup)

### 8. [Error Handling](#Error-Handling)

### 9. [Conclusion](#Conclusion)

### 10. [Reference](#Reference)

### 11. [Contact Information](#Contact-Information)

***

# Introduction

"Our OT microservices full stack setup is crafted with a modern and modular architecture, prioritizing scalability and efficiency. The system features dedicated APIs for managing employees (**Employee**), salaries (**Salary**), and attendance(**Attendance**), ensuring precision in workforce-related processes.

At the heart of our system lies **PostgreSQL**, a reliable database renowned for handling structured data, providing a robust foundation for crucial business information. **ScyllaDB**, a powerful NoSQL database, excels in efficiently managing large datasets, making it particularly valuable in scenarios where high performance and scalability are essential. Additionally, **Redis** plays a crucial role as an in-memory data store, enhancing system responsiveness by quickly providing access to frequently used information.

This combination of technologies forms the backbone of our microservices, delivering a solution that meets the demands of various industries, including manufacturing, energy, and utilities."

***
# Prerequisites

Before you proceed with the setup, make sure you have reviewed the following documentation:

| **APIs/Software** | **Link** |
| ----------------- | -------- |
| Frontend | [Frontend Documentation](https://github.com/avengers-p7/Documentation/blob/main/OT%20Micro%20Services/Application/Frontend.md) |
| Attendance API | [Attendance API Documentation](https://github.com/avengers-p7/Documentation/blob/main/OT%20Micro%20Services/Application/Attendance_API.md) |
| Salary API | [Salary API Documentation](https://github.com/avengers-p7/Documentation/blob/main/OT%20Micro%20Services/Application/Salary_API.md) |
| Employee API | [Employee API Documentation](https://github.com/avengers-p7/Documentation/blob/main/OT%20Micro%20Services/Application/Employee_API.md) |
| Redis Link | [Redis Documentation](https://github.com/avengers-p7/Documentation/blob/main/OT%20Micro%20Services/Software/Redis.md) |
| ScyllaDB Link | [ScyllaDB Documentation](https://github.com/avengers-p7/Documentation/blob/main/OT%20Micro%20Services/Software/ScyllaDB.md) |
| PostgreSQL Link | [PostgreSQL Documentation](https://github.com/avengers-p7/Documentation/blob/main/OT%20Micro%20Services/Software/PostgresSQL.md) |

***

# System Requirements

|   System Requirement              |             Minimum                     |
|-----------------------------------|-----------------------------------------|
| Processor/Instance Type           |                                         | 
| RAM                               |                                         |
| Disk Space                        |                                         |
| OS Required (Linux Distributions) |                                         |


***
# Dependencies
Before you proceed with the setup, make sure the following dependencies are installed in your setup:

### Build time Dependency

|          Name            |             Description               |
| ------------------------ |---------------------------------------|
| maven                    |   Build automation tool                 |
| java17                   |   Java Development Kit (JDK)            |
| poetry                   |   Python dependency management         |
| GNU make                 |   Build automation tool                 |
| npm                      |   Node package manager                  |


### Runtime Dependency

|          Name            |          Description                  |
| ------------------------ |---------------------------------------|
| ScyllaDB                 |    Database for employee API            |
| redis                    |   In-memory data store                  |
| postgres                 |   Relational database                   |
| liquibase                |   Database schema migration             |
| migrate                  |   Database migration tool               |
| jq                       |   Command-line JSON processor           |
| pylint                   |   Python linting tool                   |
| Node.js                  | JavaScript runtime for scalable network applications using Chrome's V8 engine. |

***

# Important Ports

Specify the important ports used by the microservices and their descriptions.

|Inbound Ports  | Description               |
|--------|---------------------------|
| 22     | SSH port                  |
| 3000   | Default REACTJS port      |
| 8080   | All API ports (Collective)|

| Outbound Ports  | Description          | 
|--------|----------------------|
| 5432   | PostgreSQL port       | 
| 6379   | Redis port            | 
| 9042   | Scylla DB port        | 
| 8080   | All API ports (Collective)| 

                     


***

# Architecture

![image](https://github.com/Parasharam-DevOps/Avenger-P7/assets/132131379/57b0df34-d415-4c50-abc2-240add12e423)



***

# Error Handling

Document common errors and their resolutions during the setup and usage of the microservices.

***

# Conclusion

In conclusion, the OT Microservices Full Stack Setup provides a modern and modular architecture that emphasizes scalability and efficiency. With dedicated APIs for employee management, salary processing, and attendance tracking, the system ensures precision in workforce-related processes.

The combination of robust databases such as PostgreSQL for structured data, ScyllaDB for efficient handling of large datasets, and Redis as an in-memory data store forms the backbone of our microservices. 





***

# Reference

Include any external sources or references used in the documentation.

| Source               | Description                |
| -------------------- | -------------------------- |
| Source 1             | Description 1              |
| Source 2             | Description 2              |
| Source 3             | Description 3              |
***

# Contact Information


| Name                 | Email                      |
| -------------------- | -------------------------- |
| Shreya Jaiswal       | shreya.jaiswal.snatak@mygurukulam.co |                          
| Parasharam Desai     |  parasharam.desai.snaatak@mygurukulam.co |

