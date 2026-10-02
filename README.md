# Veda Technology - Task 25
## Multi-Table Sales Analysis

### Data Analytics Internship

This project was completed as part of the Veda Technology Data Analytics Internship.

## Student Details

- **Name:** R. Kaniga
- **Program:** B.Tech - Artificial Intelligence and Data Science
- **Department:** ARTIFICIAL INTELLIGENCE AND DATA SCIENCE
- **College:** Muthayammal Engineering College
- **Academic Period:** 2025-2029
- **Platform:** Google Colab

---

## Project Objective

The objective of this project is to combine orders, products and customers for business analysis using relational SQL queries and end-to-end data analysis.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- SQL
- SQLite
- Plotly
- Excel
- Google Colab
- Power BI

---

## Dataset Structure

The project contains four related tables:

### 1. Customers

Contains customer information such as:

- Customer ID
- Customer Name
- Region

### 2. Products

Contains product information such as:

- Product ID
- Product Name
- Category
- Unit Price

### 3. Orders

Contains:

- Order ID
- Customer ID
- Order Date

### 4. Order Items

Contains:

- Order ID
- Product ID
- Quantity
- Unit Price
- Sales

---

## Relationship Structure

```text
Customers
    |
    | CustomerID
    v
Orders
    |
    | OrderID
    v
Order_Items
    |
    | ProductID
    v
Products
