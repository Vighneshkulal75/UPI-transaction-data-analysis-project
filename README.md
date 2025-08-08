# 📊 UPI Transactions Data Analysis – Power BI

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiYWE2Y2RmNmYtYWE2ZS00OTAyLWE3YWYtZjgzMTk5MWI3MDUyIiwidCI6ImY1OTJlZjFjLWI1OGQtNDY0Zi1iZDFkLWY3MGU2NWU3MDRiYSJ9

## 📌 Overview
This project dives deep into **UPI (Unified Payments Interface)** transaction data to understand financial trends and consumer behavior in India’s booming digital payment space.  
The analysis is structured in **phases** to build a clean, reliable, and interactive dashboard for stakeholders.

---

## 🛠 Skills Demonstrated
- **Data Cleaning & Profiling** (Power Query)
- **Interactive Dashboards** (Slicers, Bookmarks, Visual Syncing)
- **Advanced Reporting Techniques** (Conditional Formatting, Drill-through)
- **Domain Understanding** (Digital Payments, UPI transaction trends)

---

## 📂 Dataset
- **Source:** UPI transactions dataset (Excel format)
- **Key Columns:**  
  `Transaction_ID`, `Date`, `Amount`, `Remaining_Balance`, `Gender`, `City`, `Bank`, `Merchant`, `Device_Type`
- **Size:** ~1.6–1.7M transactions/month

---

## 📈 Project Workflow

### **Step 1 – Loading & Transforming UPI Data**
- Imported dataset from Excel into Power BI Desktop.
- Selected the correct data sheet and reviewed column meanings.
- Adjusted data types (e.g., account numbers from exponential → text).
- **Takeaway:** Understanding data early prevents ambiguity in later stages.

---

### **Step 2 – Data Profiling for Integrity**
- Switched profiling mode to **Entire Data** for accurate stats.
- Used:
  - **Column Distribution** to see value spread.
  - **Column Quality** to find nulls.
  - **Column Profile** to identify outliers.
- **Takeaway:** Clean data = reliable visuals = stronger insights.

---

### **Step 3–4 – Preparation Before Visualization**
- Performed:
  - Removal of duplicates.
  - Standardization of merchant & city names.
  - Creation of calculated columns (e.g., Age Groups).
- **Takeaway:** 80% of analysis is prep. Do it before plotting.

---

### **Step 5–6 – Analytical Tools**
- Used slicers, filters, and pivot-like visuals to:
  - Break down data by **city**, **gender**, **merchant**, and **device type**.
  - Empower stakeholders to self-serve insights.
- **Takeaway:** Interactive filters make dashboards actionable.

---

### **Step 7–8 – Enhancing the Reporting Experience**
- Added:
  - **Bookmarks** for quick switching between “Transactions” & “Remaining Balance” views.
  - **Selection Pane** for clean toggle control.
  - **Line & Column Charts** for monthly trends.
- Highlighted **Bangalore, Delhi, Mumbai, Hyderabad** for comparison.

---

## 📊 Final Dashboard Output
**Main Insights:**
- Monthly UPI transaction volume: **~1.6M–1.7M/month**.
- Wallet balances drop significantly mid-month.
- Young adults and metro cities lead transaction volume.
- Top merchants dominate ~40% of all transactions.

<img width="1232" height="700" alt="Image" src="https://github.com/user-attachments/assets/7f3eed51-2f85-4088-b2b3-60507c5c468e" />



<img width="1232" height="699" alt="Image" src="https://github.com/user-attachments/assets/a8e06432-a429-40d3-9748-3a945b8297f0" />
