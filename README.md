# Academic-Projects-Hands-on

A fully normalized relational database (3NF) for Khumbulekhaya Stokvel, a South African community financial organization. Built with Microsoft SQL Server—featuring 11 interconnected tables, stored procedures with error handling, performance indexing, and RBAC-ready security.

# 🏦 Khumbulekhaya Stokvel - Database Management System

## 📌 Project Overview

This project involved designing and implementing a **fully normalized relational database** for Khumbulekhaya Stokvel, a community-based financial organization registered under NASASA (National Stokvel Association of South Africa).

The database centralizes member management, savings tracking, investment portfolios, travel expense calculations, and business/skills repositories into a single, unified platform.

**Business Problem:** The Stokvel needed to move from disjointed spreadsheets to a centralized system that could track member contributions, generate reports, and provide real-time financial insights to the executive committee.

---

## 🛠️ Technologies Used

- **Microsoft SQL Server** (Database Engine)
- **SQL** (Data Definition, Data Manipulation, Stored Procedures)
- **SQL Server Management Studio (SSMS)** (Development Environment)

---

## 📊 Database Schema (11 Tables)

| Table | Purpose |
| :--- | :--- |
| `Member` | Stores member personal and contact information |
| `Savings` | Tracks individual member savings contributions |
| `Investments` | Records investment portfolios and performance metrics |
| `Transactions` | Logs all financial activities (deposits, withdrawals, investments) |
| `TravelExpenseCalculation` | Calculates travel-related expenses per member |
| `ExpenseGapBreaching` | Tracks shortfalls and gap breaches in member finances |
| `Trip` | Manages trip requests, destinations, and costs |
| `Vehicle` | Stores vehicle availability and trip history |
| `InvestmentProjection` | Forecasts investment returns over time |
| `Business` | Records businesses owned by members and income generated |
| `Skills` | Catalogues member skills for community collaboration |

---

## 🔧 Key Features

### ✅ Normalization (3NF)
- Designed to meet **1st, 2nd, and 3rd Normal Form** to eliminate data redundancy and ensure data integrity.

### ✅ Stored Procedures
- `AddNewMember` – Adds a new member with error handling
- `RecordTransaction` – Records deposits/investments and updates member totals
- `CalculateTotalExpenses` – Computes total travel expenses per member

### ✅ Views
- `MemberFinancialSummary` – Aggregates savings and investment data for reporting

### ✅ Performance Optimization
- Created **indexes** on frequently queried columns (`FullName`, `Date`, `InvestmentType`, `TransactionType`)

### ✅ Security & Access Control
- Designed with **Role-Based Access Control (RBAC)** in mind (administrators vs. members)

---

## 📂 ERD Diagram

> *<img width="975" height="511" alt="image" src="https://github.com/user-attachments/assets/e658776c-40fe-4ffe-a0d1-5bf5811b29a9" />*

---

## 🎯 What I Learned

- How to translate **business requirements** into a **relational data model**
- How to implement **referential integrity** using foreign keys
- How to write **stored procedures** with **TRY...CATCH error handling**
- How to optimize queries with **indexing** for performance
- How to document a full database project (ERD, Data Dictionary, SQL scripts)

---

## 👤 Author

**Oabusa Madubung**  
ICT Graduate | Belgium Campus iTversity  
[GitHub](https://github.com/ReignMad) | [LinkedIn](https://linkedin.com/in/oabusa-madubung)

---

**Last Updated:** March 2026
