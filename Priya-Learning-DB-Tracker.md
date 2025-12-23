# Priya Learning - Database & SQL Learning Plan

## 📚 Complete Learning Roadmap for Database Fresher

> **How to Use This Plan:**
> - Each learning item has a checkbox `- [ ]`
> - Click the checkbox or replace `[ ]` with `[x]` to mark as completed
> - Track your progress through each phase systematically
> - Don't skip phases - each builds on the previous one

## 📊 Progress Tracker

### Overall Progress
- [ ] Phase 1: Database Fundamentals (Week 1-2) - 0/3 sections completed
- [ ] Phase 2: MySQL Deep Dive (Week 3-4) - 0/6 sections completed  
- [ ] Phase 3: SQL Fundamentals (Week 5-6) - 0/3 sections completed
- [ ] Phase 4: SQL Query Fundamentals (Week 7-8) - 0/2 sections completed
- [ ] Phase 5: Advanced SQL Queries (Week 9-10) - 0/4 sections completed
- [ ] Phase 6: MySQL Advanced Features (Week 11-12) - 0/4 sections completed
- [ ] Phase 7: Database Administration Basics (Week 13-14) - 0/3 sections completed
- [ ] Phase 8: Practical Projects (Week 15-16) - 0/3 projects completed

### Phase 1: Database Fundamentals (Week 1-2)

#### 1.1 What is a Database?
- [ ] Understand data vs information
- [ ] Learn why databases are needed
- [ ] Explore real-world database examples
- [ ] Understand database vs file systems

#### 1.2 Types of Databases
- [ ] **Relational Databases (RDBMS)**
  - MySQL, PostgreSQL, Oracle, SQL Server
  - Uses tables with rows and columns
  - ACID properties
- [ ] **NoSQL Databases**
  - Document: MongoDB, CouchDBw
  - Key-Value: Redis, DynamoDB
  - Column-family: Cassandra, HBase
  - Graph: Neo4j, Amazon Neptune
- [ ] **NewSQL Databases**
  - CockroachDB, VoltDB
- [ ] **In-Memory Databases**
  - Redis, Memcached
- [ ] **Cloud Databases**
  - AWS RDS, Google Cloud SQL, Azure SQL

#### 1.3 Database Concepts
- [ ] Tables, Rows, Columns
- [ ] Primary Key, Foreign Key
- [ ] Relationships (One-to-One, One-to-Many, Many-to-Many)
- [ ] Data Types
- [ ] Constraints
- [ ] Indexes

---

### Phase 2: MySQL Deep Dive (Week 3-4)

#### 2.1 MySQL Introduction
- [ ] What is MySQL?
- [ ] MySQL vs other databases
- [ ] MySQL versions and editions
- [ ] MySQL ecosystem and tools

#### 2.2 MySQL Installation & Setup
- [ ] Install MySQL Server
- [ ] Install MySQL Workbench
- [ ] Configure MySQL
- [ ] Connect to MySQL server
- [ ] Create first database

#### 2.3 MySQL Architecture
- [ ] **MySQL Server Architecture**
  - Connection Layer
  - SQL Layer
  - Storage Engine Layer
- [ ] **MySQL Process List**
- [ ] **MySQL Memory Structure**
  - Buffer Pool
  - Redo Log Buffer
  - Query Cache

#### 2.4 MySQL Storage Engines
- [ ] **InnoDB (Default)**
  - ACID compliant
  - Row-level locking
  - Foreign key support
  - Crash recovery
- [ ] **MyISAM**
  - Table-level locking
  - Fast for read-heavy workloads
  - No foreign key support
- [ ] **Memory (HEAP)**
  - Data stored in RAM
  - Very fast access
  - Data lost on restart
- [ ] **CSV**
  - Data stored as CSV files
- [ ] **Archive**
  - For compressed storage
- [ ] **Choosing the right engine**

#### 2.5 MySQL Data Types
- [ ] **Numeric Types**
  - TINYINT, SMALLINT, MEDIUMINT, INT, BIGINT
  - DECIMAL, FLOAT, DOUBLE
- [ ] **String Types**
  - CHAR, VARCHAR
  - TEXT, LONGTEXT
  - BINARY, VARBINARY
- [ ] **Date and Time Types**
  - DATE, TIME, DATETIME
  - TIMESTAMP, YEAR
- [ ] **JSON Data Type**
- [ ] **Choosing appropriate data types**

#### 2.6 MySQL Configuration
- [ ] my.cnf / my.ini configuration file
- [ ] Important configuration parameters
- [ ] Performance tuning basics
- [ ] Security configurations

---

### Phase 3: SQL Fundamentals (Week 5-6)

#### 3.1 Introduction to SQL
- [ ] What is SQL?
- [ ] SQL standards (ANSI SQL)
- [ ] SQL categories:
  - DDL (Data Definition Language)
  - DML (Data Manipulation Language)
  - DQL (Data Query Language)
  - DCL (Data Control Language)
  - TCL (Transaction Control Language)

#### 3.2 Database Design Principles
- [ ] **Normalization**
  - 1NF, 2NF, 3NF, BCNF
  - When to normalize vs denormalize
