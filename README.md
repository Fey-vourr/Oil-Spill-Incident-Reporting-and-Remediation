# 🛢️ Oil Spill Incident Reporting & Remediation Dashboard

## 📌 Project Overview
This repository contains an automated end-to-end data analytics solution designed to track, analyze, and visualize oil spill incidents and remediation efforts across various Local Government Areas (LGAs) in **Rivers State, Nigeria**. The interactive dashboard provides key insights into **spill cleanup turnaround times**, **incident volumes by location**, and overall environmental remediation efficiency to support data-driven decision-making in the energy and environmental sectors.

---

## 🔑 Key Features
* **Turnaround Time Tracking:** Calculates and monitors the duration between initial incident reporting and complete remediation.
* **Geospatial & LGA Analysis:** Maps incident volumes across different LGAs in Rivers State to identify high-risk zones.
* **Automated Workflow:** Built to process and refresh data smoothly from raw input to final visual reporting.
* **Interactive Drill-downs:** Allows users to filter by LGA, incident severity, date ranges, and operational status.
  
---

## 🛠️ Data Pipeline & Tech Stack
Python (Data Generation)
│
▼
Power Query (ETL & Transformation)
│
▼
Power BI & DAX (Modeling & Visualization)
* **Python:** Generated synthetic datasets simulating realistic HSE oil spill telemetry and operational records.
* **Power Query:** Performed ETL processes including data cleaning, handling missing values, column standardization, and schema structuring.
* **Power BI & DAX:** Constructed a star schema model and wrote custom DAX measures for turnaround calculations, rolling metrics, and KPI visualizations.

---

## 💡 What I Learned

Building this end-to-end HSE analytics solution strengthened both my technical data engineering capabilities and domain knowledge in environmental management:

* **End-to-End Data Pipeline Architecture:** Gained hands-on experience structuring a project from mock data creation in Python to ETL processing in Power Query and final delivery in Power BI.
* **Advanced DAX & Business Logic:** Learned how to write performant DAX measures for calculating turnaround times, handling business day logic, and modeling metrics across custom calendar tables.
* **HSE & ESG Domain Insight:** Deepened my understanding of key environmental safety metrics, regulatory remediation workflows, and how geography influences incident response times in regions like Rivers State.
* **Data Modeling Best Practices:** Reinforced star-schema database design principles to ensure fast dashboard performance and seamless interactive filtering.

---

## 📊 Business Impact
* **Improved Response Times:** Highlights bottleneck LGAs to optimize cleanup and remediation workflows.
* **Regulatory & ESG Compliance:** Delivers audit-ready visual reporting on environmental impact and recovery milestones.
* **Resource Allocation:** Enables environmental management teams to strategically deploy cleanup resources to heavily impacted areas.

---

## 🚀 How to View & Use
1. Clone this repository:
   ```bash
   git clone [https://github.com/Fey-vourr/oil-spill-incident-reporting-and-remediation.git](https://github.com/Fey-vourr/oil-spill-incident-reporting-and-remediation.git)
