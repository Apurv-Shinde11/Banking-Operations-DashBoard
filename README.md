# Bank Operations Monitoring Panel

A Power BI dashboard designed to monitor and analyze key metrics across banking operations, including escalation trends, KYC status, SLA compliance, and case assignments.

## 📊 Dashboard Overview

This interactive dashboard offers a real-time visual summary of operational efficiency and compliance. It helps operations teams and analysts quickly identify bottlenecks, SLA breaches, and escalation patterns.

---

## ✅ Key Metrics (Cards)

- **Total Cases**: Displays the total number of cases in the system.
- **Open Cases**: Shows the count of currently open cases.
- **Escalated Cases**: Highlights the number of escalated cases.
- **SLA Breaches**: Indicates how many cases breached the Service Level Agreement.

---

## 📈 Visualizations

1. **Escalation Status by Assigned Staff**  
   _Column Chart_: View how escalation trends vary among staff members.

2. **KYC Status Breakdown**  
   _Pie Chart_: Distribution of KYC status across all cases (e.g., Verified, Pending).

3. **Case Status Breakdown**  
   _Donut Chart_: Highlights the proportion of Open, Closed, In-Progress, etc.

4. **Turnaround Time by Staff**  
   _Horizontal Bar Chart_: Helps identify slow case handlers by sorting average turnaround times.

5. **Cases Assigned by Staff**  
   _Column Chart_: Tracks workload distribution among the operations team.

6. **Status vs SLA Breach Count**  
   _Line Chart_: Shows SLA breaches with respect to each case status for compliance monitoring.

---

## 🛠️ Tools Used

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Relational Modeling & Data Transformation**

---

## 📁 File

- `Bank_Operations_Monitoring_Panel.pbix` – The full Power BI project file

---

## Notes

- This dashboard is currently a **static report**, built using a local `.pbix` file.
- If integrated with a Power BI Service or workspace and connected to a live data source, it can be refreshed periodically for real-time tracking.

---

## 🧠 Future Enhancements

- Live data integration via SQL or SharePoint
- Role-based access in Power BI Service
- Automated email alerts on SLA breaches

---
