# Software Project

Customer Purchasing Pattern Analysis System Using Data Mining Techniques

## Overview

**Customer Purchasing Pattern Analysis System** is a desktop-based Decision Support System developed as a graduation project. The system analyzes customer transaction data to discover hidden purchasing patterns and relationships between products using Data Mining techniques.

The system applies data mining techniques, primarily the **Apriori Association Rule Mining algorithm**, to identify frequently purchased item combinations and generate meaningful association rules. These insights help businesses understand customer buying behavior, improve product placement, optimize marketing strategies, and support data-driven decision making.

## Objectives

- Analyze customer purchasing behavior.
- Discover frequent itemsets from transaction data.
- Generate association rules between products.
- Identify customer purchasing patterns.
- Support business decision-making through data analysis.
- Visualize purchasing trends using reports and charts.

## Features

- User Authentication
- Customer Management
- Product Management
- Sales Transaction Management
- Market Basket Analysis
- Association Rule Mining (Apriori Algorithm)
- Frequent Itemset Discovery
- Purchasing Pattern Analysis
- Interactive Dashboard
- Statistical Reports & Charts
- Decision Support System

## System Modules

### 1. User Authentication
- User login
- User account management
- Role-based access (Administrator / User)

### 2. Customer Management
- Add, edit, and delete customer records
- Search customer information
- View customer profiles

### 3. Product Management
- Manage product categories
- Add, edit, and delete products
- Maintain product pricing and inventory information

### 4. Sales Transaction Management
- Record customer purchases
- Manage invoices and transaction history
- Import transaction datasets

### 5. Data Mining Module
- Execute the Apriori algorithm
- Generate frequent itemsets
- Discover association rules
- Configure Support & Confidence values

### 6. Purchasing Pattern Analysis
- Analyze customer buying behavior
- Identify frequently purchased product combinations
- Detect purchasing trends and relationships

### 7. Reports and Visualization
- Sales reports
- Customer purchasing reports
- Association rule reports
- Frequent itemset reports
- Statistical charts and graphs

### 8. Decision Support Dashboard
- Key sales statistics
- Top-selling products
- Most frequent purchasing patterns
- Business insights and recommendations

## Data Mining Techniques

- Association Rule Mining
- Apriori Algorithm
- Frequent Itemset Mining
- Market Basket Analysis

## Technologies

| Category | Technology |
|----------|------------|
| Programming Language | C++ |
| User Interface | Microsoft Foundation Classes (MFC) |
| IDE | Microsoft Visual Studio 2005 |
| Database | Microsoft SQL Server 2005 |
| Database Connectivity | ODBC |
| Operating System | Windows XP Professional |

## System Architecture

```text
+-------------------------+
| Customer Transactions   |
+------------+------------+
             |
             v
+-------------------------+
| SQL Server Database     |
+------------+------------+
             |
             v
+-------------------------+
| Data Preprocessing      |
+------------+------------+
             |
             v
+-------------------------+
| Apriori Algorithm       |
| Association Rule Mining |
+------------+------------+
             |
             v
+-------------------------+
| Pattern Analysis        |
+------------+------------+
             |
             v
+-------------------------+
| Reports & Dashboard     |
+-------------------------+
```

## System Workflow

```text
Sales Transactions
        │
        ▼
Transaction Database
        │
        ▼
Data Preprocessing
        │
        ▼
Apriori Algorithm
        │
        ▼
Frequent Itemsets
        │
        ▼
Association Rules
        │
        ▼
Reports & Dashboard
```

## Sample Dataset

| Transaction ID | Purchased Items |
|----------------|-----------------|
| 1001 | Bread, Milk, Butter |
| 1002 | Milk, Eggs |
| 1003 | Bread, Butter, Tea |
| 1004 | Bread, Milk, Eggs |
| 1005 | Tea, Sugar, Milk |

## Sample Output

After analyzing customer transaction data, the system generates frequent itemsets and association rules that reveal purchasing patterns.

### Frequent Itemsets

| Itemset | Support |
|---------|---------:|
| Milk, Bread | 32% |
| Bread, Butter | 25% |
| Tea, Sugar | 22% |
| Milk, Eggs | 19% |
| Bread, Butter, Jam | 15% |

### Association Rules

| Rule | Support | Confidence |
|------|---------:|-----------:|
| Milk → Bread | 32% | 76% |
| Bread → Butter | 25% | 71% |
| Tea + Sugar → Milk | 18% | 69% |
| Bread + Butter → Jam | 15% | 72% |
| Eggs → Milk | 19% | 68% |

## Project Outcomes

The system provides valuable insights into customer purchasing behavior by identifying hidden relationships among products. These insights can help businesses:

- Discover hidden relationships between products.
- Improve product placement strategies.
- Increase cross-selling opportunities.
- Support marketing campaign planning.
- Understand customer buying habits.
- Analyze customer purchasing behavior.
- Support strategic business decisions through data-driven analysis.
- Decision support for marketing and inventory planning.

## Solution Folder Structure

```text
CustomerPurchasingPatternAnalysisSystem/
│
├── Documentation/
│   ├── Project Report.pdf
│   ├── SRS.pdf
│   └── Presentation.ppt
│
├── Database/
│   ├── Database.sql
│   ├── SampleData.sql
│   └── ERD.png
│
├── Source/
│   ├── CustomerPatternAnalysis.sln
│   ├── BusinessLogic/
│   ├── DataAccess/
│   ├── DataMining/
│   ├── Reports/
│   └── UI/
│
└── Screenshots/
```