# 🚆 **NOVA CP Trains - SQL Project Overview**

## **Project Summary**
The **NOVA CP Trains** project is a **SQL-based database management system** designed for a **fictitious train company** operating since **2023**. This project involves designing, implementing, and analyzing **a complex relational database** that efficiently handles train schedules, ticketing, pricing, and customer management.

### **Key Features:**
✅ **Entity-Relationship Model (ERM)** for **structuring the database**  
✅ **SQL queries for data storage, retrieval, and analysis**  
✅ **Trigger-based automation for pricing and logging changes**  
✅ **Data imports using Python-generated datasets** for **2023 & 2024**  
✅ **Views for customer & ticket information**  
✅ **Trend analysis** on passenger demographics and service usage  

---

## 📺 **Project Video Highlights**
🔗 [Watch the full video](https://youtu.be/clDh8p3XB_U)

---


## **📌 Key Features & Implementation**

### **Entity Relationship Model (ERM) & Database Design**
- The **database schema** models train operations, handling **schedules, routes, stops, and tickets**.
- Designed to support **many-to-many relationships** (e.g., **routes and stops**, **customers and tickets**).
- Implemented **reverse engineering scripts** to create tables efficiently.

### **Data Import & Processing**
- **Data from 2023-2024** generated using **Python algorithms** for realism.
- **CSV files loaded into MySQL** to populate database tables.

### **SQL Triggers & Automated Calculations**
- **Trigger-based price calculation** based on:
  - **Kilometers traveled**.
  - **Service class selected** (Economy, Business, etc.).
- **Triggers log changes in ticket purchases**, ensuring **automatic updates** in invoices and payments.

### **Views for Data Exploration**
- Created **two views**:
  - **Customer information view** (personal details, travel history).
  - **Ticket details view** (seat assignments, service classes).
- Used **Excel macros** to extract invoice data directly from views.

### **Service Trend & Customer Analysis**
- **Analyzed service evolution over time** (2023-2024).
- Identified **least popular routes** based on time and day.
- **Targeted younger passengers** (under 25) for potential student-focused marketing.

---

## **📌 What Could Be Improved? (Future Work)**
🚀 **Normalization Enhancements**: Further refine **one-to-many** relationships for better efficiency.  
🚀 **Performance Optimization**: Indexing strategies for **faster queries on large datasets**.  
🚀 **Stored Procedures**: Automate complex calculations (e.g., **dynamic fare adjustments**).  


