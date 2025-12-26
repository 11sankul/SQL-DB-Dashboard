# 🏫 School Analytics Dashboard  
*A Data-Driven Portfolio Project using SQL, JavaScript & Chart.js*

---

## 📌 Project Overview

The **School Analytics Dashboard** is a full-stack, data-driven analytical web application designed to transform raw school-level operational data into **actionable insights**.

This project simulates a **real-world analytics use case** where decision-makers (school management, consultants, investors, or education authorities) can evaluate **financial performance, staffing efficiency, capacity utilization, and geographic distribution** of schools.

The dashboard works **entirely on structured data**, using SQL queries executed in-browser and rendered visually using charts and KPIs.

---

## 🎯 Objectives

- Convert raw school data into meaningful KPIs  
- Perform **financial and operational analysis** using SQL  
- Visualize insights clearly using interactive charts  
- Demonstrate end-to-end analytics workflow (Data → SQL → Insights → UI)  
- Build a **portfolio-ready analytics case study**

---

## 🧱 Architecture & Tech Stack

### Frontend
- **HTML5 / CSS3**
- **Modern Glassmorphism UI**
- **Chart.js (v4)** for data visualization

### Data & Logic
- **SQLite database**
- **sql.js** (SQLite running fully in browser)
- Raw dataset contains **35+ schools** with financial, staff, capacity & location data

### Version Control
- **Git**
- **GitHub** (project documentation + code)

---

## 📊 Dashboard Structure

The dashboard is divided into **4 functional pages**:

---

## 1️⃣ Overview Page (Executive Summary)

### KPIs
- **Total Schools**
- **Total Students**
- **Total Revenue (₹ Crores)**
- **Average Fees**

### Charts
- 📍 **Schools Count by District**
- 📚 **Students by Board**
- 🏆 **Top 10 Schools by Revenue**
- 💵 **Fee Distribution (Budget → Premium)**

📌 *Purpose:*  
Quick snapshot for leadership to understand scale, reach, and revenue concentration.

---

## 2️⃣ Financial Page (Business Health)

### KPIs
- **Total Expenses**
- **Total Profit**
- **Average Profit Margin**
- **Number of Profitable Schools**

### Charts
- 💰 **Revenue vs Expenses (Top Schools)**
- 📊 **Top Profit-Making Schools**

### Table
- 🏆 **Most Profitable Schools**
  - Revenue
  - Expenses
  - Net Profit

📌 *Purpose:*  
Identify financially strong schools and compare cost vs income efficiency.

---

## 3️⃣ Staff Page (Operational Efficiency)

### KPIs
- 👨‍🏫 **Total Teaching Staff**
- 👥 **Total Non-Teaching Staff**
- 📊 **Average Student–Teacher Ratio**
- 🎯 **Total Student Capacity**

### Charts
- 👥 **Staff Distribution (Teaching vs Non-Teaching)**
- 📊 **Capacity vs Enrollment Analysis**

### Table
- 📋 **Top Schools by Capacity & Occupancy**

📌 *Purpose:*  
Evaluate staffing adequacy, workload balance, and capacity utilization.

---

## 4️⃣ SQL Query Tool (Advanced Analysis)

- Execute **custom SQL queries directly on the dataset**
- Predefined quick queries:
  - All schools
  - Top students
  - Profitable schools
  - District-wise analysis

📌 *Purpose:*  
Demonstrates **hands-on SQL proficiency** and exploratory data analysis skills.

---

## 🧠 Key Insights Enabled

- Revenue is **highly concentrated** among a few CBSE schools
- Several schools operate with **low occupancy despite high capacity**
- Profit margins vary significantly even among similar fee ranges
- Student–teacher ratios highlight **staffing imbalance** in some institutions

---

## 📁 Dataset Highlights

The dataset includes (but is not limited to):

- School board (CBSE, ICSE, State Board)
- Student count & capacity
- Fee structure (min, max, average)
- Total revenue & salary expenses
- Teaching & non-teaching staff counts
- Profit / loss calculations
- District, area, and establishment year

All calculations are derived dynamically using SQL queries.

---

## 🚀 How to Run the Project

1. Clone the repository
   ```bash
   git clone <repo-url>
