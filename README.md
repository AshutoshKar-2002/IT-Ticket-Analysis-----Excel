# 📊 IT Ticket Analysis — Excel
<img width="1666" height="970" alt="it_ticket_dashboard_title" src="https://github.com/user-attachments/assets/c44a9d48-66bc-4e1c-bcfa-16719b13a2d4" />



> An interactive Excel dashboard analyzing **97K+ IT support tickets** to understand ticket trends, resolution performance, agent workload, and customer satisfaction.

---

## 🎯 Project Overview

This project analyzes **97,498 IT support tickets** handled by **50 support agents** from **2016–2020**.

The goal was to understand:

- 📈 How ticket volume changed over time
- ⏱️ Where resolution time was highest
- 👥 How workload was distributed across agents
- ⭐ How customer satisfaction (CSAT) changed
- 🔎 Whether ticket severity was related to resolution time
- 🧑‍💻 Whether the existing workforce was being utilized effectively

The analysis uses Excel to turn raw ticket data into an **interactive dashboard with business-focused insights**.

---

## 🛠️ Tools & Skills

- Microsoft Excel
- Pivot Tables & Pivot Charts
- Slicers
- Conditional Formatting
- Data Cleaning & Validation
- Exploratory Data Analysis
- KPI Analysis
- Correlation Analysis
- `VLOOKUP`
- `MID`, `FIND`, `LEN`
- `COUNTA`, `AVERAGE`, `MAX`, `MIN`
- `CORREL`

---

## 📂 Dataset Overview

| Metric | Value |
|---|---:|
| 🎫 Total Tickets | **97,498** |
| 📅 Time Period | **2016–2020** |
| 👥 Support Agents | **50** |
| 📋 Attributes | **14** |
| ✅ Data Quality | **No missing/inconsistent values** |

### 🎫 Tickets by Category

| Category | Tickets |
|---|---:|
| 🖥️ System | 39,002 |
| 🔐 Login Access | 29,193 |
| 💻 Software | 19,570 |
| 🔧 Hardware | 9,733 |

---

## 📊 Dashboard KPIs

The dashboard provides a quick view of:

- 🎫 Total Tickets
- 👥 Total Support Agents
- ⏱️ Average Resolution Time
- ⚡ First Response Time
- ⭐ Customer Satisfaction (CSAT)
- 👤 Agent-wise Performance
- 🚩 Underperforming Agents

---

## 🔍 Key Insights

### 🎫 Ticket Volume
- Analyzed **97K+ tickets** handled by **50 agents** over 5 years.
- **System-related requests** were the largest category with **39,002 tickets**.
- Ticket volume increased by approximately **123%** during the analysis period.

### ⏱️ Resolution Time
- Overall average resolution time was **4.55 days**.
- **Hardware:** ~**7.63 days**
- **Software:** ~**5.24 days**
- **System:** ~**6.62 days**
- **Login Access:** ~**0.31 days**

### ⭐ Customer Satisfaction
- CSAT remained above **4.0** overall.
- CSAT increased from **3.98 in 2016** to **4.16 in 2020**, despite the increase in ticket volume.

### 🔎 Severity vs Resolution Time
- Correlation between severity and resolution time was approximately **-0.04**.
- This indicates that severity and resolution time had **almost no linear relationship** in this dataset.

---

## 💡 Business Recommendations

Based on the analysis:

- 🔄 Reallocate resources toward categories with longer resolution times.
- 🔧 Focus on improving processes around **Hardware** and other slower-moving categories.
- 📚 Provide targeted training and support where performance gaps are identified.
- 📊 Monitor ticket volume, resolution time, and CSAT together rather than looking at a single KPI.
- 🔁 Use the dashboard as a recurring performance-monitoring tool.

---

## ✨ What I Built

### 1️⃣ Data Preparation
Cleaned and validated the raw ticket data before analysis.

### 2️⃣ Exploratory Analysis
Analyzed ticket categories, volume trends, resolution time, CSAT, and agent performance.

### 3️⃣ Interactive Dashboard
Created an Excel dashboard using **Pivot Tables, Pivot Charts, Slicers, and Conditional Formatting**.

### 4️⃣ Performance Analysis
Compared agent workload and performance and created a threshold-based approach for identifying agents requiring further review.

### 5️⃣ Business Insights
Converted the analysis into practical observations and recommendations for improving support operations.

---

## 📁 Repository Structure

```text
IT-Ticket-Analysis-Dashboard/
│
├── 📊 IT Ticket Analysis Dashboard & Charts (.xlsx)
├── 📑 IT Ticket Analysis PPT (.ppt)
├── 📝 IT Ticket Analysis-QA (.docx)
└── 📄 README.md