- [ ] **Entity Relationship Diagrams (ERD)**
- [ ] **Database Schema Design**
- [ ] **Best Practices**

#### 3.3 DDL - Data Definition Language
- [ ] **CREATE DATABASE**
- [ ] **CREATE TABLE**
  - Column definitions
  - Constraints (PRIMARY KEY, FOREIGN KEY, UNIQUE, NOT NULL, CHECK)
  - AUTO_INCREMENT
- [ ] **ALTER TABLE**
  - Add/Drop columns
  - Modify columns
  - Add/Drop constraints
- [ ] **DROP TABLE / DATABASE**
- [ ] **TRUNCATE TABLE**

---

### Phase 4: SQL Query Fundamentals (Week 7-8)

#### 4.1 DML - Data Manipulation Language
- [ ] **INSERT**
  - Single row insert
  - Multiple row insert
  - INSERT ... SELECT
- [ ] **UPDATE**
  - Single table update
  - Multi-table update
  - Conditional updates
- [ ] **DELETE**
  - DELETE with WHERE
  - DELETE with JOIN
  - TRUNCATE vs DELETE

#### 4.2 DQL - Basic Queries
- [ ] **SELECT Statement Structure**
- [ ] **SELECT ... FROM**
- [ ] **WHERE Clause**
  - Comparison operators (=, !=, <, >, <=, >=)
  - Logical operators (AND, OR, NOT)
  - IN, NOT IN
  - BETWEEN
  - LIKE (wildcards %, _)
  - IS NULL, IS NOT NULL
- [ ] **ORDER BY**
  - ASC, DESC
  - Multiple column sorting
- [ ] **LIMIT and OFFSET**

---

### Phase 5: Advanced SQL Queries (Week 9-10)

#### 5.1 Aggregate Functions
- [ ] **COUNT, SUM, AVG, MIN, MAX**
- [ ] **GROUP BY**
- [ ] **HAVING clause**
- [ ] **GROUP BY with multiple columns**
- [ ] **ROLLUP and CUBE** (MySQL 8.0+)

#### 5.2 Joins
- [ ] **Understanding Relationships**
- [ ] **INNER JOIN**
- [ ] **LEFT JOIN (LEFT OUTER JOIN)**
- [ ] **RIGHT JOIN (RIGHT OUTER JOIN)**
- [ ] **FULL OUTER JOIN** (MySQL alternatives)
- [ ] **CROSS JOIN**
- [ ] **SELF JOIN**
- [ ] **Multiple table joins**
- [ ] **Join performance considerations**

#### 5.3 Subqueries
- [ ] **Single-row subqueries**
- [ ] **Multiple-row subqueries**
- [ ] **Correlated subqueries**
- [ ] **EXISTS and NOT EXISTS**
- [ ] **Subqueries vs JOINs performance**

#### 5.4 Advanced SQL Features
- [ ] **UNION and UNION ALL**
- [ ] **CASE statements**
- [ ] **Common Table Expressions (CTE)** - MySQL 8.0+
- [ ] **Window Functions** - MySQL 8.0+
  - ROW_NUMBER(), RANK(), DENSE_RANK()
  - LEAD(), LAG()
  - SUM() OVER, AVG() OVER

---

### Phase 6: MySQL Advanced Features (Week 11-12)

#### 6.1 Indexes and Performance
- [ ] **Understanding Indexes**
- [ ] **Types of Indexes**
  - Primary Index
  - Secondary Index
  - Unique Index
  - Composite Index
  - Partial Index
- [ ] **CREATE INDEX**
- [ ] **Index optimization**
- [ ] **EXPLAIN statement**
- [ ] **Query optimization techniques**

#### 6.2 Views
- [ ] **Creating Views**
- [ ] **Updatable Views**
- [ ] **View security benefits**
- [ ] **Performance considerations**

#### 6.3 Stored Procedures and Functions
- [ ] **Stored Procedures**
  - Creating procedures
  - Parameters (IN, OUT, INOUT)
  - Control structures (IF, CASE, LOOP, WHILE)
- [ ] **Functions**
  - User-defined functions
  - Built-in functions
- [ ] **Triggers**
  - BEFORE/AFTER triggers
  - INSERT/UPDATE/DELETE triggers

#### 6.4 Transactions and Concurrency
- [ ] **ACID Properties**
  - Atomicity
  - Consistency
  - Isolation
  - Durability
- [ ] **Transaction Control**
  - START TRANSACTION
  - COMMIT
  - ROLLBACK
  - SAVEPOINT
- [ ] **Isolation Levels**
- [ ] **Locking mechanisms**
- [ ] **Deadlock handling**

---

### Phase 7: Database Administration Basics (Week 13-14)

#### 7.1 User Management and Security
- [ ] **Creating Users**
- [ ] **GRANT and REVOKE**
- [ ] **Role-based access control**
- [ ] **Password policies**
- [ ] **SSL connections**

#### 7.2 Backup and Recovery
- [ ] **mysqldump**
- [ ] **Binary logs**
- [ ] **Point-in-time recovery**
- [ ] **Backup strategies**

