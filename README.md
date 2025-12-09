# 🚀 ER360 – Hospital Emergency Room Analytics Dashboard

---

## 🌐 Overview
**ER360** is a complete Power BI dashboard designed to analyze Emergency Room (ER) operations.  
It converts raw hospital and patient flow data into actionable insights — ideal for hospital admins, analysts, BI developers, and decision-makers.

---

## ⭐ Key Features
- ⏱️ **Waiting Time Insights** – Avg wait time, triage delay, treatment time  
- 🛏️ **Bed Utilization** – Occupancy %, available vs. occupied beds  
- 🧑‍⚕️ **Staff Workload Analysis** – Doctor/Nurse allocation, patient-to-staff ratio  
- 🚑 **Patient Flow Tracking** – Arrival patterns, triage levels, discharge trends  
- 📈 **Operational KPIs** – ER turnaround time, treatment efficiency  

---

## 🧱 Architecture
```
   ┌────────────────────────┐
   │      Data Sources       │
   │ CSV • Excel • SQL DB    │
   └────────────┬───────────┘
                │
   ┌────────────▼────────────┐
   │     Power Query (ETL)    │
   │ Clean • Transform • Merge│
   └────────────┬────────────┘
                │
   ┌────────────▼────────────┐
   │   Data Model (Star)      │
   │ Fact Patients / Dim Staff│
   └────────────┬────────────┘
                │
   ┌────────────▼────────────┐
   │        Power BI          │
   │  KPIs • Charts • Gauges  │
   └──────────────────────────┘
```

---

## ⚙️ Installation & Setup

### **1️⃣ Open the Dashboard**
```
Hospital ER Dashboard.pbix
```

### **2️⃣ Connect Your Data**
Compatible with:
- Excel  
- CSV  
- SQL Database  

### **3️⃣ Refresh the Data Model**
**Home → Refresh**

---

## 🖼️ Sample Dashboard
<img width="821" height="496" alt="Hospital" src="https://github.com/user-attachments/assets/d95144fe-9fe7-439b-83db-92cf0a3bd11d" />

**Hospital ER Dashboard Preview**

---

## 🏷️ Badges
![Power BI](https://img.shields.io/badge/Power%20BI-Visualization-F2C811?logo=power-bi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-1F6FEB)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-008272)
![Data Modeling](https://img.shields.io/badge/Data%20Modeling-Star%20Schema-blue)
![Status](https://img.shields.io/badge/Status-Active-success)


---

## 🧠 Skills Demonstrated
- Power BI Advanced Dashboarding  
- Healthcare Analytics  
- DAX Calculations & Time Intelligence  
- Power Query Data Cleaning  
- Data Modeling (Star Schema)  
- Performance Optimization  
- KPI Design & UI/UX Principles  

---

## 🧩 Roadmap
- Add Drillthrough for Patient Details  
- Add RLS (Role Level Security)  
- Add Forecasting using AI Insights  
- Add Real-time Streaming Data  
- Mobile Layout Optimization  

---

## 📘 Documentation
A complete **Step-by-Step PDF Guide** is included with:  
- Data preparation  
- Modeling approach  
- DAX calculation logic  
- Visual design best practices  
- Publishing & sharing  

---

## 🤝 Contributing
Have ideas to improve this dashboard?  
Feel free to open issues or submit pull requests.

---

## ⭐ Support This Project
If you found this project helpful, consider giving it a ⭐ on GitHub — your support motivates further improvements!.

---

## 👨‍💻 About the Author
Hi, I’m **Loganathan**, a Data Analyst & Power BI Developer passionate about turning complex hospital data into actionable insights.  
Thank you for exploring this project — Happy Learning! 🎉📚  

📩 **Contact:**  
**loganathanvizasia@gmail.com**