#### 7.3 Monitoring and Maintenance
- [ ] **Performance monitoring**
- [ ] **Log files analysis**
- [ ] **Database maintenance tasks**
- [ ] **MySQL Workbench monitoring**

---

### Phase 8: Practical Projects (Week 15-16)

#### 8.1 Project 1: E-commerce Database
- [ ] Design schema for products, customers, orders
- [ ] Implement relationships
- [ ] Create complex queries for reporting
- [ ] Add indexes for performance

#### 8.2 Project 2: Library Management System
- [ ] Design schema for books, members, borrowing
- [ ] Implement business logic with stored procedures
- [ ] Create views for different user roles
- [ ] Handle transactions for book lending

#### 8.3 Project 3: Analytics Dashboard
- [ ] Design schema for sales data
- [ ] Use window functions for analysis
- [ ] Create complex reports
- [ ] Optimize for performance

---

## 🔧 Recommended Tools and Resources

### Tools
- [ ] **MySQL Server** (Latest version)
- [ ] **MySQL Workbench** (GUI tool)
- [ ] **phpMyAdmin** (Web-based)
- [ ] **DBeaver** (Universal database tool)
- [ ] **Visual Studio Code** with MySQL extensions

### Online Resources
- [ ] MySQL Official Documentation
- [ ] W3Schools SQL Tutorial
- [ ] SQLBolt (Interactive SQL lessons)
- [ ] HackerRank SQL challenges
- [ ] LeetCode Database problems

### Books
- [ ] "Learning SQL" by Alan Beaulieu
- [ ] "MySQL Crash Course" by Ben Forta
- [ ] "High Performance MySQL" by Baron Schwartz

---

## 📋 Weekly Assessment Checklist

### Week 1-2: Database Fundamentals
- [ ] Can explain what a database is and why it's needed
- [ ] Can differentiate between types of databases
- [ ] Understands basic database concepts

### Week 3-4: MySQL Deep Dive
- [ ] Successfully installed and configured MySQL
- [ ] Understands MySQL architecture
- [ ] Can choose appropriate storage engines and data types

### Week 5-6: SQL Fundamentals
- [ ] Can create databases and tables
- [ ] Understands normalization principles
- [ ] Can write basic DDL statements

### Week 7-8: SQL Query Fundamentals
- [ ] Can write CRUD operations
- [ ] Masters basic SELECT queries with WHERE, ORDER BY, LIMIT
- [ ] Comfortable with data filtering and sorting

### Week 9-10: Advanced SQL Queries
- [ ] Can write complex queries with JOINs
- [ ] Masters aggregate functions and GROUP BY
- [ ] Understands and uses subqueries effectively

### Week 11-12: MySQL Advanced Features
- [ ] Can create and optimize indexes
- [ ] Understands transactions and concurrency
- [ ] Can write stored procedures and functions

### Week 13-14: Database Administration
- [ ] Can manage users and permissions
- [ ] Understands backup and recovery procedures
- [ ] Can monitor database performance

### Week 15-16: Practical Projects
- [ ] Completed at least 2 practical projects
- [ ] Can design normalized database schemas
- [ ] Can write complex queries for real-world scenarios

---

## 🎯 Daily Practice Routine

### Daily (30-60 minutes)
- [ ] Practice SQL queries on sample databases
- [ ] Read MySQL documentation
- [ ] Solve one SQL problem on HackerRank/LeetCode

### Weekly
- [ ] Complete assigned project milestones
- [ ] Review and refactor previous week's code
- [ ] Join MySQL/SQL community discussions

### Monthly
- [ ] Take practice exams
- [ ] Build a portfolio project
- [ ] Update learning progress and goals

---

## 🏆 Certification Paths

### Entry Level
- [ ] MySQL 8.0 Database Developer (1Z0-909)
- [ ] Oracle MySQL 5.7 Database Administrator (1Z0-888)

### Advanced
- [ ] Oracle Certified Professional MySQL 8.0 DBA
- [ ] Microsoft Certified: Azure Database Administrator Associate

---

## 📈 Completion Summary

### Learning Statistics
- **Total Learning Items**: 150+ checkboxes
- **Completion Rate**: 0% (Update as you progress)
- **Current Phase**: Phase 1 - Database Fundamentals
- **Estimated Completion Date**: _[Calculate based on your pace]_

### Weekly Progress Log
| Week | Phase | Items Completed | Notes |
|------|--------|----------------|--------|
| Week 1 | Phase 1 | 0/15 | _Record your progress here_ |
| Week 2 | Phase 1 | 0/15 | _Record your progress here_ |
| Week 3 | Phase 2 | 0/25 | _Record your progress here_ |
| Week 4 | Phase 2 | 0/25 | _Record your progress here_ |

### Achievements Unlocked
- [ ] 🎯 Completed first week of learning
- [ ] 📊 Installed and configured MySQL
- [ ] 💾 Created first database
- [ ] 🔍 Wrote first SELECT query
- [ ] 🔗 Mastered table joins
- [ ] ⚡ Optimized first query with indexes
- [ ] 🏗️ Completed first project
- [ ] 🎓 Ready for certification

---

*Last Updated: October 12, 2025*

